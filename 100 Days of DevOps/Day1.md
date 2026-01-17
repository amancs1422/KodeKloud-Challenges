## Linux User Setup with Non-Interactive Shell

### The task is to create a user john with a specific uid and a non interactive shell.

```
sudo useradd -u 1998 john
```
```
sudo usermod -s /sbin/nologin james
```
