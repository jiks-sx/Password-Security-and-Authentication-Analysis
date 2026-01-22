
# Lab 09 – bcrypt Password Hashing

## Objective
Understand why bcrypt is used for secure password storage.

## Theory Mapping
- Slow hashing
- Built-in salting
- Key stretching

## Step 1: Generate bcrypt Hash
- Command:
  
htpasswd -bnBC 12 "" Password@123 | tr -d ':\n'

## Observation
- Hash contains salt
- Cost factor is visible
- Computation is slower

## Learning Outcome
bcrypt increases attacker cost by design.
