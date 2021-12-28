# Programming

# C

## Ubuntu

- compiler - `gcc`
  - `sudo apt install build-essential`
- build - `make`
  - `sudo apt install make`

# C++

## Ubuntu

- compiler - `g++`
  - `sudo apt instal build-essential`
- build - `cmake`
  - `sudo apt install cmake`

# Java

- compiler - `openjdk`
  - `sudo apt install default-jdk`
  - `sudo apt install openjdk-8-jdk` - for `jdk8`, you can choose another one
  - `sudo update-alternatives --config java` - check the available versions in the system
- build - `apache ant` `apache maven` `gradle`
  - `apache maven`
    - `sudo apt install mvn`

# Python

## Ubuntu

- interpreter - `python2` `python3`
  - `sudo apt install python3`
  - `sudo apt install python2`
- packages - `pip`
  - `sudo apt install pip3`
  - `sudo apt install pip`
- virtual environments
  - `conda`
  - `venv`

## Packages

### Ubuntu (Debian)

**IMPORTANT - MUST KNOW**

- the versions of the packages you install from the system package manager
  - and that you install for the `pip` will differ
  - system package manager packages will also be used by other programs
  - distribution packages are in - `/usr/lib/python3/dist-packages`
  - other packages will be in - `~/.local/lib/site-packages`
- install the packages with `pip` in the user directory 
  - `pip install pkgname --user`


# R

## Ubuntu

- compiler `R`
  - `sudo apt install r-base`
- packages
  - from The Comprehensive R Archive Network (`CRAN`)
    - `install.packages("pkgname")`

# Julia

## Ubuntu

- interpreter `julia`
  - `sudo apt install julia`
- packages
  - `pkg` built in julia

# Scala

## Ubuntu

- compiler `scala`
  - `sudo apt install scala`
- built `sbt`
  - `sudo apt install sbt`

# [Ruby](./src/ruby.md)

## Ubuntu

- compiler `ruby`
  - `sudo apt install ruby`
- packages also called gems
  - `gem`
  - set these env variables
    - `export GEM_HOME=$HOME/.gem`
    - `export GEM_PATH=$HOME/.gem`

# Rust

## Ubuntu

- compiler `rust`
  - `rustup` - installer for ruby, installs the latest version of ruby
  - [https://rustup.rs/](https://rustup.rs/)

# Node

## Ubuntu

- use `nvm` node version manger to install node
  - [https://github.com/nvm-sh/nvm](https://github.com/nvm-sh/nvm)


# [Lua](./src/lua.md)

## Ubuntu

- compiler - `lua`
  - three versions are available
  - `sudo apt install lua5.1`

## Packages

- `luarocks`
  - [https://luarocks.org/](https://luarocks.org/)