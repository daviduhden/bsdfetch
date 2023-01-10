# bsdfetch

**bsdfetch** is a simple tool to show information about a running **FreeBSD/OpenBSD/MidnightBSD/NetBSD/DragonflyBSD** system.

## Packages/Ports
bsdfetch is available as a package/port on the following BSD's:

**NetBSD** - sysutils/bsdfetch (https://pkgsrc.se/sysutils/bsdfetch)   
**MidnightBSD** - sysutils/bsdfetch (https://github.com/MidnightBSD/mports/tree/master/sysutils/bsdfetch)

## Usage:
1. Clone/download this repository
2. Unpack/cd into the directory
3. Run
```
$ make
```
4. bsdfetch can now be run as follows
```
$ ./bsdfetch
```

## Screenshots:

**FreeBSD system example:**   
![image](https://user-images.githubusercontent.com/37046652/208292534-2c64874e-e3a8-4486-9fdd-bd74adc3e0a0.png)

**OpenBSD system example:**   
![image](https://user-images.githubusercontent.com/37046652/208292527-b63af7c5-6a1a-4ccc-833e-9d1175bcc33f.png)

**NetBSD system example:**   
![image](https://user-images.githubusercontent.com/37046652/211198104-5bd43e08-4213-4b81-9e25-a4b7805aec1f.png)

## Interesting:   
Pure shell implementation of bsdfetch: https://github.com/rilysh/bsdfetch-sh   

## Thanks:

**Felix Palmen** (https://twitter.com/8bitsound) - For suggestions regarding tty, initialization, color output handling. Also for contributing to the project (pkg).   
**Laurent Cheylus** (https://twitter.com/lcheylus) - For implementing "Arch" and "Memory" support for bsdfetch on OpenBSD (libsysctl). Also, for fixing a bug when no sensors are present on OpenBSD.   
**Lucas Holt** (https://www.midnightbsd.org/) - For porting bsdfetch to MidnightBSD.   
**rilysh** (https://github.com/rilysh) - For porting bsdfetch to NetBSD and DragonflyBSD. Also, for removing a unneeded header and adding a date output to version().   
**vins** (@sehnsucht@social.sdf.org) - For improving the CPU handling and enabling uptime on NetBSD. Also, for informing about possible breakage with wrong include (sys/time.h) affecting FreeBSD (based) systems. And for overhauling a large part of the code.   
**Thomas Adam** (https://github.com/ThomasAdam) - Using void in function prototypes without arguments.   
**Alexander Naumochkin** (https://github.com/dorjechang) - For providing two fixes to the project (USER and UID fix). Also for fixing a compiler warning on armv6 systems. Reported a version difference in the code.    
**Anonymous contributor** - Improved/Simplified bsdfetch to a great extent.
