# Lab 07 – Effect of Salting

## Objective
Understand how salting changes hash behavior.

## Theory Mapping
Related to:
- Salting
- Rainbow table prevention

## Step 1: Hash Without Salt
echo -n "password123" | md5sum

## Step 2: Simulate Salt
echo -n "password123XYZ" | md5sum

## Observation
Same password produces different hashes.

## Learning Outcome
Salting breaks hash reuse and precomputed attacks.
