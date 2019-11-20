# Code-0 repository

## Cloning this repository

Please add the `--recurse-submodules` option when cloning this repository: this will ensure the correct documentation is included. If you've already cloned this repo, you should add the submodules with:

```zsh
git submodule update --init --recursive
```

The size of the checkout directory should increase afterwards. Example:

```zsh
code-0 on  develop
➜ du -hs
83K     .
code-0 on  develop
➜ git submodule update --init --recursive
Submodule 'documentation-0' (https://github.com/morancj/documentation-0.wiki.git) registered for path 'documentation-0'
Cloning into '/home/ciaran/Git/GitHub/morancj/wiki-submodule-test/temp/code-0/documentation-0'...
Submodule path 'documentation-0': checked out '2946f9e2e182708c66ae60b316ed7eb56df7dbd9'
code-0 on  develop
➜ du -hs
123K     .

code-0 on  develop
➜
```

## Documentation

Please see the `git submodule` `documentation-0`: this will take you to the current wiki.

If you're reading this on GitHub's preview under the `Code` view, you can click `documentation-0` above. Otherwise, you must use this link: [documentation-0](https://github.com/morancj/documentation-0/wiki).

## Configuring your Visual Studio Code Workspace

If you're new to `git submodules`, you should hide the `documentation-0` directory in the workspace. To do so, add `documentation-0/**` to `files.exclude`.

See also: blah.
