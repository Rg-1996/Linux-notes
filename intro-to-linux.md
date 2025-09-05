Intro to Linux
What is Linux?

Linux is an operating system (OS), like Windows or macOS.

It is open-source and free. Anyone can modify, share, and distribute it.

Linux has two main parts:

Kernel → The core that manages hardware (CPU, RAM, disks, network).

Userland/Utilities → Tools, libraries, and applications that make the system usable.

Kernel vs Distribution

Kernel: The low-level program that talks directly to hardware.

Distribution (Distro): A complete package with the Linux kernel plus software, package manager, and sometimes a desktop environment.

Examples: Ubuntu, Fedora, Debian, Arch.

👉 Analogy:

Kernel = engine.

Distribution = car (engine + steering wheel + seats + dashboard).

Windows vs Linux

Windows uses the NT kernel.

Unlike Linux, Windows doesn’t have “distributions” → it’s closed-source and controlled by Microsoft.

PowerShell in Windows plays a role similar to Bash in Linux.

WSL (Windows Subsystem for Linux)

WSL allows you to run Linux inside Windows.

WSL1: A compatibility layer (translated Linux calls into Windows).

WSL2: A real Linux kernel inside lightweight virtualization (Hyper-V).

Check version with:

wsl --version


Example details:

WSL version

Kernel version

Distribution (Ubuntu 24.04 LTS in your case)