# CTF Challenge: Base64 Forensics

## Overview

This repository contains a simple Capture‑the‑Flag (CTF) challenge designed to test your ability to handle basic encoding schemes and file manipulation.  The goal is to recover a hidden flag from an encoded string.

### Challenge Description

In the file [`challenge/encoded.txt`](challenge/encoded.txt) you will find a mysterious string.  Your task is to determine how the string is encoded, decode it, and extract the flag.  The flag follows the standard CTF format: it starts with `flag{` and ends with `}`.  Once you have recovered the flag, you can validate your solution by comparing it to the known answer in the `solution/README.md` file.

**Hint:** examine the character set and length of the encoded string.  Common encodings often reveal themselves through these clues.

### Repository Structure

- `challenge/encoded.txt` – the file containing the encoded string you must decode.
- `solution/README.md` – the solution explanation and the flag (spoilers!).  Avoid reading this until you've solved the challenge on your own.

### How to Play

1. Clone this repository to your local machine or open the `encoded.txt` file directly in the GitHub web interface.
2. Inspect the contents of `encoded.txt`.
3. Identify the encoding method used and decode the string.
4. The decoded text will reveal the flag in the format `flag{...}`.
5. (Optional) Compare your decoded flag with the answer in `solution/README.md` to verify your solution.

### License

This challenge is released under the MIT license.  Feel free to use and modify it for your own training or events.
