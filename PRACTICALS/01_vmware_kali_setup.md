# Lab 01 – VMware + Kali Linux Setup

## Objective
Prepare a safe and ethical lab environment for password security analysis.

## Why This Lab Is Important
All password experiments must be done in an isolated lab.
VMware + Kali Linux provides a controlled testing environment.

## Step 1: Verify Kali Linux OS
Command:
cat /etc/os-release

Expected Output:
Kali GNU/Linux

## Step 2: Verify Hashcat Installation
Command:
hashcat --version

Purpose:
Hashcat is a professional password auditing tool used in security analysis.

## Step 3: Verify Wordlists
Command:
ls /usr/share/wordlists/

If rockyou.txt is compressed:
gzip -d /usr/share/wordlists/rockyou.txt.gz

## Ethical Note
All experiments use self-created passwords and hashes only.
No real users or systems are involved.
