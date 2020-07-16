# hash_to_emoji
Mitchell / Isthmus - July 2020

Twitter recently applied a filter that appears to block any tweets containing alphanumeric strings longer than 26 characters. Unfortunately this includes hash digests (among many other use cases).

This inspired the latest cryptographic stenographic innovation for censorship resistance: `hash_to_emoji`
 
### Example

Input: `some prediction for the future`

Output: 🐇🐈☁❄☃☃🌁🐕🌀💀☃🌁🎺🐕☃🐁✉👀🌁👀🌀🌀🐕🐁☁☃🌀☃🐈👀👍🐇☃🐈🎺🐕☂☃🐈🐇🐇❄🔔🐇❄💀☁🐇🐇☂👍☁🐕☁🔔💀🐈👍👍❄🐇🌀☃💀

### Notes 

-  The 1:1 mapping from hex representation digit to emoji is painfully inefficient. Shorter final digests could be produced by using more characters from the large emoji set. 
-  A possible extension would be an efficient (bidirectional) translation between arbitrary data blobs and emoji strings. (Silly example: can't access a p2p blockchain network to broadcast your transaction? Just convert it to an emoji string and tweet at @xyzGateway to be added to the main mempool)
