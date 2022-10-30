# pi-calendar

Small project using Ansible to setup a Pi to run Google Calendar on startup.

## Usage

To use this, you'll need to install `ansible`.

### Install Requirements

Installing with `pip`:

`pip install --user -r requirements.txt`

### Running Playbook

To run the playbook, you'll need to know the hostname or IP address of your Pi.

For example, if hostname of the Pi is `pi-calendar`:

```bash
ansible-playbook -bkKDi pi-calendar, deploy.yml
```

_Note that the `,` is required here_

