# Solution: Base64 Forensics

## Decoding Process

1. Open the file [`challenge/encoded.txt`](../challenge/encoded.txt) and copy the contents: `ZmxhZ3tyZXZlcnNlX2Jhc2U2NF9pc19mdW59`.
2. Notice that the string uses only the characters `A–Z`, `a–z`, `0–9`, `+` and `/`, and its length is a multiple of four.  These characteristics are a strong indicator of Base64 encoding.
3. Use any Base64 decoding tool or library (for example, the `base64` command on Unix systems or an online decoder) to decode the string.
4. Decoding yields the plaintext `flag{reverse_base64_is_fun}`.

## Flag

The flag for this challenge is:

```
flag{reverse_base64_is_fun}
```
