# SigmaOS-asusctl

SigmaOS integration component for **ASUS ROG control**.

## Commands

```bash
sigmaos-asusctl install   # install package + deploy defaults
sigmaos-asusctl deploy    # copy config templates to $HOME
sigmaos-asusctl status    # binary/package/config report
sigmaos-asusctl reset     # remove deployed config
sigmaos-asusctl open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
