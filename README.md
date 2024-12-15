## About
lfs-live is a description of the process to create a Boot-CD or Live-CD based on a [Linux From Scratch](https://www.linuxfromscratch.org) system. The tools used to build the CD are all built from source, there will be no hidden magic. The CD built with this description should be bootable on BIOS as well as on UEFI systems.

The edge between a Boot-CD and a Live-CD might be fluent, we assume that a Boot-CD is just a bare OS bootable from a CD while a Live-CD contains OS and many tools and applications, even a GUI. At the end, a Live-CD might be used as a daily driver.

## Getting started
### Prerequisites
The description is built using Docbook XML. That format is easily converted to HTML or other formats like PDF which includes navigation. For the conversion, following tools are needed
* make
* libxml2
* libxslt
* Docbook XML
* blah
* blubb

All this tools are described in LFS and BLFS respectively. Since the used tools, the OS which will be on CD and the tools to generate the HTML version of this description are all based on LFS, it is required that the user has a certain amount of knowledeg in building a LFS system.

### Installation
To render the XMLs to HTML, run
```sh
make
```
When finished, the HTML should be stored in <HTML-OUTPUT-DIR>

## Usage
(navigate in the book)

## Roadmap
- [ ] Setup initial structure
- [ ] blah
- [ ] blubb
