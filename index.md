---
layout: default
---

# Why does this exist

This is just a place for me to play around with Github Pages. I may do something with it at some point but I have no plans for it.

---

### Since you wasted time coming here, help yourself to a python password generator

```python
#!/usr/bin/python3

import string
from random import *

length = int(input("Enter password length: "))
characters = string.ascii_letters + string.punctuation  + string.digits
password =  "".join(choice(characters) for x in range(length))

print(f"\n{password}")
```

* Contact
  * [Mastodon](https://fosstodon.org/@mthehorrible)
  * Matrix: @mthehorrible:kde.org
  * XMPP: mthehorrible@jix.im
* Other Sites
  * [mthehorrible.cc](https://mthehorrible.cc)
  * [xrandomness.com](https://xrandomness.com)
  * [xhskateboards.com](https://xhskateboards.com)

