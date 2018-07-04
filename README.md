# 1.Introduction

If you want to use Ubuntu (or any other version of Linux) as the operating system for your development related to TOP, but you don't feel like permanently changing your OS or switching back and forth between two different operating systems installed on your PC, then using a VM is probably the best option you have. VM is a shortcut for 'Virtual machine' which is a widely used program that [emulates](https://en.wikipedia.org/wiki/Emulator) a computer system. In other words, a VM allows you to run an operating system of your choice just like any other computer program. Unfortunately, such convenience comes at a price. Running a program that contains an operating system can be very heavy on your processor and RAM memory. More details about the required and recommended specs are listed later on. For now, lets look at the pros and cons of running a Virtual machine from the perspective of an average developer:

## Pros:
*Snapshots: Probably the greatest advantage of running an OS virtually compared to running a regular OS on your computer are snapshots. They allow you to save the state of your virtual operating system at any point and go back to that point if needed. This is extremely useful if you're installing stuff you're not completely sure about, playing around with settings or you simply prefered how you OS looked two days ago. A rollback is just a click away and it can be a huge life saver.
*Convenience: You can have a virtual machine up and running in a very short period of time. There's also the posibility of using a pre-configured operating system, with everything already installed on it. This can be very useful when installing a certain OS with certain applications/programs on multiple computers.
*Multiple OS' a button away: You can use multiple operating systems with your VM program with different configurations for different needs.
*No commitment: You can uninstall the VM program or delete any of the operating systems you have installed on your VM and resume using your computer as if nothing happened. This is great if you want to get a taste of a specific OS without removing your current OS. A lot of people started out with Linux on a VM and later on permanently replaced their Windows with a Linux operating system (I didn't regret it, neither will you!).

## Cons:
*Requiers a 'stronger' computer: Having nested operating systems consumes more RAM and processing power than having a regular operating system it also requires some additional space on your hard disk to store the virtual system. 
*Learning curve: Using a VM can be a bit intimidating at first, but it's not something an Odin student can't overcome.

# 2.Installation

## 2.0 Requirements

Before commiting to the installation, make sure your computer meets the [requirements](https://www.virtualbox.org/wiki/End-user_documentation) to run a virtual machine.

## 2.1 Downloads

You have read through the introduction part and you feel like a VM is your best option? Your computer meets the minimum requirements? Great, let's get started then. This is a fairly simple process and only a few things could possibly go wrong, we'll make sure to mention them. This guide uses Oracle's 'VirtualBox' program, it's open source, free and simple. What more can you ask of a piece of software? Now let's make sure we have everything downloaded and ready for installation:

### 2.1.1 Downloading Virtual Box


[Click here](https://download.virtualbox.org/virtualbox/5.2.12/VirtualBox-5.2.12-122591-Win.exe) to download VirtualBox (64 bit) for Windows.

### 2.1.2 Linux download

There are various versions of Linux out there, Ubuntu being undoubtedly the most popular one. Our recommendation is to [download](http://releases.ubuntu.com/18.04/ubuntu-18.04-desktop-amd64.iso) and use Ubuntu 18.04 LTS, if you plan on running your VM on a less powerful computer (A rough estimation would be < 4gb ram, < 4 processor cores, for more details check out their [official recommendations](https://help.ubuntu.com/community/Installation/SystemRequirements)), we recommend [downloading](https://xubuntu.org/download) and using Xubuntu 18.04 LTS.

## 2.2 Installing Virtualbox and setting up Ubuntu

### 2.2.1 The installation process 

The installation of VirtualBox is a very straight forward process. It doesn't require any technical knowledge and is the same as installing any other computer program on your Windows computer. Double-clicking the downloaded file is sufficient to start the installation process. Any additional options prompted by the installation are left for the user to decide (such as creating a desktop icon and so on). After the installation is finished (the progress bar might get stuck for a few minutes, just wait for it to finish) search for your newly installed Virtual Box program and run it.

### 2.2.2 Setting up Ubuntu



talk about specs and setting up more ram and processor, and HDD space (if the computer can handle it)
you might be able to find a calculator somewhere
rules of thumb ( a link would be best)
### 2.2.3 Installing Guest additions and enabling them

# 3.Understanding how VM works

  It's important to note a few things about coding in a virtual environment:
  
*All installations are done in the VM. Your regular operating system (Windows in this case), the one that is booted directly by pressing that big button on your computer is called the **Host** and all other operating systems that are run inside your VM are **Guests**. Now that you have everything set up it is important to know that everything you install regarding coding you install on the Guest OS (Ubuntu in this case) including Ruby,Rails,Text editors(more details about these things later on) and everything else you will need during this curriculum. This means that during the installation project, you consider yourself a Linux user, not a Windows user.
*All of the coding is done in the VM. 

# 4. Possible issues
If you can not choose anything else than a 32-bit operating system when setting up your VM look at [this](http://www.fixedbyvonnie.com/2014/11/virtualbox-showing-32-bit-guest-versions-64-bit-host-os/#.WzzZYXYzZN0)

If you do run upon a problem don't hestitate to ask for help on the [forums](https://forum.theodinproject.com/c/help) or in our [Gitter chat](https://gitter.im/TheOdinProject/theodinproject).


Things to add/change: 
-Link for VirtualBox 32-bit
-Should one download Xubuntu 32-bit or 64-bit (Xubuntu is recommended in absence of a powerful pc to run Ubuntu, so my question is which is less hardware consuming and at which cost?)
-I removed Hyper-V from the guide, most people don't have access to it and I think it could just complicate things. I could use more opinions on this matter
