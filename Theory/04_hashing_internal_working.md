# Hashing – Internal Working Explained

## What Is Hashing?

Hashing converts input data into a fixed-size output called a hash.

Example:
password → hash

## Why Hashing Is Used for Passwords

The system does not need to know the password.
It only needs to verify correctness.

Hashing allows verification without disclosure.

## Properties of a Secure Hash Function

1. One-Way Function
   Easy to compute, infeasible to reverse.

2. Deterministic
   Same input always produces same output.

3. Fixed-Length Output
   Input size does not matter.

4. Avalanche Effect
   Small input change produces unpredictable output.

## How Login Works Internally

Registration:
- User enters password
- Password is hashed
- Hash is stored

Login:
- User enters password
- Password is hashed again
- Hashes are compared

Plain passwords are never stored.
