+++
categories = ["blog"]
date = "2017-04-20T16:04:56-04:00"
description = ""
tags = ["ssh"]
title = "Add my SSH key to remote host authorized keys"

+++

Here is handy command to add my SSH key to remote host authorized keys.

```
cat ~/.ssh/id_rsa.pub | ssh <USER>@<REMOTE_HOST> "mkdir -p ~/.ssh && cat >> ~/.ssh/authorized_keys"
```

