---
name: Bug report
about: Report a problem with DockClickToggle
title: "[bug] "
labels: bug
---

## Description

<!-- What happened, and what did you expect? -->

## Environment

- macOS version (e.g. 15.2):
- Install method (`./scripts/install.sh`, custom `INSTALL_DIR`?):
- App version / commit (`git rev-parse --short HEAD`):

## Diagnostics

Run and paste the output (redact anything personal):

```bash
./scripts/diagnose.sh --json
cat "$HOME/Library/Application Support/DockClickToggle/status.json"
tail -80 "$HOME/Library/Logs/DockClickToggle/err.log"
```

```text
<paste here>
```

## Permissions

- [ ] Accessibility granted (System Settings > Privacy & Security > Accessibility)
- [ ] Input Monitoring granted (System Settings > Privacy & Security > Input Monitoring)
- [ ] Restarted LaunchAgent after granting (`launchctl kickstart -k gui/$(id -u)/local.dock-click-toggle`)

## Steps to reproduce

1.
2.
3.
