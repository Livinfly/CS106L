## Environment

-   Platform: Windows - windows subsystem Linux 2 (WSL 2)

## Notice

I add some `std::cerr` to help myself figure out the process of the code, so you maybe just compare with the origin assiment files or might be confuse.

## Table of contents

0.   [Lecture_Note_Fall_2019](https://www.youtube.com/playlist?list=PLCgD3ws8aVdolCexlz8f3U-RROA0s5jWA)

     This is probably for personal backup.

1.   [Wikiracer_Winter_2023](https://web.stanford.edu/class/archive/cs/cs106l/cs106l.1234/assignment2.html)

     For self-testing, just as tutor says, `setup.sh`, `test-wikiscraper.sh`, and when execute these fail, following is some solutions.

     -   `no cmake`：

         `apt install cmake`

     -    `no test in build`：

         Check your files and folders named simply, which means not contain special characters like space, dot or something.(best keep all English?) Don't convince if all of these not work, but i replace by underline, then work.

         Might it still doesn't work, for me, it be the bug of my task-code.

     -   if you need proxy in wsl, you need to do the following prepare.

         `cat /etc/resolv.conf` get one ip, then `export ALL_PROXY="http://[the ip you get]:[your proxy port]" 

         then you can `wget google.com` to test if its ok.

2.   [STL_HashMap_Fall_2022](https://web.stanford.edu/class/archive/cs/cs106l/cs106l.1232/assignment3.html)


By the way, More resourse can be found [here](https://github.com/OleehyO/CS106L).
