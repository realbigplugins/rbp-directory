# rbp-directory
Plugin Directory Addon for Real Big Plugins

This should be included within our plugins as a [Git Submodule](https://git-scm.com/docs/git-submodule).

`git submodule add https://github.com/realbigplugins/rbp-directory.git ./path/to/wherever/you/want/it`

This creates a `.gitmodules` file that will be commited to the Plugin's Repository. The Submodule files don't actually get tracked within the Plugin's Repository.

Depending on your Git version, you may also have to run `git submodule update --init --recursive`. This command is also useful if this Submodule updates and the Plugin needs to include the most recent version.

Now whenever you want to clone the plugin (main/parent) repository, you will want to run `git clone --recursive`
