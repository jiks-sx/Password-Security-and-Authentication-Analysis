# Lab 02 – Password Hashing Basics

## Objective
Understand how the same password behaves with different hash algorithms.

## Theory Mapping
Related to:
- Hashing fundamentals
- One-way functions
- Deterministic property

## Step 1: Choose a Test Password
Password used:
Password@123

## Step 2: Generate MD5 Hash
echo -n "Password@123" | md5sum

## Step 3: Generate SHA-256 Hash
echo -n "Password@123" | sha256sum

## Observation
- Same password
- Different hash outputs
- Different output lengths

## Learning Outcome
Hashing is deterministic but algorithm-dependent.
