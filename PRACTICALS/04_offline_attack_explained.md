# Lab 04 – Offline Attack 

## Objective
Understand how attackers crack passwords after database leaks.

## Theory Mapping
- Offline attacks
- Why hashing alone is not enough

## Step 1: Create a Hash File
Command:
echo "482c811da5d5b4bc6d497ffa98491e38" > hash.txt

(This is the MD5 hash of 'password123')

## Step 2: Understand the Attacker Advantage
Attacker has:
- Hash file
- Unlimited guesses
- No rate limits
- No alerts

## Learning Outcome
Once hashes are stolen, system-side protections no longer apply.

