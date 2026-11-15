## SC-001: Email exfiltration

**Risk:** High

**Situation:** A finance employee attempts to send a spreadsheet containing customer payment information to a personal Gmail account.

| Element | Design |
|---|---|
| Channel | Exchange Online |
| Detection | Payment card information / Restricted label |
| Action | Block external email |
| Override | No override for Restricted data |
| Investigation | Review recipient, sender and matched content |

**Suggested reasoning:** The information is highly sensitive and there is no legitimate business justification for sending payment information to a personal email account.

