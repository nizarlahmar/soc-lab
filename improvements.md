# Possible Improvements
In this file, I have a few suggestions that can be incorporated to better this project.

## Internal 2 — Windows Machine
I think adding a Windows machine can be a good way of displaying a different breadth of vulnerabilities, such as Active Directory ones or an infamous vulnerability like EternalBlue. (When originally working on this lab, I did add a Windows 7 machine, but the OS didn't work well with QEMU/KVM).

## execve Auditing
Some commands being ran like `whoami` and `ip a` slipped by our radar. `execve` rules can be added to spot these commands too.

## Network Logs
I think it would be interesting to see network logs associated with certain actions like `nmap` scans.

## Complex Vulnerabilities
Besides surface-level vulnerabilities like a `sudo` misconfiguration, it would be interesting to add more classically-exploitable vulnerabilities, like [Shellshock](https://en.wikipedia.org/wiki/Shellshock_(software_bug)).
