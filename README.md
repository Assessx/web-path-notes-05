# web-path-notes-05

Mixed path / bypass notes (38 entries).

Categories in this repo are intentionally mixed: admin-api, app-api,
backup/export, log/config/source, PHP, WAF bypass.

```bash
ffuf -u https://target.com/FUZZ -w paths.txt -mc 200,204,301,302,401,403,500 -ac -rate 40 -t 20
```
