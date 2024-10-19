# Get started

## Prerequisite
- SSH server installed and running
- Add public key to kali for passwordless login
- Have user `kali` that can privesc with `sudo`

## Action
- Create `hosts.ini` with host configuration for `kali`
- Run `ansible-playbook -i hosts.ini playbook.yaml -u kali --ask-become-pass`
- Profit!
