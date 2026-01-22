# Lab 05 – Dictionary Attack 

## Objective
Demonstrate how human behavior leads to password compromise.

## Theory Mapping
Related to:
- Dictionary attacks
- Human password choices

## Step 1: Use RockYou Wordlist
Wordlist contains leaked real-world passwords.

## Step 2: Run Hashcat Dictionary Attack
hashcat -m 0 -a 0 hash.txt /usr/share/wordlists/rockyou.txt

## Result
password123 is cracked in seconds.

## Why This Worked
- Weak password
- Common wordlist
- Fast hash algorithm

## Learning Outcome
Most real-world breaches occur due to dictionary attacks.
