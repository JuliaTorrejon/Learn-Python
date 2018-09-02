`/dist` means "distribution", the compiled code/library.
Folder structure varies by build system and programming language. Here are some standard conventions:

`src/`: "source" files to build and develop the project. This is where the original source files are located, before being compiled into fewer files to `dist/`, `public/` or `build/`.
`dist/`: "distribution", the compiled code/library, also named `public/` or `build/`. The files meant for production or public use are usually located here.
`lib/`: external dependencies (when included directly).
`test/`: the project's tests scripts, mocks, etc.
`vendor/`: dependencies are usually put here via dependency management.
`bin/`: files that get added to your PATH when installed.

Markdown/Text Files:
`README.md`: A help file which addresses setup, tutorials, and documents the project. `README.txt` is also used.
`LICENSE.md`: any [rights](https://choosealicense.com/no-permission/) given to you regarding the project. `LICENSE` or `LICENSE.txt` are variations of the license file name, having the same contents.
`CONTRIBUTING.md`: how to [help out](https://github.com/blog/1184-contributing-guidelines) with the project. Sometimes this is addressed in the README.md file.

Specific (these could go on forever):
`package.json`: describes library and dependencies (if a JS package).
`composer.json`: same as above but for PHP packages via composer.
`.travis.yml`: config file for the [Travis CI](https://travis-ci.com/) environment.
`.gitignore`: Specification of the files meant [to be ignored](https://help.github.com/articles/ignoring-files/) by Git.
