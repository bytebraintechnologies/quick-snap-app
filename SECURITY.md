# Security policy

## Reporting a vulnerability

Do not disclose a suspected vulnerability in a public issue.

Use GitHub's
[private vulnerability reporting](https://github.com/bytebraintechnologies/quick-snap-app/security/advisories/new)
with affected versions, reproduction steps, expected impact, and supporting material. Remove
personal or confidential image, recording, clipboard, and log content whenever possible.

Bytebrain will acknowledge a complete report, investigate it, and coordinate disclosure after a fix
is available. Please do not publish details while the investigation is active.

## Verifying downloads

The Microsoft Store package is the trusted Windows production distribution and is signed by
Microsoft.

GitHub portable previews are intentionally unsigned. Each archive has a matching `.sha256` file and
is published in an immutable release. A checksum detects a modified download but does not establish
an operating-system publisher identity. The operating system may warn about or block these previews.
