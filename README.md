# GRC Homelab

Personal Lab for learning control implementation, testing, and risk documentation. NOT a production environment

## Scope

| Asset | Role | OS  | Notes |
| --- | --- | --- | --- |
| fedora-host | Workstation + scan engine | Fedora 42 | Bare Metal |
| ubuntu-srv | Server asset | Ubuntu 24.04 LTS | VM, CLI |
| win11-ep | Endpoint asset | Windows 11 Eval | VM, snapshot-based |

## Frameworks

- **CIS Controls V8** - control spine (18 controls, 153 safeguards)
  
- **NIST CSF 2.0** - outcome mapping (Govern/Identify/Protect/Detect/Respond/Recover)
  

## Method

1. Pick a control
  
2. Implement it technically on an asset
  
3. Write a repeatable test command
  
4. Capture evidence as raw output
  
5. Record pass/fail in the register
  
6. Deliberately break it, confirm the test fails
  
7. Restore, note the drift
