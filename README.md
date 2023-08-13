# Node Instructions

Created: April 1, 2021 4:21 PM

[Cardano node 1.26.2 Installation Instructions](https://instructions.target-pool.com/v/english/)

[input-output-hk/cardano-node](https://github.com/input-output-hk/cardano-node/blob/master/doc/stake-pool-operations/register_stakepool.md)

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
