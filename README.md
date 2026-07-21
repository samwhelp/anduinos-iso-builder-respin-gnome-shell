

# Home

| Link | GitHub |
| ---- | ------ |
| [anduinos-iso-builder-respin-gnome-shell](https://samwhelp.github.io/anduinos-iso-builder-respin-gnome-shell/) | [GitHub](https://github.com/samwhelp/anduinos-iso-builder-respin-gnome-shell) |




## Subject

* [Combination](#combination)
* [Environment](#environment)
* [Start](#start)
* [Clone](#clone)
* [Usage](#usage)
* [Config Files](#config-files)
* [Package Install List](#package-install-list)
* [Keybind](#keybind)
* [Discussions](#discussions)
* [Refactoring Evolution](#refactoring-evolution)
* [Link](#link)




## Combination

| Project |
| ------- |
| [anduinos-iso-builder-template](https://github.com/samwhelp/anduinos-iso-builder-template) |
| `+` |
| [anduinos-iso-builder-remix-gnome-shell](https://github.com/samwhelp/anduinos-iso-builder-remix-gnome-shell) |
| `=` |
| [anduinos-iso-builder-respin-gnome-shell](https://github.com/samwhelp/anduinos-iso-builder-respin-gnome-shell) |




## Environment

* `Ubuntu 26.04`




## Start

Open Terminal , and run to install [git](https://packages.ubuntu.com/resolute/git) and [make](https://packages.ubuntu.com/resolute/make)

``` sh
sudo apt-get install git make
```




## Clone

Run to clone [anduinos-iso-builder-respin-gnome-shell](https://github.com/samwhelp/anduinos-iso-builder-respin-gnome-shell)

``` sh
git clone https://github.com/samwhelp/anduinos-iso-builder-respin-gnome-shell
```

Run to change dir `anduinos-iso-builder-respin-gnome-shell`

``` sh
cd anduinos-iso-builder-respin-gnome-shell
```




## Usage

* [Help](#help)
* [Prepare](#prepare)
* [Build](#build)
* [Clean](#clean)




## Help

Run

``` sh
make
```

Or run

``` sh
make help
```

Show

```
Usage:
	$ make [action]

Example:
	$ make
	$ make help

	$ make prepare
	$ make build
	$ make clean

```




## Prepare

> Run the following command to install the packages required to create an ISO file.

``` sh
make prepare
```




## Build

Only need to execute the following command to create an ISO file.

``` sh
make build
```




## Clean

Run to clean up previous builds.

``` sh
make clean
```




## Config Files

| Config Files |
| ------------ |
| [~/.config](https://github.com/samwhelp/anduinos-iso-builder-respin-gnome-shell/tree/main/template/asset/overlay/etc/skel/.config) |
| [/etc/dconf/db/anduinos.d](https://github.com/samwhelp/anduinos-iso-builder-respin-gnome-shell/tree/main/template/asset/overlay/etc/dconf/db/anduinos.d) |
| [/usr/share/glib-2.0/schemas](https://github.com/samwhelp/anduinos-iso-builder-respin-gnome-shell/tree/main/template/asset/overlay/usr/share/glib-2.0/schemas) |




## Package Install List

> Please check the folder

* [template/asset/package/install](https://github.com/samwhelp/anduinos-iso-builder-respin-gnome-shell/tree/main/template/asset/package/install)


> And check the file

* [template/engine/mods/anduinos-desktop-package-install/install.sh](https://github.com/samwhelp/anduinos-iso-builder-respin-gnome-shell/blob/main/template/engine/mods/anduinos-desktop-package-install/install.sh)

> Ubuntu Community Help Wiki / [MetaPackages](https://help.ubuntu.com/community/MetaPackages)




## Keybind

* [Keybind Cheatsheet](https://samwhelp.github.io/anduinos-gnome-shell-adjustment/read/cheatsheet/keybind.html)




## Discussions

* [#352 - Custom AnduinOS-2 iso build script](https://github.com/Anduin2017/AnduinOS/discussions/352)




## Refactoring Evolution

| Refactoring Evolution |
| --------------------- |
| [prototype-2.0.0](https://github.com/samwhelp/AnduinOS-2/tree/prototype-2.0.0) |
| [demo-build-steps](https://github.com/samwhelp/AnduinOS-2/tree/demo-build-steps) |
| [demo-build-engine](https://github.com/samwhelp/AnduinOS-2/tree/demo-build-engine) |
| [demo-build-template](https://github.com/samwhelp/AnduinOS-2/tree/demo-build-template) |




## Link

| Link |
| ---- |
| [live-custom-ubuntu-from-scratch](https://github.com/mvallim/live-custom-ubuntu-from-scratch) |
| [AnduinOS](https://github.com/Anduin2017/AnduinOS) |
| [AnduinOS-2](https://github.com/AiursoftWeb/AnduinOS-2) |




| Link | GitHub |
| ---- | ------ |
| [AnduinOS Gnome Shell Adjustment](https://samwhelp.github.io/anduinos-gnome-shell-adjustment/) | [GitHub](https://github.com/samwhelp/anduinos-gnome-shell-adjustment) |
| [AnduinOS Gnome Shell Note](https://samwhelp.github.io/note-about-anduinos-gnome-shell/) | [GitHub](https://github.com/samwhelp/note-about-anduinos-gnome-shell) |
| [AnduinOS Adjustment](https://samwhelp.github.io/anduinos-adjustment/) | [GitHub](https://github.com/samwhelp/anduinos-adjustment) |
| [demo-for-anduinos-discussion](https://samwhelp.github.io/demo-for-anduinos-discussion/) | [GitHub](https://github.com/samwhelp/demo-for-anduinos-discussion) |




## Samwhelp

* [GitHub](https://github.com/samwhelp)
