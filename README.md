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
    <th>Grade Recieved:</th>
    <td>A-</td>
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

This repository contains several small-medium assignments from CS 480, the Artifical Intelligence course offered at Cal Poly San Luis Obispo. These assignments were structured as a variety of nuanced challenges, which each required a different algorithm and/or approach to solve quickly and efficiently. Although we were given some guidance on which algorithms to use, we were largely left on our own to research and discover implementation details.

Some of the algorithms/concepts covered include:
* [A* Search](https://en.wikipedia.org/wiki/A*_search_algorithm)
* [Alpha-Beta Pruning](https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning)
* [Beam Search](https://en.wikipedia.org/wiki/Beam_search)
* [Boolean Algebra](https://en.wikipedia.org/wiki/Boolean_algebra)
* [Genetic Algorithms](https://en.wikipedia.org/wiki/Genetic_algorithm)
* [Hill Climbing Search](https://en.wikipedia.org/wiki/Hill_climbing)
* [Monte Carlo Simulation](https://en.wikipedia.org/wiki/Monte_Carlo_method)
* [Naive Bayes Classification](https://en.wikipedia.org/wiki/Naive_Bayes_classifier)
* [Simulated Annealing](https://en.wikipedia.org/wiki/Simulated_annealing)
* [Transpositions](https://en.wikipedia.org/wiki/Transposition_(chess))

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
    <th>Grade Recieved:</th>
    <td>A</td>
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

[CTF (Capture the Flag) challenges](https://blogs.cisco.com/perspectives/cyber-security-capture-the-flag-ctf-what-is-it) are exercises designed to test a user's creativity and knowledge of security concepts. In these challenges, a vulnerable program or service is presented with a hidden "flag" that can only be accessed by someone who has discovered the vulnerability and compromised the security of the program.

This repository contains my solutions to the CTF challenges for CS 279, one of UCSB's graduate Computer Security courses. Where possible, I've included the challenge binary and a description of the challenge, the vulnerability, and the attack my program executes to get the flag. Most of the exploits are 100% reliable, but due to the nature of some of the challenges, some exploits require multiple attempts to access the flag.

Some of the exploits/concepts covered by the CTF challenges include:
* [Arbitrary Code Execution](https://en.wikipedia.org/wiki/Arbitrary_code_execution)
* [ASLR & Address Leaks](https://en.wikipedia.org/wiki/Address_space_layout_randomization)
* [Brute-Force Attacks](https://en.wikipedia.org/wiki/Brute-force_attack)
* [Buffer Overflows/Underflows](https://en.wikipedia.org/wiki/Buffer_overflow)
* [Cryptography](https://en.wikipedia.org/wiki/Cryptography)
* [Directory Traversal Attacks](https://en.wikipedia.org/wiki/Directory_traversal_attack)
* [Environment Variables](https://en.wikipedia.org/wiki/Environment_variable)
* [Format String Attacks](https://en.wikipedia.org/wiki/Uncontrolled_format_string)
* [Hash Functions](https://en.wikipedia.org/wiki/Hash_function)
* [Heap Corruption](https://heap-exploitation.dhavalkapil.com/attacks/)
* [Input Validation/Sanitization](https://download.oracle.com/oll/tutorials/SQLInjection/html/lesson1/les01_tm_ovw3.htm)
* [Pseduo-random number generation](https://en.wikipedia.org/wiki/Pseudorandom_number_generator)
* [Race Conditions](https://en.wikipedia.org/wiki/Race_condition)
* [Return Oriented Programming & ROP Chaining](https://en.wikipedia.org/wiki/Return-oriented_programming)
* [Spoofing Attacks](https://en.wikipedia.org/wiki/Spoofing_attack)
* [Stack Overflows/Underflows](https://en.wikipedia.org/wiki/Stack_buffer_overflow)

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
    <th>Grade Recieved:</th>
    <td>A</td>
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

This Battleship AI program was a submission for an assignment in CPE 357, Cal Poly's Systems Programming course. For this assignment, every student had to research, write, and test their own [Battleship-playing](https://en.wikipedia.org/wiki/Battleship_(game)) AI. The algorithms would then face eachother in an automated tournament, where the highest rated player would be given a 100% assignment score, and the lowest would recieve a 0% score.

My initial approach to this problem was to use Monte-Carlo simulation, but the heavy constraints placed on CPU time prevented this from being a great option. My revised solution was a heavily modified search-and-hunt algorithm which first searched likely ship locations and then hunted any hit ships until they were sunk. This approach made heavy use of a stack, which allowed dealt with the uncertainty in Battleship by allowing the program to make guesses and then revert its state if they turned out to be wrong.

This program performed extremely well (close to the theoretical limit) and ranked above the professor's solution. Out of all the students taking the course (100+), this AI placed in the top 3, earning me a perfect score on the assignment.

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
    <th>Grade Recieved:</th>
    <td>A</td>
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

This is a 67 page research paper I wrote for my senior project at Cal Poly San Luis Obispo. This paper examines the importance (or lack thereof) of endgame tablebases in modern chess-playing AI. Endgame tablebases are essentially massive (5GB to 100TB) look-up tables for engines to reference when playing out known positions with only a few pieces remaining on the board. Their importance is a topic of debate amongst chess engine creators: modern chess engines in the endgame even without tablebases due to their ability to look many (30+) turns into the future on simple boards.

This paper uses 5,000+ games played over 800+ hours of chess gameplay to conclude that endgame tablebases provide a fairly small advantage in close games between highly skilled engines. Access to endgame tablebases will not greatly improve a poorly preforming engine, as their usefulness requires the engine reach the endgame without an insurmountable deficit. This paper also finds that "pruned tablebases", or tablebases with exceedingly rare positions removed, offer similar performance with large space savings.

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
    <th>Grade Recieved:</th>
    <td>A</td>
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

The project is a simple, robust implementation of the `malloc` family of functions in `libc` library. These are:
* `malloc`
* `realloc`
* `calloc`
* `free`

These functions are all implemented using the `sbrk` system call, which can be used to allocate or deallocate raw memory on the heap. From there, additional bookkeeping data is added to the beginning of each allocation to form a linked list. This bookkeeping data guides subsequent calls to the `malloc` family functions to ensure that memory is not lost, wasted, or overwritten.

Once implemented with proper UNIX syntax and compiled into a C library file, these malloc functions were linked with existing C programs and test cases. This demonstrated the implementation was reliable and performed reasonably well.

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

Multicontroller (also known as Chris's Multicontroller) is an extremely flexible fully-featured [multi-boxing](https://en.wikipedia.org/wiki/Multi-boxing) program that allows users to play as many as 20+ accounts at once in a variety of MMORPGs. At the time of writing, Chris's Multicontroller is one of the most capable multi-boxing programs available and contains many quality-of-life features including automatic client detection/placement, customizable keybinds, and fully programmable in-game functionality using a simple interpreted programming language.

Multicontroller uses numerous Windows API functions to draw on, resize, control, and gather information about actively running windows without injecting code or reading process memory (which would flag it as a cheat client). The program also uses the low-level Windows message passing API functions to send commands to clients without requiring them to have focus or be visible (as is required for the high-level SendInput function). Getting all of this to work reliably took a ton of research and experimentation and I'm extremely satisfied with how it's turned out so far.

Multicontroller has seen a public "narrow release" to some of my close friends to gather feedback and test functionality. At the time of writing, the program has been distributed to around 10 users and has seen a combined 1000+ hours of use with no major issues.

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
    <th>Grade Recieved:</th>
    <td>A</td>
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

[FUSE (Filesystem in Userspace)](https://en.wikipedia.org/wiki/Filesystem_in_Userspace) is a software interface for Unix-like computer operating systems that lets non-privileged users create their own file systems in user space without editing kernel code. A FUSE file system is used the same as a standard file system except that all normal system calls (ex. mkdir, mknod, read, write, etc.) are passed to and handled by the FUSE program instead of the kernal.

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

Our file system was a layered implementation of the [basic UNIX FS](https://en.wikipedia.org/wiki/Unix_File_System#History_and_evolution), containing a superblock, a list of inodes, and a list of data blocks:
* **Layer 0:** Functions that handle raw disk bytes and abstract them to disk blocks
* **Layer 1:** Functions that handle disk blocks and abstract them to inodes & data
* **Layer 2:** Functions that handle inodes and abstract them to files and directories
* **Layer 3:** FUSE integration layer

To improve performance and to match UNIX semantics, we also implented a bitmap for free inodes, an open file table, and an in-place free list. Additionally, we wrote automatic tests for each layer of our file system and added built-in debugging functionality at each step of the design process.

[[back to top](#contents)]
