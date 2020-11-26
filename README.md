# <a href="url"><img src="https://cdn1.iconfinder.com/data/icons/metro-ui-dock-icon-set--icons-by-dakirby/256/Command_Prompt.png" align="middle" width="100" height="100"></a> simple_shell


## Table of Contents
* [Description](#description)
* [File Structure](#file-structure)
* [Requirements](#requirements)
* [Installation](#installation)
* [Usage](#usage)
* [Authors](#authors)

## Description
This is our try at creating a simple shell for linux, it's very basic.  

## File Structure
* [AUTHORS](AUTHORS)
* [shell.h](shell.h)
* [builtins.c](builtins.c)
* [free.c](free.c)
* [man_1_simple_shell](man_1_simple_shell)
* [path.c](path.c)
* [prompt.c](prompt.c)
* [strtow.c](strtow.c)
* [utility.c](utility.c)
* [simple_shell.c](simple_shell.c)

## Requirements

Ubuntu 14.04 LTS

## Installation

   - Clone this repository: `git clone "https://github.com/rubenoliveros/simple_shell.git"`
   - Change directories into the repository: `cd simple_shell`
   - Compile: `gcc -Wall -Werror -Wextra -pedantic *.c -o hsh`
   - Run the shell in interactive mode: `./hsh`
   - Or run the shell in non-interactive mode: example `echo "pwd" | ./hsh`

## Usage

This project can execute commands similar to bash, it has limited features and is still a work in progress.

## Authors
Leopoldo Luna

Ruben Oliveros
