### Navigation:
- [Home](README.md)
- [About](about.md)
- [Contact](contact.md)

```bash
[Unit]
Description=<Node exporter>

[Service]
User=<root>
ExecStart=<prometheus-node-export>
Restart=always

[Install]
WantedBy=multi-user.target
```
