## In the beginning there was Unix

The story has to start somewhere and I have chosen to start at the Unix operating system. If there are any purists out there that would rather me delve deeper into the history of operating systems... Email me and you can contribute.

Things to consider when envisioning the origin of these operating systems:
- A single computer used to serve an entire university
- Computer scientists had to write all of their code and bring it to a massive

What is an operating system?
As per wikipedia:
```
  An operating system (OS) is system software that manages computer hardware,
  software resources, and provides common services for computer programs.
```

In short, the operating system is the code that manages all of the resources on your computer. The on-loading and off-loading of programs into the RAM on your computer is handled by programs written in the operating system. What is important to take note of is how many processes actually take place in order for all of these processes to take place: every single bit that is toggled is the result of very carefully thought-out code. And millions of bits get toggled every second.


Unix: Originally names `Unics`
  - was a pun on the name `Multics`
    - Multics was the operating system before Unix
    - Multics had the innovative idea of attempting to serve multiple users at once
    - this would enable more than one computer scientist to interact with the machine at once
    - Multics was supposed to be able to have 1000 users logged in at once [it could barely handle 3]
  - Unics became `Unix` when it was able to support 2 simultaneous users at once
    - This meant that computer scientists could now access the same computer at the same time

Linux:
  - On August 25, 2019 Linux Torvalds posted the following on a discussion channel:
  ```
    I'm doing a (free) operating system (just a hobby, won't be big and
    professional like gnu) for 386(486) AT clones. This has been brewing since
    April, and is starting to get ready. I'd like any feedback on things people
    like/dislike in minix, as my OS resembles it somewhat (same physical layout
    of the file-system (due to practical reasons) among other things).

    I've currently ported bash(1.08) and gcc(1.40), and things seem to work.
    This implies that I'll get something practical within a few months [...] Yes
    - it's free of any minix code, and it has a multi-threaded fs. It is NOT
    portable (uses 386 task switching etc), and it probably never will support
    anything other than AT-harddisks, as that's all I have :-(.

    [...] It's mostly in C, but most people wouldn't call what I write C. It
    uses every conceivable feature of the 386 I could find, as it was also a
    project to teach me about the 386. As already mentioned, it uses a MMU, for
    both paging (not to disk yet) and segmentation. It's the segmentation that
    makes it REALLY 386 dependent (every task has a 64Mb segment for code & data
    - max 64 tasks in 4Gb. Anybody who needs more than 64Mb/task - tough
    cookies). [...] Some of my "C"-files (specifically mm.c) are almost as much
    assembler as C. [...] Unlike minix, I also happen to LIKE interrupts, so
    interrupts are handled without trying to hide the reason behind them.

  ```
  - Linus Torvalds, unknown to him at the time, had just initiated what is known as the biggest collaborative project in human history
  - If you go to [Linux](https://github.com/torvalds/linux) on Github, you will notice that the contributor count is `infinity`
    - That is because so many people have contributed to the project that Github no longer tracks it

So why learn Linux?   
I think that this answer was well answered by my CPSC1020 professor. Knowing Linux is a unique skill and today employers need employees with as many unique (and useful) skills as possible. All of the servers that you will (hopefully) deploy your code on are going to be running some form of Linux. Knowing Linux well is going to give you the distinct advantage over other potential hires. Additionally, just knowing a very small number of tools that come standard with Linux is going to make you a very powerful programmer.
