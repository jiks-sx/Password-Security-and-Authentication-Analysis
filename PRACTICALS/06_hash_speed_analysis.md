# Lab 06 – Hash Speed Analysis

## Objective
Understand why fast hashes are insecure for passwords.

## Theory Mapping
- Hash speed vs security

## Step 1: Benchmark MD5 Speed

- Command:
hashcat -b -m 0

## Observation
MD5 can be computed billions of times per second.

## Security Impact
Fast hashes allow attackers to test massive numbers of passwords quickly.

## Learning Outcome
Password hashing must be slow to reduce attacker efficiency.

