 Ansible playbook for pulseaudio
===========================

This ansible role install some components you need for pulseaudio.

 WARNING:
---------
Currently this playbook is only used on Archlinux. It will probably require differen package names and maybe driver on other OS.

 Configuration
--------------
Have a look into the defaults Folder for some options.
Here are some defaults:
```yaml
# version check for this playbook
submodules_versioncheck: true

# Should we install bluetooth stuff?
install_bluetooth: true

# add additional packages to install
pulseaudio_arch_extra_packages: []
# - foo
# - bar

# warn if playbook is executed on different os than arch
warn_if_role_pulseaudio_is_not_tested_well: true
```
