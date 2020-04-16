Overview
========

|github| Development of this software is hosted at `github.com/joaomdsc/lfs`_.

|rtd| Documentation for this software can be found on `lfs.readthedocs.io`_.

What's in here ?
----------------

This repository holds python scripts dealing with **LFS** (as in `Linux From
Scratch`_), which automates the building of an entire linux system from source
code, as described in `the LFS book`_.

lfs
---

Linux From Scratch is a community-maintained online book with instructions for
downloading, configuring, and compiling all the necessary software to obtain a
bootable, usable Linux system. The book is an extraordinary resource, embodying
the collective knowledge and the efforts of all the LFS volunteers who study
every individual piece of the linux machinery to determine a set of compatible
parameters to make it all work together.

This project, referred to as **lfs_py** in this documentation, aims to relieve
you of the manual repetitive task of running each piece of shell script one
after the other. It's a set of python scripts that parse the LFS book and
generate shell scripts that are then used to automate the building
process. Using lfs_py, you basically just set the values of a few variables,
launch a script, and wait a few hours: when the script is done, you can boot
your new Linux system.

Hopefully lfs_py will reduce the time and effort required to unlock the huge
value of the LFS book and to get that customized Linux system up and
running. For all the details on how to use the software, see the lfs_py
documentation in :ref:`automating-lfs`.

.. sectionauthor:: Joao Moreira <joao.moreiradsc@gmail.com>

.. |github| image:: /img/GitHub-Mark-32px.png
.. |rtd| image:: /img/rtd-logo-dark-32px.png

.. _github.com/joaomdsc/lfs: https://github.com/joaomdsc/lfs
.. _lfs.readthedocs.io: https://lfs.readthedocs.io
.. _Linux From Scratch: http://www.linuxfromscratch.org/
.. _the LFS book: http://www.linuxfromscratch.org/lfs/view/stable-systemd/
