# Welcome to my GitHub!
## When i'm not making music, I like doing stuff in my free time.

This includes:
* Reverse engineering
* CNO Development
* Vulnerability research
* BBQing meat
* Working out at the gym
* Blasting the subs in my truck

## Languages and Tools
- C
- Python
- x86/x86-64 Assembly
- Ghidra
- objdump -M intel -D binary.elf | less


## Current Project:
### Shellrealm is linux based command and control (C2) framework made to practice CNO development.

### (Will be supported on Ubuntu 22.04 and Arch Linux) 

![Demo!](/demo/shellrealm-demo-5.png)

#### In this proof-of-concept, we did the following:
* Infected computer 192.168.69.69 with a payload called exploit
* Sent over a rootkit called malware to 192.168.69.69
* Accessed compromised computer 192.168.69.69 with a reverse shell
* Caused chaos and destruction :)

#### Shellrealm features:
* Built-in Shell Environment
* Payload Crafting and Delivery
* Secure Encryption
* Remote Access Capabilities
* Linux Kernel Module Rootkit

C2 Framework Design:
```
+-----------+      +---------+      +------------+      +-------------------+
| C2 Server | ---> | Rootkit | ---> | Obfuscator | ---> | Victim's Computer |
+-----------+      +---------+      +------------+      +-------------------+
     |                                                           /^\
     |                                                            |
     +--------------------> Payload Exploit ----------------------+
```

### Project Link Here:
https://github.com/dilldylanpickle/Shellrealm

## Some Fun Tool Buired in my Repo
### ROPcheck is a linux exploit development tool used for identifying potential Return Oriented Programming (ROP) gadgets in ELF executable files.
### (Currently supported on Ubuntu 20.04 and Arch Linux) 
![Demo!](/demo/animated_demo_v7.gif)

### Project Link Here:
https://github.com/dilldylanpickle/ROPcheck

#### Bonus, I used ROPcheck to solve all of ROP Empoirum's challenges:
![Demo!](/demo/ret2win32.png)
https://github.com/dilldylanpickle/ROP-Emporium-Solutions

## DeepVoicePickle's Binary Exploitation Roadmap
### A detailed roadmap series that serves as a step-by-step guide on binary exploitation!
#### (Also, this roadmap is heavily inspired by ret2systems and pwn.college. Lastly, I am not an expert)
![Demo!](/demo/Binary-Exploitation-Roadmap-v2.png)

### Project Link Here:
https://github.com/dilldylanpickle/Binary-Exploitation-Roadmap
