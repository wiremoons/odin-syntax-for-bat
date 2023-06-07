# About 'bat Odin Syntax'

Install *Odin* language syntax highlighting support for use with the command 
line tool called [bat](https://github.com/sharkdp/bat) created by @sharkdp

> bat : A cat(1) clone with syntax highlighting and Git integration.


## Purpose

To provide an [Odin](https://odin-lang.org) language syntax 
highlighting support file, that works with [bat](https://github.com/sharkdp/bat).


## Installation and Usage

Only the single file: [Odin.sublime-syntax](https://github.com/wiremoons/odin-syntax-for-bat/blob/main/Odin.sublime-syntax) is required!

### Download
Download either by:

a) cloning this whole repo : `git clone https://github.com/wiremoons/odin-syntax-for-bat.git` **or** 

b) just download the single syntax support file directly to your computer with a tool such as curl or wget : `curl -OL https://raw.githubusercontent.com/wiremoons/odin-syntax-for-bat/main/Odin.sublime-syntax`


## Install
Once you have a copy of the `Odin.sublime-syntax` file, use it with `bat` as follows:

### Ubuntu (Linux)

To install `bat` use the distro package manager (ie `sudo apt install bat`) or download it from: [bat](https://github.com/sharkdp/bat). Once installed, to add Odin language support:

1. Save a copy of the `Odin.sublime-syntax` from this repo into the following 
directory: `~/.config/bat/syntaxes/`
2. Run the following `bat` command: `bat cache --build`
3. Check Odin is now included in the list when running: `bat --list-languages`

Now when viewing an Odin language source code file, syntax highlighting should 
be supported.

### Appple macOS

To install `bat` the popular *macOS* package manager [HomeBrew](https://brew.sh) can be used (ie `brew install bat`) or download it from: [bat](https://github.com/sharkdp/bat). Once installed, to add Odin language support:

1. Save a copy of the `Odin.sublime-syntax` from this repo into the following 
directory: `~/.config/bat/syntaxes/`
2. Run the following `bat` command: `bat cache --build`
3. Check Odin is now included in the list when running: `bat --list-languages`

Now when viewing an Odin language source code file, syntax highlighting should 
be supported.

### Windows 10

To install `bat` on Windows, see the help here: [bat](https://github.com/sharkdp/bat). Once installed, to add Odin language support:

1. With `bat.exe` installed run the command: `bat --config-dir`. This location is the `bat.exe` config directory location.
2. Change to the `bat.exe` config directory (as above) and make a new directory called: `syntaxes`.
3. Save a copy of the `Odin.sublime-syntax` from this repo into the newly created `syntaxes` directory.
4. Run the following `bat.exe` command: `bat.exe cache --build`
5. Check Odin is now included in the list when running: `bat --list-languages`

Just for clarity - on my *Windows 10* computer with a username of *simon* the full path of the 
required `syntaxes` directory is: `C:\Users\simon\AppData\Roaming\bat\syntaxes\` and this is 
where the a copy of the `Odin.sublime-syntax` file from this repo should be saved. The 
username (ie `simon`) will be diffrent of course for your computer! Then run the 
command: `bat cache --build` to complete the process.

Now when viewing an Odin language source code file, syntax highlighting should 
be supported.
 
More complete instructions on using and adding a new syntax files with `bat` are 
included in the [Bat Readme document](https://github.com/sharkdp/bat#adding-new-syntaxes--language-definitions).


## Acknowledgements

The `Odin.sublime-syntax`file was created by @gingerBill and is made availble from his repo here: [sublime-odin](https://github.com/odin-lang/sublime-odin/tree/master)

As well as being kind enough to create this syntax highlighting file, @gingerBill then went on and made a whole language and complier to go with!! Be sure to visit the [Odin](https://github.com/odin-lang/Odin) GitHub repository and give it a ⭐️ - then learn more about [Odin](https://odin-lang.org) and "*enjoy program again*".


## License

The files are provided under the MIT open source license. A copy of the 
MIT license file is [here](./LICENSE).

The files in the repository are licensed under the **MIT License** that also 
respects the original licences used in @gingerBill's repo that when last checked is MIT 
as well.
