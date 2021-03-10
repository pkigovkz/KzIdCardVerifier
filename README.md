### KZ ID-Card key pairs verifier

------

This utility verifies whether it is possible to generate 4 keypairs (or at least 2 key pairs) in a Kazahstani ID-Card. Each passed step prints SW (status word) in decimal. After each generation process it signs SHA1("test") with a corresponding key.

**ATTENTION!**

- You will block your card if you enter wrong pin 3 times in a row.
- You will erase (due to a GENKEY command) your current key pairs if you enter correct pin.
