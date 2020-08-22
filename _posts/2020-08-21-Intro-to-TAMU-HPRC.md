---
title: 'A Brief Introduction to Texas A&M High Performance Research Computing (TAMU-HPRC)'
date: 2020-08-21
permalink: /posts/tamu-hprc/
tags:
  - introduction
  - tutorial
  - supercomputer
  - High Performance Research Computing (HPRC)
---


## Overview
TAMU provides **free** HPRC accounts for everyone
- Students can have free 5000 SUs per year
- Advisors can apply for almost unlimited SUs then assign to students

Please be aware of other free computing resources
- Free Servers at the [Computer Engineering & Systems Group](https://cesg.tamu.edu/tech-resources/) of ECEN
- Check your own department's *technology resources* (e.g., computer science, industrial engineering)

## Background
### Basics
- **Google is your friend**, and learn to use [google search operators](https://moz.com/learn/seo/search-operators) when searching
- Everything is in command line on HPRC, so you need to learn basic command operations (a quick tutorial on [lifehacker](https://lifehacker.com/a-command-line-primer-for-beginners-5633909))
	- make sure you are familiar with commands: `cd`, `ls`, `mkdir`, `mv`, `rm -r`, `tail -f`
	- On WindowsOS: always use `PowerShell` (do not use `cmd`), always use `Putty` (instead of `ssh` in `Powershell`)
	- On MacOS: use [iterm2](https://www.iterm2.com/)
	- On Linux: Congrats! You made the right choice of OS!

### A little more
- Github, **Free TAMU Github Accounts** [here](https://github.tamu.edu). After Acquired by Microsoft, Github provides free private repos (with limited collaborators). Make sure you are familiar with `git add`, `git commit -m`, `git push`, `git pull`, `git rebase`
- Code editor: VIM, [an interactive tutorial](https://www.openvim.com/), [VIM primer](https://danielmiessler.com/study/vim/) [VIM cheatsheet](https://vim.rtorr.com/). Try to use numerous plugins of VIM: [best ones here](https://vimawesome.com/). Just for fun: [Emacs versus VIM](https://en.wikipedia.org/wiki/Editor_war)
- Knowledge about Bash is also helpful, [learn bash in Y minutes](https://learnxinyminutes.com/docs/bash/)

### Software Recommendations

In general

- use `git` to manage your code (NOT data)
- (optional) use software like `Fugu`/`WinSCP` to sync large files (e.g., your data and tensorflow model), command `rsync` is another option

#### Windows
- best ssh tool: [Putty](https://www.putty.org/)
- best FTP tool for data transfer: [WinSCP](https://winscp.net/eng/index.php)

#### MacOS
- command line tool: iterm2 with [oh my zsh](https://ohmyz.sh/)
- data transfer: [Fugu](https://sourceforge.net/projects/fugussh/files/)

#### Linux 
- data sync (can be installed on TAMU HPRC): [google drive linux client](https://github.com/odeke-em/drive) or [odrive](https://www.odrive.com/)

## Introduction to TAMU-HPRC
You need to replace `NETID` below with your own netid

### Get Started
- Apply for an account [here](https://hprc.tamu.edu/apply/)
- Check the hardware summary of different clusters, make sure the cluster meets your requirements (e.g., with GPUs): [ada](https://hprc.tamu.edu/wiki/Ada:Intro), [terra](https://hprc.tamu.edu/wiki/Terra:Intro), [currie](https://hprc.tamu.edu/wiki/Curie:Intro)
- TAMU HPRC staff provide detailed and excellent guides to beginners, make sure you *carefully* read through these pages: [Ada Quick Start Guide](https://hprc.tamu.edu/wiki/Ada:QuickStart), [Terra Quick Start Guide](https://hprc.tamu.edu/wiki/Terra:QuickStart)

### Basic Usage
**Suggestions: **
- Test your code on small cases locally (your laptop), try avoiding debugging on HPRC since it could be hard if you are used to IDEs 
- Use folder `/scratch/user/NETID/` if you need more storage space (upto 1T), the home foder `/home/NETID/` is limited (10GB)

Submit jobs:
- **Matlab Users**, HPRC provides a good tool `matlabsubmit`, see usage [here](https://hprc.tamu.edu/wiki/SW:Matlab_matlabsubmit) 
- **Other Users**: use `qsub` with various options. Some other comonly used commands (note: all these commands have detailed explanations in the quick-start-guide of every cluster)
  - `qsub`: submit a job to HPRC (common options `-w`)
  - `bjobs`: check job status
  - `bkill XXXX`: cancel a job
  - try to type `-h` after each command and learn more about them.
- Monitoring jobs: 
  - `bjobs JOBID` will show the progress of a specific job
  - each job will create a log file (perhaps `*.out`) , command `tail` will show the last part of the logfile, and `tail -f` willl keep showing the end of the  file (whenever it is updated)

### More 
- check available packages using `module spider`
- load a module `module load MODULENAME`


## Other Useful Links
- [ Mitchell Institute Computing, HPRC New Users and Getting Started](http://mitchcomp.physics.tamu.edu/newuserguide/hprcnewuserguide.shtml)