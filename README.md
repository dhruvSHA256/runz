# runz

An interactive fuzzy interface for runz, using [sk](https://github.com/lotabout/skim) or [fzf](https://github.com/junegunn/fzf)

## Usage

- just run script, select service, then select action

## Installation

- Clone the [repo](https://github.com/dhruvsha256/runz) and copy `runz` to your `$PATH`
- change `USERSVDIR` and `ROOTSVDIR`

## Customization

- fuzzy handler can be changed by setting `FUZZYHANDLER` in script (default is sk)
- command used for getting root permissions can be changed by setting `SUDO` in script
  (default is doas)
- path to both user and root level runit services can be changed by changing `USERSVDIR`
  and `ROOTSVDIR` variable respectively

## TODO
- preview
