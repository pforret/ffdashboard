![bash_unit CI](https://github.com/pforret/ffdashboard/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/pforret/ffdashboard/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/pforret/ffdashboard)
![GH stars](https://img.shields.io/github/stars/pforret/ffdashboard)
![GH tag](https://img.shields.io/github/v/tag/pforret/ffdashboard)
![GH License](https://img.shields.io/github/license/pforret/ffdashboard)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://www.basher.it/package/)

# ffdashboard

Firefox dashboard showing URLs in a loop

## 🔥 Usage

```
Program : ffdashboard  by peter@forret.com
Version : v0.0.2 (2022-11-07 20:53)
Purpose : Firefox dashboard showing URLs in a loop
Usage   : ffdashboard [-h] [-q] [-v] [-f] [-k] [-l <log_dir>] [-t <tmp_dir>] [-d <delay>] [-b <browser>] <action> <input?>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] also show debug messages [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -k|--kiosk       : [flag] run in kiosk mode (full screen) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: ./log]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: ./.tmp]
    -d|--delay <?>   : [option] seconds between each URL  [default: 30]
    -b|--browser <?> : [option] browser to use (firefox/chrome)  [default: firefox]
    <action>         : [choice] action to perform  [options: show,url,check,env,update]
    <input>          : [parameter] input file (optional)
                                  @github.com:pforret/ffdashboard.git
### TIPS & EXAMPLES
* use ffdashboard show [file] to show list of URLs in a loop
  ffdashboard show urls.txt
* use ffdashboard url to ...
  ffdashboard url
* use ffdashboard check to check if this script is ready to execute and what values the options/flags are
  ffdashboard check
* use ffdashboard env to generate an example .env file
  ffdashboard env > .env
* use ffdashboard update to update to the latest version
  ffdashboard update
* >>> bash script created with pforret/bashew
* >>> for bash development, also check IO:print pforret/setver and pforret/IO:progressbar
```

## ⚡️ Examples

```bash
> ffdashboard -d 60 show urls.txt
# show each url for 60 seconds in a endless loop
```

## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install pforret/ffdashboard

or with `git`

	$ git clone https://github.com/pforret/ffdashboard.git
	$ cd ffdashboard

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2022 Peter Forret
