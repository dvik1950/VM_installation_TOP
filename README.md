# 1.Introduction

If you want to use Ubuntu (or any other version of Linux) as the operating system you code on, but you don't feel like permanently changing your OS or switching back and forth between two different operating systems installed on your PC, then using a VM is probably the best option you have. VM is a shortcut for 'Virtual machine' which is a widely used program that [emulates](https://en.wikipedia.org/wiki/Emulator) a computer system. In other words, a VM allows you to run an operating system of your choice just like any other computer program. Unfortunately, such convenience comes at a price. Running a program that contains an operating system can be very heavy on your processor and RAM memory. More details about the required and recommended specs are listed later on. For now, lets look at the pros and cons of running a Virtual machine from the perspective of an average developer:

Pros:
*Snapshots: Probably the greatest advantage of running an OS virtually compared to running a regular OS on your computer are snapshots. They allow you to save the state of your virtual operating system at any point and go back to that point if needed. This is extremely useful if you're installing stuff you're not completely sure about, playing around with settings or you simply prefered how you OS looked two days ago. A rollback is just a click away and it can be a huge life saver.
*Convenience: You can have a virtual machine up and running in a very short period of time. There's also the posibility of using a pre-configured operating system, with everything already installed on it. This can be very useful when installing a certain OS with certain applications/programs on multiple computers.
*Multiple OS' a button away: You can use multiple operating systems with your VM program with different configurations for different needs.
*No commitment: You can uninstall the VM program or delete any of the operating systems you have installed on your VM and resume using your computer as if nothing happened. This is great if you want to get a taste of a specific OS without removing your current OS. A lot of people started out with Linux on a VM and later on permanently replaced their Windows with a Linux operating system (I didn't regret it, neither will you!).

Cons:
*Requiers a 'stronger' computer: Having nested operating systems consumes more RAM and processing power than having a regular operating system it also requires some additional space on your hard disk to store the virtual system. 
*Learning curve: Using a VM can be a bit intimidating at first, but it's not something an Odin student can't overcome.

# 2.Installation
## 2.0 Requirements

Before commiting to the installation, make sure your computer meets the [requirements](https://www.virtualbox.org/wiki/End-user_documentation) to run a virtual machine.

## 2.1 Downloads
verify 64/32 bit windows
enabling hyperV on 64bit
download proper linux version
for a powerful computer: ubuntu 18.04 LTS
less powerful: xubunut 18.04 LTS
download correct virturalbox version
# 2.2 Installing Virtualbox
Install Virturalbox
install linux as a VM
talk about specs and setting up more ram and processor, and HDD space (if the computer can handle it)
you might be able to find a calculator somewhere
rules of thumb ( a link would be best)
Installing Guest additions and enabling them
Step 3: Understanding (?)
All installations happen in the VM
All development work happens in the VM
Issues they might run into.
