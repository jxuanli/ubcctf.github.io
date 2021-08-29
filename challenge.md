--- 
layout: challenge 
title: Challenges | CTF @ UBC 
---

# Reversing

x86 binary

```
8b64240844464c614731db4331fd6681ff676c751d31fe81fd541840
1a7513c1ef106681ff6167750981fe1c1f165475014b31c040cd8090
```

# Pwn

```
nc 152.67.233.218 6969
```

[Source exe](https://drive.google.com/file/d/15mBjhZ2czhF4d0cTBkW4ZAHd5_lVp4pw/view?usp=sharing)

[Source code](https://drive.google.com/file/d/1op6YplcAflHZzy3bIugVVoJJOachG4fd/view?usp=sharing)

# Crypto

Stack exchange says everyone uses AES-GCM, but I don't need the tag so I'll just use CTR

- [gen.py](/assets/challenges/beginner-crypto/gen_no_comments.py)
- [secret.enc](/assets/challenges/beginner-crypto/secret.enc)

For complete newcomers, I would recommend giving this [companion guide](/2021/08/beginner-crypto/) a read, it covers some background and gives you the gist of how this challenge is solved

# Web

[Steal our secrets](http://152.67.233.218:1337)

# Forensics

There's nothing here... or is there?