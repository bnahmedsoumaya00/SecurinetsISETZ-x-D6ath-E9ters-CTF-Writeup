

**Name**: blackbird  
**Level**: Hard  
**Points**: 700  

---


## Description

The Old World blackbird lives in woods and gardens in Europe, Asia, New Zealand, Australia and other places. One of these places is so famous this year especially with its beautiful spring weather. Could you find this place?

**Flag format**: `Securinets{}`

---

## Solution

1. We are given a bird-themed challenge. A useful hint is the tool: [Birds on a wire cipher - dCode](https://www.dcode.fr/chiffre-oiseaux-sur-un-fil).
2. We follow the birds in the given picture one by one using the above tool.
3. If done correctly, we get the following cipher:

   ```
   Cipher 1: KNSWGFOURTVNFXGKFIVEDTPNFIVEGSTHREETHREENFTHREEVSIXSIXJXMFTHREEWKSIXFOURSEVENTWOZMZUVSIXSIXTBMFIVEUGSIXFIVELBNZSIXQ
   ```

4. We notice that the cipher includes numbers written in letters (e.g., `FOUR`, `THREE`, `FIVE`, etc.).
5. Replacing the number words with digits gives:

   ```
   Cipher 2: KNSWG4TVNFXGK5DTPN5GS532NF3V66JXMF3WK427MZUV66TBM5UG65LBNZ6Q
   ```

6. Trying to identify the cipher, we find that it is Base32 (can be detected using dcode.fr).
7. Decoding the Base32 string gives us the flag.

---

## Flag

```
Securinets{ziwziw_y7awes_fi_zaghouan}
```