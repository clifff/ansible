Ansible setup for my personal server. Right now, that just means running
some Docker scripts on a cron job.

For now, that server is a Raspberry Pi running Debian.

First run:
`ansible-playbook playbooks/bootstrap_raspbian.yml --ask-pass --become`

Subsequent runs: `ansible-playbook playbooks/pi.yml --become`
