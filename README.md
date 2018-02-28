# Taming SELinux with Ansible
A talk to be given at the DevOps Perth Meetup on [28 Feb 2018](https://www.meetup.com/DevOps-Perth/events/247818662/)

## Blurb

SELinux is a part of the Linux kernel.  It stands for Security-Enhanced Linux and was invented by the NSA (I kid you not) and Red Hat.

Essentially, SELinux locks down a Linux system using a labyrinthine collection of policies that restrict what any given process (even one running as root) or user can do.  This is intended to limit the damage or exposure that can be done by a compromised web site, for example.  In practice, it makes adminstering a Linux system a lot harder, because a lot of the basic assumptions about security and access rules simply no longer apply.  It is so complex that it can give you a very bad day if you are not careful.

This talk intends to show that manual configuration of SELinux policies is no longer required.  Instead, once you have created the policy files, you can use Ansible to install them across part or all of your server fleet.

## Outline

1. Ansible recap
2. SELinux intro
3. Comedy sequence
4. Detail of operation inc. Policies
5. Ansible roles
6. Example

## Presenter bio

Alastair is a Software Engineer and system administrator by trade.  He has a BSc in Computer Science from Curtin University.

His computer-related interests lie in various areas within his trade; suffice to say that he is a "geek of many colours". :)  Alastair is a die-hard FOSS user and Linux fan.

He is also a freelancer with his own business.  [Warpspace IT](http://www.warpspace.net/) is a consultancy with a fairly broad focus on the technical side of IT.

## Slides

**TBA**
