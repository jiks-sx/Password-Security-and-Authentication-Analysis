# Lab 05 – Dictionary Attack 

## Objective
Demonstrate how human password choices lead to compromise.

## Theory Mapping
- Dictionary attacks
- Human behavior in password selection

## Step 1: Run Dictionary Attack
Command:

hashcat -m 0 -a 0 hash.txt /usr/share/wordlists/rockyou.txt

## Step 2: Display Cracked Password
Command:
hashcat -m 0 hash.txt --show

Expected Result:
password123

## Why This Worked
- Weak password
- Common wordlist
- Fast hashing algorithm

## Learning Outcome
Dictionary attacks are the most effective real-world password attack.
