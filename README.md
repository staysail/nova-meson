# [Meson Build][1] Syntax for [Nova][2]

More information about the plugin can be found in the
`Meson.novaextension` directory.

This implemented using [Tree-sitter][3].

## Building

If you want to build this, you will need the tree-sitter-meson
repository, and will need to build the parser using the
supplied compile.sh and Makefile.

1. git clone https://github.com/staysail/tree-sitter-meson
2. ./compile.sh ./tree-sitter-meson/Applications/Nova.app
3. cp build/*.dylib ./Meson.novaextension/Syntaxes

[1]: https://mesonbuild.com "Meson Build website"
[2]: https://nova.app "Nova website"
[3]: https://tree-sitter.github.io "Tree-sitter website"