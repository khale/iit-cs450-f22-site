---
layout: home
title: CS 450
nav_exclude: true
seo:
  type: Course
  name: Operating Systems
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

## Welcome!

This is the webpage for CS 450: Operating Systems at [IIT](https://iit.edu).  This
course is for junior/senior level undergraduates and graduates in Computer
Science. CS 450 is a core requirement for the CS curriculum. Both CS 350 and CS
351 are **required** prerequisites. 
 
## Course Communication
We'll be using the [Diderot](https://diderot.one) platform for course communication. You will
receive an invite from me in the first week of class. The course schedule, lecture materials, class discussion, and assignments will all be
on Diderot. 
 
## Other Useful Links and Resources
This is a list of other resources that you might find useful for this class.
Feel free to peruse them at your own convenience.
 
### Links
- [Good resource for OS development]("https://wiki.osdev.org/Main_Page)
- [Resources for learning Git](https://try.github.io/)
- [Another nice Git resource](http://gitready.com/)
- [QEMU documentation](https://wiki.qemu.org/Documentation)
- [Nice article on virtual memory](http://blog.robertelder.org/virtual-memory-with-256-bytes-of-ram/)
- [The ELF executable format](http://www.skyfree.org/linux/references/ELF_Format.pdf)
- [Intel Architecture Manual](https://software.intel.com/en-us/articles/intel-sdm)
- [AMD Architecture Manuals](https://developer.amd.com/resources/developer-guides-manuals/)
- [Brennan's Guide to Inline Assembly](http://www.delorie.com/djgpp/doc/brennan/brennan_att_inline_djgpp.html)
- [GCC Inline Assembly](http://www.ibiblio.org/gferg/ldp/GCC-Inline-Assembly-HOWTO.html)
- [Various simulators](http://classque.cs.utsa.edu/simulators/), e.g. for process schedulers, disk head schedulers, etc.
- Code for various [Linux kernel](https://github.com/SecWiki/linux-kernel-exploits) and [Windows kernel](https://github.com/SecWiki/windows-kernel-exploits) exploits

### Interesting, important, historical, and new OS Kernels
- [The Linux Kernel](https://www.kernel.org/), arguably the most important kernel of our time
-   [FreeBSD](https://www.freebsd.org/)
- [Nautilus](https://github.com/hexsa-lab/nautilus), a research OS written by your instructor for parallel runtime systems
- [Plan 9](https://en.wikipedia.org/wiki/Plan_9_from_Bell_Labs), an important (but commercially unsuccessful) UNIX successor by Bell Labs
-   [Harvey OS](https://harvey-os.org/), a new successor to Plan 9
- [Drawbridge](https://www.microsoft.com/en-us/research/project/drawbridge/), research prototype from MSR (components of which are now in the NT kernel).
- [MINIX 3](https://www.minix3.org/), a historically important microkernel (originally---and still---used for teaching). Intel chips [actually run this](https://www.zdnet.com/article/minix-intels-hidden-in-chip-operating-system/) internally!
- [Several OSes](http://l4hq.org/projects/kernel/) based on the L4 kernel, an important early microkernel
- [Android OS](https://www.android.com/), Google's mobile OS (based on Linux kernel, but probably soon Fuchsia (below))
-   [Fuchsia OS](https://github.com/fuchsia-mirror), a new microkernel-based OS from Google
- [Barrelfish OS](http://www.barrelfish.org/), an important research OS from ETH Zurich (the OS is a distributed system)
-   [Redox](https://www.redox-os.org/), an OS written in Rust (UNIX-like)
- [Kitten Lightweight Kernel](https://software.sandia.gov/trac/kitten), an OS kernel designed for supercomputing
-   [Scout](http://www2.cs.arizona.edu/projects/scout/), a network-oriented research OS
-   [MirageOS](https://mirage.io/), a Unikernel for OCaml applications
-   [OSv](http://osv.io/), a popular new Unikernel
- [Pintos](https://web.stanford.edu/class/cs140/projects/pintos/pintos_1.html), a teaching OS based on the [Nachos](https://homes.cs.washington.edu/~tom/nachos/) research OS.
-   [JOS](https://github.com/komukomo/jos), another teaching OS
-   [OS/2](https://en.wikipedia.org/wiki/OS/2), an important mainframe OS from IBM
- [COS](https://en.wikipedia.org/wiki/Cray_Operating_System), an OS for some of the first supercomputers
- [CP/M](https://en.wikipedia.org/wiki/CP/M), an OS for some of the first microcomputers. [Here](https://www.computerhistory.org/atchm/early-digital-research-cpm-source-code/) is the code.
- [code](http://xeroxalto.computerhistory.org/xerox_alto_file_system_archive.html) for the OS of Xerox Alto, the first computer with a GUI
-   [source code](https://github.com/Microsoft/MS-DOS) for MS-DOS 1.25 and 2.0
- [source code](https://github.com/apple/darwin-xnu) for the XNU kernel, part of Darwin, which powers macOS
- [source code](https://github.com/reactos/reactos) for ReactOS, a WindowsNT-compatible kernel
- [System software](http://www.ibiblio.org/apollo/links.html) for the Apollo Guidance Computer
- [Code](https://www.computerhistory.org/atchm/apple-ii-dos-source-code/) for the Apple II's DOS
- [Code](http://www.atarimuseum.com/videogames/consoles/7800/games/) for the Atari 7800's OS
