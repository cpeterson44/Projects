# Contents <a name="contents"></a>
- [Introduction](#intro)
- [Artificial Intelligence Projects](#ai)
- [Application Security CTF Challenges](#security)
- [Battleship AI](#battleship)
- [Chess AI Research Paper](#chess)
- [Malloc Implementation](#malloc)
- [Multicontroller](#multicontroller)
- [UNIX Filesystem Implementation via FUSE](#fuse)

# Introduction <a name="intro"></a>

Hello!

This github page serves as a publically-visible hub for many of the notable projects I am currently working on or have worked on in the past. This page intends to serve as a both a sampler to give an overall picture of the various projects I have worked on, as well as a resource that can direct individuals to repository links containing code and more detailed explanations.

The projects on this page are not currently ordered in any meaningful way beyond simple alphabetical order. Each project's description contains a few important facts, including language and dates, as well as a brief summary of the problem and how the project aims to solve/solved it.

Many of the repositories this page links to are private. Contact me if you'd like access to them or to their code.

# Artificial Intelligence Projects <a name="ai"></a>

<table>
  <tr>
    <th colspan="2">Artificial Intelligence Projects</th>
  </tr>
  <tr>
    <th>Date:</th>
    <td>Winter 2018</td>
  </tr>
  <tr>
    <th>Language:</th>
    <td>Python</td>
  </tr>
  <tr>
    <th>Group Size:</th>
    <td>Solo</td>
  </tr>
  <tr>
    <th>Repo link:</th>
    <td>www.github.com/cpeterson44/ai</td>
  </tr>
  <tr>
    <th>Public:</th>
    <td>No - college assignment</td>
  </tr>
</table>

[[back to top](#contents)]

# Application Security CTF Challenges <a name="security"></a>

<table>
  <tr>
    <th colspan="2">Application Security CTF Challenges</th>
  </tr>
  <tr>
    <th>Date:</th>
    <td>Fall 2018</td>
  </tr>
  <tr>
    <th>Language:</th>
    <td>Python, Assembly, and C</td>
  </tr>
  <tr>
    <th>Group Size:</th>
    <td>Solo</td>
  </tr>
  <tr>
    <th>Repo link:</th>
    <td>www.github.com/cpeterson44/security</td>
  </tr>
  <tr>
    <th>Public:</th>
    <td>No - graduate assignment</td>
  </tr>
</table>

[[back to top](#contents)]

# Battleship AI <a name="battleship"></a>

<table>
  <tr>
    <th colspan="2">Battleship AI</th>
  </tr>
  <tr>
    <th>Date:</th>
    <td>Winter 2017</td>
  </tr>
  <tr>
    <th>Language:</th>
    <td>C</td>
  </tr>
  <tr>
    <th>Group Size:</th>
    <td>Solo</td>
  </tr>
  <tr>
    <th>Repo link:</th>
    <td>www.github.com/cpeterson44/battleship</td>
  </tr>
  <tr>
    <th>Public:</th>
    <td>No - college assignment</td>
  </tr>
</table>

[[back to top](#contents)]

# Chess AI Research Paper <a name="chess"></a>

<table>
  <tr>
    <th colspan="2">Chess AI Research Paper</th>
  </tr>
  <tr>
    <th>Date:</th>
    <td>Winter-Spring 2018</td>
  </tr>
  <tr>
    <th>Language:</th>
    <td>LaTeX</td>
  </tr>
  <tr>
    <th>Group Size:</th>
    <td>Solo</td>
  </tr>
  <tr>
    <th>Repo link:</th>
    <td>www.github.com/cpeterson44/chess</td>
  </tr>
  <tr>
    <th>Public:</th>
    <td>No - college assignment</td>
  </tr>
</table>

[[back to top](#contents)]

# Malloc Implementation <a name="malloc"></a>

<table>
  <tr>
    <th colspan="2">Malloc Implementation</th>
  </tr>
  <tr>
    <th>Date:</th>
    <td>Fall 2017</td>
  </tr>
  <tr>
    <th>Language:</th>
    <td>C</td>
  </tr>
  <tr>
    <th>Group Size:</th>
    <td>Solo</td>
  </tr>
  <tr>
    <th>Repo link:</th>
    <td>www.github.com/cpeterson44/malloc</td>
  </tr>
  <tr>
    <th>Public:</th>
    <td>No - college assignment</td>
  </tr>
</table>

[[back to top](#contents)]

# Multicontroller <a name="multicontroller"></a>

<table>
  <tr>
    <th colspan="2">Multicontroller</th>
  </tr>
  <tr>
    <th>Date:</th>
    <td>Winter 2019</td>
  </tr>
  <tr>
    <th>Language:</th>
    <td>C#</td>
  </tr>
  <tr>
    <th>Group Size:</th>
    <td>Solo</td>
  </tr>
  <tr>
    <th>Repo link:</th>
    <td>www.github.com/cpeterson44/multicontroller</td>
  </tr>
  <tr>
    <th>Public:</th>
    <td>No - actively in development</td>
  </tr>
</table>

[[back to top](#contents)]

# UNIX Filesystem Implementation via FUSE <a name="fuse"></a>

<table>
  <tr>
    <th colspan="2">UNIX Filesystem Implementation via FUSE</th>
  </tr>
  <tr>
    <th>Date:</th>
    <td>Fall 2018</td>
  </tr>
  <tr>
    <th>Language:</th>
    <td>C</td>
  </tr>
  <tr>
    <th>Group Size:</th>
    <td>3</td>
  </tr>
  <tr>
    <th>asdf:</th>
    <td>3</td>
  </tr>
  <tr>
    <th>Repo link:</th>
    <td>www.github.com/cpeterson44/fuse</td>
  </tr>
  <tr>
    <th>Public:</th>
    <td>No - graduate assignment</td>
  </tr>
</table>

FUSE (Filesystem in Userspace) is a software interface for Unix-like computer operating systems that lets non-privileged users create their own file systems in user space without editing kernel code. A FUSE file system is used the same as a standard file system except that all normal system calls (ex. mkdir, mknod, read, write, etc.) are passed to and handled by the FUSE program instead of the kernal.

For this project, our group had to design a robust filesystem implementation from scratch in C. We implemented the following core Unix system calls, with syntax and return values matching the `man` page specifications:
* `getattr`
* `readdir`
* `mknod`
* `mkdir`
* `unlink`
* `rmdir`
* `truncate`
* `open`
* `read`
* `write`

Our file system was a layered implementation of the basic UNIX FS, containing a superblock, a list of inodes, and a list of data blocks:

To improve performance and to match UNIX semantics, we also implented a bitmap for free inodes, an open file table, and an in-place free list.

[[back to top](#contents)]
