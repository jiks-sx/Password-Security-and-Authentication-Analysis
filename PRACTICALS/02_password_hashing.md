# Lab 02 – Password Hashing 

## Objective
Understand how hashing converts passwords into non-reversible values.

## Theory Mapping
- Hashing fundamentals
- One-way functions
- Deterministic behavior

## Step 1: Select Test Password
Password used:
Password@123

## Step 2: Generate MD5 Hash
Command:
echo -n "Password@123" | md5sum

## Step 3: Generate SHA-256 Hash
Command:
echo -n "Password@123" | sha256sum

## Observation
- Same password
- Different algorithms
- Different hash outputs

## Learning Outcome
Hashing depends on the algorithm used, not just the input.
