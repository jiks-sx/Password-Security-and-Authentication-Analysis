# Why Password Hashes Still Get Cracked

## Important Truth

Hashing does NOT prevent guessing.
Hashing only prevents reversing.

## Offline Attack Concept

If attacker steals the database:
- They can try unlimited guesses
- No system rate-limiting applies

Attack method:
1. Guess password
2. Hash guess
3. Compare with stored hash

This is called an offline attack.

## Why Weak Passwords Fail Even With Hashing

Hashing protects storage, not password strength.

Weak password + fast hash = instant compromise.
