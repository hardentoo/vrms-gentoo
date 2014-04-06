vrms-gentoo
===========

This is a clone of [VRMS (Virtual Richard M. Stallman)](https://vrms.alioth.debian.org/) for Gentoo Linux.
It scans the computer for non-free packages, and shows a list of them, if any.

Instead of using its own list of licenses, it scans the license_group file in the local computer
and compares the locally installed packages to the @FREE group. If you want it to use only the @FSF-APPROVED
group you can use the --strict flag.
