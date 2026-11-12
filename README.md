# Linux for Network Engineers

A practical collection of Linux notes, commands, and labs aimed at network
engineers: the Linux skills you need to operate, troubleshoot, and automate
network infrastructure.

> **Status:** the repository is just getting started. This README describes the
> intended scope and layout; content will be added as it is written.

## What this covers

Topics this repository aims to document, with runnable examples where possible:

- **Linux fundamentals** — filesystem layout, permissions, users and groups,
  processes, systemd services, and logs.
- **Networking on Linux** — interfaces, addresses and routes, `iproute2`,
  bridges, VLANs, bonding, network namespaces, and packet capture.
- **Firewalling and NAT** — `nftables`/`iptables` basics, forwarding, and
  masquerading.
- **Troubleshooting** — a repeatable workflow using `ip`, `ss`, `tcpdump`,
  `journalctl`, and friends.
- **Automation** — shell scripting, `ssh`, `scp`/`rsync`, and configuration
  management basics for repeatable network changes.

## Repository layout

The layout is intentionally simple and will grow with the content:

```
.
├── README.md
└── docs/        # topic write-ups and cheat sheets (planned)
```

Planned additions include `labs/` for hands-on exercises and `scripts/` for
small automation helpers.

## Prerequisites

- A Linux machine or VM to practise on. Any recent distribution works; commands
  are written to be portable across `systemd`-based distributions.
- Root or `sudo` access for the networking and firewalling exercises.
- Optional: a virtual lab (VMs, containers, or network namespaces) so you can
  change interfaces and routes without disrupting your host.

## Getting started

1. Browse the topics above and pick one.
2. Practise the commands in a disposable VM or container.
3. Keep notes of what you changed so you can roll it back.

As content lands, each topic will get its own page under `docs/` with copy-paste
commands and expected output.

## Contributing

Issues and pull requests are welcome. Please keep examples small, reproducible,
and safe to run — call out any command that changes network state or requires
root.

## License

No license has been chosen yet. Until one is added, the default copyright rules
apply.
