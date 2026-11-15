## SC-003: Unauthorised cloud sharing and upload

**Risk:** High

**Situation:** An employee attempts to upload confidential company documents to Google Drive or Dropbox or unauthorized third party sharepoint.

| Element | Design |
|---|---|
| Channel | Endpoint / Cloud application |
| Detection | Sensitive file and restricted destination |
| Action | Block upload and file sharing |
| Override | No override for Restricted data |
| Investigation | Review destination domain and file activity |

**Suggested reasoning:** Use Endpoint DLP browser and domain restrictions for supported endpoint scenarios, and Defender for Cloud Apps session controls where supported and configured. This gives us complementary protection rather than relying on a single network blocklist.

