# Lab 07 – Salting Effect Demonstration

## Objective
Understand how salting protects against mass password cracking.

## Theory Mapping
- Salting
- Rainbow table prevention

## Step 1: Hash Without Salt
- Command:
  
echo -n "password123" | md5sum

## Step 2: Simulate Salting
- Command:
  
echo -n "password123XYZ" | md5sum

## Observation
Same password produces different hashes.

## Learning Outcome
Salting ensures uniqueness and prevents reuse of cracked hashes.

