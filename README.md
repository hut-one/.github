<div align="center">

<br>

# 🏈 HUT.ONE

### The Playbook for Private Infrastructure

**Your servers. Your keys. Your privacy.**

</div>

## What is Hut.one?

Hut.one provides the tools to turn any Linux machines you own into a cryptographically separated, multi-hop VPN network. 

Unlike commercial VPNs where a single provider sees everything, our architecture uses a **relay/exit separation** model:

```text
You ──► Relay (sees your IP, can't decrypt) ──► Exit (decrypts, can't see you) ──► Internet
```

**No single node has the complete picture.**

## 📦 The Roster

| Repo | Description | Visibility |
|------|-------------|:----------:|
| [**hut-one**](https://github.com/hut-one/hut-one) | 📖 **The Playbook:** Open-source provisioning scripts, `nftables` configs, and WireGuard templates. | Public |
| `hut-one-app` | 🖥️ The desktop orchestration client (Coming Soon). | Private |
| `hut-one-web` | 🌐 The marketing site and waitlist. | Private |

## 🛡️ Security & Trust

Privacy tools should be auditable. That's why our core infrastructure scripts are 100% open-source.
- Default-deny `nftables` firewalls
- Fail-closed forwarding (no IP leaks)
- SSH key-only authentication
- Zero telemetry

Read our [Threat Model](https://github.com/hut-one/hut-one/blob/main/docs/threat-model.md) in the playbook repo to see exactly what we protect against.

---

<div align="center">

*Privacy is a team sport.*

📧 [team@hut.one](mailto:team@hut.one) • 🛡️ [security@hut.one](mailto:security@hut.one)

</div>
