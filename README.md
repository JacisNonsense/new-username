## This username is old, find me here now: https://github.com/JaciBrunning
After I changed my username, I stood up this account to make sure the username doesn't get sniped and 
old links to my repos recreated maliciously. I changed my username mostly to fit with my new handle on most 
other platforms.

When you change your username on github, github will stand up redirects to all your repositories (https://github.com/JacisNonsense/Pathfinder -> https://github.com/JaciBrunning/Pathfinder). However, someone can come in and
make a new account with that old username and stand up a new repository with the same name, breaking the redirect. For legacy tooling that relies on those names (like build system, install scripts, etc), the repository can be replaced with malicious data that may execute on the user's system. Since a lot of my repos are linked to by FRC tooling, I've decided to stand up this account to prevent those repos from being made for malicious purposes.

## You can verify this is me!
My main github account [`jacibrunning`](https://github.com/JaciBrunning) is verified against my keybase account [`jaci`](https://keybase.io/jaci). You can verify the below message signed with my private key in a few ways.
- Through Keybase: https://keybase.io/verify
- Through `gpg`:
  - Save the below PGP message in a file `jaci.msg`
  - Import my public key into `gpg`
    - Via keybase: `keybase pgp pull jaci`, or...
    - Manually. My main github account contains my public pgp key [here](https://github.com/JaciBrunning/keys). Keybase also has a copy of this key. Import it with `gpg --import <file>`
  - Verify or decrypt the message with `gpg --verify jaci.msg` or `gpg --decrypt jaci.msg`.
    - If you imported the key manually, it may state the key is not certified. Essentially this says "are you sure this public key came from a source you trust?".

```
-----BEGIN PGP MESSAGE-----

xA0DAAgBvHSmPkJN5s4By+F0AOIAAAAA5UphY2kgdG8gV29ybGQ6IENvbmdyYXRz
LCB5b3UndmUg42dvdCBteSBt4mVzc2HhZ2XgLgDCwVwEAAEIABAFAl7twsUJELx0
pj5CTebOAAC8EhAAt/G8PedHruqhjKLQ4GYGlteawHr3EY39o95LFjV/uYABjcrn
9s5BGLQFyZY5ADbHZda8C5r+Zsa7CGXRQKowVY73tYM/3rbD9guuz06ZYMyfYeD5
iFvshL2ibKccnHq9cEi8F3marVp9uWhYuOZeU7HgXm9qN3YX1sRgZXjO23MSywL3
qwKknTlw4njZ28W5cgBRDnR/R5/LX4vrpyHnvJqmsRhNpAm7qQ3LrN33YGS5Va7d
+uf+lzV1Riw0iTcpyW9tC5878ubyUNPpDk3nxPTYN3bNE1bnhgGL3veTi5zXRtXC
ckv227PbZktet+PavX5D0xMHgN+qx8VMcNOr+pDPV8yaokWX9n1nYPUtN9SbuNY/
N813o73lg93u6mZWRBP0qSD6a7cljG15hAY7yPnpGEIRa3RomBZcngpuDFgb2DhX
sIFGXhpDdT99E9EXh54tU9YMgg5mU4NAqKFcWeik152AVPz82J4oD+/Vywz3H1Vg
JKgBjKjXKubyjXce9hdxbtvzUbF6qvdm1//kwvQUSECU9q2MB63xQbVFMh2Bqk0H
ooe+66Obp3tqxIAKY6APFgLRA/tqX7M4Fsix9TaWyoxPZ92luORGZSNVeYW6bi+5
xXlXAQrGEKnJxsjV26qZjNQwuFfR9g2aiFd4H0LWBslRefXslIh7Rf0HmqY=
=Fb0U
-----END PGP MESSAGE-----
```

