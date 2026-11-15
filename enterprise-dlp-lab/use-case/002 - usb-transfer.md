## SC-002: USB data transfer

**Risk:** High

**Situation:** An employee copies confidential customer records from a company laptop to a personal USB drive.

| Element | Design |
|---|---|
| Channel | Endpoint |
| Detection | Confidential sensitivity label |
| Action | Block copying to removable media |
| Override | Business justification for approved exceptions |
| Investigation | Review user, device, file and USB activity |

**Suggested:** Some operational teams may require removable storage for legitimate business activities. We should restrict unauthorised transfers while maintaining controlled exceptions.
