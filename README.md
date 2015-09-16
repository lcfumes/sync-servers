## Sync between servers ##

### How to use ###

You need add your public key in servers.

To generage keys, you can use:

```
ssh-keygen
```

The best way to utilize this script is generating a cron.

Example:

```
* * * * * sudo /srv/syncservers
```
