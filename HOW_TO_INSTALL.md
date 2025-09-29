## HOW TO INSTALL THIS VERSION

### WHAT IS IT?
This Zulip version supports %LIKE% search, which can be used to search for any characters in messages.
> This will be **slower** than PostgreSQL’s normal full-text search.

## INSTALL
1. Open `/etc/zulip/zulip.conf` and change the Zulip repository path to this repo:

```console
[deployment]
git_repo_url = https://github.com/michealapach-del/zulip.git
```

2. Run install:
```console
/home/zulip/deployments/current/scripts/upgrade-zulip-from-git 8.x-like-search
```