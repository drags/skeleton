<p><img src="https://www.circonus.com/wp-content/uploads/2015/03/sol-icon-itOps.png" alt="graph logo" title="graph" align="right" height="60" /></p>

# Cloud Alchemy Ansible Role Skeleton

[![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](https://opensource.org/licenses/MIT)
[![IRC](https://img.shields.io/badge/irc.freenode.net-%23cloudalchemy-yellow.svg)](https://kiwiirc.com/nextclient/#ircs://irc.freenode.net/#cloudalchemy)

## Description

Skeleton to create new ansible roles similar to other Cloud Alchemy roles.

## How to use it

To create a new role, just follow a couple of easy steps:
1. Clone this repo
1. Open `create.sh` with your favorite editor
1. Modify variables mentioned in that file
1. Run `create.sh`

## Result

After running `create.sh` it will convert this repo into a directory structure with everything needed to start 
developing new Cloud Alchemy ansible role.

## Warnings

- Running `create.sh` deletes `.git` directory.
- README.md file is overwritten with ROLE_README.md

## License

This project is licensed under MIT License. See [LICENSE](/LICENSE) for more details.
