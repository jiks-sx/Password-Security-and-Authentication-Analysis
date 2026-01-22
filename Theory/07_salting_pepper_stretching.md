# Salting, Peppering, and Key Stretching

## Salting

Salt is random data added to a password before hashing.

Purpose:
- Ensure same passwords have different hashes
- Defeat rainbow tables

Salt is public and stored with the hash.

## Peppering

Pepper is a secret value stored separately from the database.

Purpose:
- Adds an extra secret
- Protects even if database leaks

Pepper is optional but powerful.

## Key Stretching

Key stretching increases computation time.

Methods:
- bcrypt cost factor
- Argon2 time parameter

Key stretching slows attackers significantly.
