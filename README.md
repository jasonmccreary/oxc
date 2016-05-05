# oxc

Type `oxc` to open Xcode with a workspace, project, or file from the command line.

## Usage
    oxc [file]

### Examples
    $ oxc README.md
    > open README.md in Xcode

    $ oxc
    > if the current directory contains a workspace or project, open it in Xcode
    > otherwise, just open Xcode

## Installation

```sh
npm install --global oxc
```

If you don't want to [install Node](https://nodejs.org/), you can simply download [oxc](https://raw.githubusercontent.com/jasonmccreary/oxc/master/oxc) to a directory in your `PATH`.

## License

Copyright Jason McCreary. Licensed under MIT.

http://opensource.org/licenses/MIT
