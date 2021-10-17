# Cfork

A Swift package wrapping the fork() system call. Swift on Linux allows for fork to be called directly, however, Swift on MacOS will refuse to built code that calls fork() directly. This package serves as a way to get around these cross-platform differences.

```
import Cfork

_ = cfork()
```
