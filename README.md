# About
This is my Ansible setup to provision tools for tinkering and hacking.
I use this on top of my [ansible-workhorse](https://github.com/aapit/ansible-workhorse) Ansible setup.

# Running the whole provisioning routine
```bash
make
```

# Running provisioning modules (roles) by tag
```bash
make tag=foo
```

Tags are defined in `site.yml`.
