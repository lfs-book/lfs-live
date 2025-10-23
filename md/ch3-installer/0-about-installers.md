# About Installers

Installers are a very common part of most LiveCDs, they allow you to install the OS from the LiveCD onto a computers disk drive for persistant use.  

They do this through uncompressing the SquashFS onto a new root partition. From there they setup system unique system elements like UUIDs, fstab (partitions), Users, and optionally remove the installer from the system.

This book will document 2 installers: a simple bash script for non-graphical or light systems; and the Calamares installer, which is used on many commerical distros. If you are not running LFS you may want to use the calamares configurations that your distro provides rather than the simplistic configurations from this book. 