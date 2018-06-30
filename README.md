= MikeOS =

MikeOS is a custom system built from source. It does not follow standards and it does not pretend to be an OS to be used on today basis.
My System, my rules.

Documentation on how to build it are inside the doc folder

Here are some of the features that I plan to implement
- Completely built from source
- It will feature both Musl-libC and GlibC (for now only GlibC)
- You can Program in C, C++ and Python with it (it also contains Perl)
- it will feature a GUI (TinyX, Kdrive or Xorg)
- it will include a Rich Text Editor
- you will be able to produce PDF files
- it will have busybox as init (maybe SysV in future?)
- bin_fmt for arm (and maybe aarch64?)
- it will boot on BIOS and x86_64-efi (I would like to use Grub but for now I'm stuck with syslinux)
- it is intended to work for i386 processors (for now I'm building for i686)
- you will be able to listen to music and watch videos with it
- it will be able to run virtual machines
- it will have a LiveCD and LiveUSB with persistence
- all the system will be under a single directory: /MikeOS (except for the /home, /root, /tmp, /dev and /proc)
