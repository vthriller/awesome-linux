# Awesome Linux Kernel

Not necessarily awesome, as this is just a (not-so-)trendy naming template for repos containing lists of links on particular topic. See also [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness).

## Patches
* ~~[ACPI DSDT in initrd](http://gaugusch.at/kernel.shtml)~~?
    * latest patch is for 2.6.30
* ~~[AUFS](http://aufs.sourceforge.net/)~~
    * superseded by OverlayFS, which is in the mainline
* [BFS by Con Kolivas](http://ck.kolivas.org/patches/bfs/)
    * [BFS/VRQ](http://cchalpha.blogspot.ru/) (also on [Bitbucket](https://bitbucket.org/alfredchen/linux-gc))
    * [MuQSS](http://ck.kolivas.org/patches/muqss/)
        * [LKML announcement](https://lkml.org/lkml/2016/10/29/4)
* [BFQ](http://algo.ing.unimo.it/people/paolo/disk_sched/)
* [BLD](https://github.com/rmullick/bld-patches)
    * [also as a branch](https://github.com/rmullick/linux)
* [CONFIG_PREEMPT_RT](https://rt.wiki.kernel.org/index.php/CONFIG_PREEMPT_RT_Patch)
* [fbcondecor](https://gitweb.gentoo.org/proj/linux-patches.git/plain/4200_fbcondecor-3.19.patch?h=4.7)
    * latest copyright notice is from 2009, but it is still somewhat supported by genpatches (or whatever it is called now) team (as it "[usually requires little effort, and only infrequent changes to the code to match updates made in the kernel framebuffer layer](https://github.com/mjanusz/homepage/tree/master/projects/fbcondecor)")
* [grsecurity](https://grsecurity.net/)
    * [PaX](https://pax.grsecurity.net/)
* [Kernel_gcc_patch](https://github.com/graysky2/kernel_gcc_patch)
* [KernelCare](http://patches.kernelcare.com/)
* kGraft
* [ksplice](https://oss.oracle.com/ksplice/software/)
* [NFS ngroups limitation bypass](http://www.frankvm.com/nfs-ngroups/)
* [NFS selective attribute caching](http://www.frankvm.com/nfs-noac/)
* [OpenVZ](http://openvz.org/Main_Page)
* [l7-filter](http://l7-filter.sourceforge.net/)
* [LinuxIMQ](http://www.linuximq.net/)
* [Reiser4](https://reiser4.wiki.kernel.org/index.php/Main_Page)
* [RIFS scheduler](https://code.google.com/p/rifs-scheduler)
* [RSBAC](https://www.rsbac.org/)
* [task_diag](https://github.com/avagin/linux-task-diag)
    * also on [LKML](https://lwn.net/Articles/683371/) and in the [CRIU wiki](https://criu.org/Task-diag)
* [TuxOnIce](https://gitlab.com/nigelcunningham/tuxonice-kernel/-/branches)
* [UKSM](http://kerneldedup.org/en/projects/uksm/)
* ~~[UnionFS](http://unionfs.filesystems.org/)~~
    * superseded by OverlayFS, which is in the mainline
* [wb-buf-throttle](http://brick.kernel.dk/snaps/)
    * can be found under the name `wb-buf-throttle-*.patch`
    * [also as a branch per each version](http://git.kernel.dk/cgit/linux-block/log/?h=wb-buf-throttle-v7)
    * [recent LKML announcement](https://lkml.org/lkml/2016/9/7/418)

## Trees
* [mainline](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/)
* [linux-next](https://git.kernel.org/cgit/linux/kernel/git/next/linux-next.git/)
* [mm, mmotm](https://git.kernel.org/cgit/linux/kernel/git/mhocko/mm.git/)
* [linux-libre](https://www.fsfla.org/ikiwiki/selibre/linux-libre/)?
* [zen-kernel](https://github.com/zen-kernel/zen-kernel)?
    * [Liquorix](https://liquorix.net/sources/)

## Distro specific patches and trees
* [CentOS](https://git.centos.org/rpms/kernel/branches)
* [Debian](https://anonscm.debian.org/cgit/kernel/linux.git)
* [Fedora](http://pkgs.fedoraproject.org/cgit/rpms/kernel.git)
* [Gentoo](https://gitweb.gentoo.org/proj/linux-patches.git)
* [Mageia](http://svnweb.mageia.org/packages/cauldron/kernel/current/PATCHES/patches/)
* [OpenSUSE](http://kernel.opensuse.org/cgit/kernel)
* [Ubuntu](http://kernel.ubuntu.com/git/ubuntu/linux.git/)
    * trees for [12.04](https://git.launchpad.net/~ubuntu-kernel/ubuntu/+source/linux/+git/precise)
      ([mirror](https://kernel.ubuntu.com/git/ubuntu/ubuntu-precise.git/)),
      [14.04](https://git.launchpad.net/~ubuntu-kernel/ubuntu/+source/linux/+git/trusty)
      ([mirror](https://kernel.ubuntu.com/git/ubuntu/ubuntu-trusty.git/)),
      [16.04](https://git.launchpad.net/~ubuntu-kernel/ubuntu/+source/linux/+git/xenial)
      ([mirror](https://kernel.ubuntu.com/git/ubuntu/ubuntu-xenial.git/)),
      [18.04](https://git.launchpad.net/~ubuntu-kernel/ubuntu/+source/linux/+git/bionic)
      ([mirror](https://kernel.ubuntu.com/git/ubuntu/ubuntu-bionic.git/)),
      [20.04](https://git.launchpad.net/~ubuntu-kernel/ubuntu/+source/linux/+git/focal)
      ([mirror](https://kernel.ubuntu.com/git/ubuntu/ubuntu-focal.git/));
      also available for other releases (on kernel.ubuntu.com it's sometimes under ubuntu-archive, e.g. [8.10](https://kernel.ubuntu.com/git/ubuntu-archive/ubuntu-intrepid.git/))
    * [docs](https://wiki.ubuntu.com/Kernel/Dev/KernelGitGuide)

## Modules
* [DRBD](http://oss.linbit.com/drbd/)
* [dtrace](https://github.com/dtrace4linux/linux)
* [ZFS on Linux](http://zfsonlinux.org/) (including SPL)
* [kpatch](https://github.com/dynup/kpatch)
* [groeck's device drivers](http://roeck-us.net/linux/drivers/)
    * [Devantech USB-ISS USB to I2C adapter](https://github.com/groeck/devantech)
    * [Silicon Labs Si570](https://github.com/groeck/si570)
* kdbus
    * [Greg KH](https://github.com/gregkh/kdbus)
    * [systemd](https://github.com/systemd/kdbus)
