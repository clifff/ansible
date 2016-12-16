Ansible setup for my personal server. Right now, that just means running
some Docker scripts on a cron job.

For now, that server is a Raspberry Pi running Hypriot.


First run:
`ansible-playbook playbooks/bootstrap_hypriot.yml --ask-pass --sudo`

Subsequent runs: `ansible-playbook playbooks/pi.yml --sudo`
