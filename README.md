# bupvss 0.1

Creating with bup, cygwin and volume shadow copy backups

## Requirements

This script was made for a cygwin enviroment. For proper work you need `bup`, 
which you may have to compile by hand, `par2` which you can get with your 
cygwin installer and `vshadow` which you can get from Microsoft Windows 
Software Development Kit (SDK).

## Installation

You can copy this script into your `/usr/local/bin` directory or just call it 
directly from the command line.

## Configuration

Configure this script by modifying the variables starting with `BACKUP_`.

## Usage

Just call this script, the script should do everything automatic (mounting, 
indexing, saving).

## License

bupvss 0.1
Copyright (C) 2016  Andreas Fendt

This program is free software; you can redistribute it and/or modify it under 
the terms of the GNU General Public License as published by the Free Software 
Foundation; either version 2 of the License, or (at your option) any later 
version.

This program is distributed in the hope that it will be useful, but WITHOUT 
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS 
FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with 
this program; if not, write to the Free Software Foundation, Inc., 51 
Franklin St, Fifth Floor, Boston, MA 02110, USA
