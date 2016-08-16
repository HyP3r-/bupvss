# bupvss 0.1

Creating with bup, cygwin and volume shadow copy backups

## Requirements

This script was made for a cygwin enviroment. For proper work you need `bup`, which you may have to compile by hand, `par2` which you can get with your cygwin installer and `vshadow` which you can get from Microsoft Windows Software Development Kit (SDK).

## Installation

You can copy this script into your `/usr/local/bin` directory or just call it directly from the command line.

## Configuration

Configure this script by modifying the variables starting with `BACKUP_`.

## Usage

Just call this script, the script should do everything automatic (mounting, indexing, saving).