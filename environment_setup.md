# Introduction to Linux / UNIX and the Bash shell: setting up your environment

Please complete the setup instructions given in this document
**before the start of the course**.

<br>

## macOS 🍏

**No need to install anything**: macOS comes by default with a "Terminal"
application that launches a **`zsh` shell**. For the most part, the `zsh` and
`bash` shells behave very similarly, and you can follow this entire course
using the `zsh` shell.

To start a shell session, open the "Terminal" application.

> **✨ Note:** macOS also comes with a version of `bash` pre-installed, but
> it is a rather old one (`3.2`, kept at that version for licensing reasons).
> We therefore do not recommend using it for this course.
>
> If you nevertheless wish to run `bash` instead of `zsh`, it is possible to
> install a recent version of `bash` using the
> [Homebrew package manager](https://brew.sh).

<br>
<br>

## Windows 🪟

Windows does not natively come with a `bash` shell, but it can be installed
via different means. We suggest two options, in order of ease of installation
(easiest first).

> **✨ Note:** Git Bash (option 1) is sufficient for this course. Choose WSL
> (option 2) if you want a genuine Linux environment. Installing WSL requires
> admin privileges.

<br>

### Option 1: Git Bash

Install [Git for Windows](https://gitforwindows.org), which comes with a
`bash` shell named **Git Bash**.

To start a shell session, open the "Git Bash" application from the Windows
Start menu.

<br>

### Option 2: WSL - Windows Subsystem for Linux (requires admin privileges)

**WSL**, the Windows Subsystem for Linux, is essentially a small Linux
distribution running inside your Windows machine.

For instructions on how to install WSL, please see the
[Microsoft documentation](https://learn.microsoft.com/en-us/windows/wsl/install).
Alternatively, WSL can also be installed via the Microsoft Store - search for
the "Ubuntu" application (Ubuntu is the name of a popular Linux distribution).

To start a shell session, open the "Ubuntu" application from the Windows
Start menu. Note that on the first startup of WSL, you will be asked to choose
a username and password for your Linux user.

<br>
<br>

## Linux 🐧

**No need to install anything**: virtually all Linux distributions come with a
recent version of **`bash`** installed out-of-the-box.

To start a shell session, open your desktop's terminal application (the exact
name of the app varies depending on the Linux distribution you are using).

To check your version of `bash`, run:

```sh
bash --version
```

Ideally, you should have a version of `bash` >= `5.0` (but at least >= `4.0`).
