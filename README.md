# Gnosis Pay Incident — Flagged Address List

> **Authoritative, public list of addresses compromised in the Gnosis Pay incident.**
>
> 🔔 Follow-ups & updates: [**@gnosispay** on X](https://x.com/gnosispay)

This list exists so that block explorers, wallets, and analytics/compliance providers can flag affected addresses and **warn users before they send funds
that would be lost.**

- **Chain:** Gnosis Chain (`chainId = 100`)
- **Format:** addresses are lowercase, EVM-format — match them case-insensitively
- **Maintained:** updated as the investigation continues; watch the repo for changes

---

## 🚫 Attacker addresses

Destinations that received drained funds. **Do not send funds to these — funds will be lost.**

```
0xf9db86db4ff8ea2a1364544700d076f59edbcc91
0x81ba8a2b895d30280bca199c2ff75f3f058d4c6c
0xd43d0660601e613f9097d5c75cd04ee0c19e6f65
0x05c90145654aa7edd9186a96c3e6487dfeacf094
0xe43f519f6595b89743235b90ce910b9b85b39a15
0x0000000000004f3d8aaf9175fd824cb00ad4bf80
0x7503fe3cd8320c93b116d4a64aceeb2dd8be7ab8
0x463d9721047cb88149ef97421cf35a2e86fe5be4
```

Also available as [`data/attacker_addresses.csv`](data/attacker_addresses.csv).

## 🔒 Compromised Safes

Safes affected by the incident — believed compromised and at risk. They previously belonged to
legitimate users and organizations and **are now believed to be controlled by an
attacker** — so they are the priority for wallet warnings, since users may have
them saved as contacts.

→ **Address list (47,377 Safes):** [`data/joined_unique_safes.csv`](data/joined_unique_safes.csv)
— one address per line, ready for ingestion.

---

## ⚠️ The warning we ask partners to show

> This address is on the Gnosis compromised Safe list. It may have previously
> belonged to a user or organization, but is now believed to be controlled by an
> attacker. Sending funds here may result in loss of funds.

Background: 📢 [Gnosis Pay statement](https://x.com/gnosispay/status/2061831214273564986)
· 🛡️ [Zodiac / Gnosis Guild](https://x.com/zodiaceco/status/2061862711206502902)

---

<sub>Flagged in the context of the Gnosis Pay incident to protect users from loss of funds. Inclusion reflects this incident only.</sub>
