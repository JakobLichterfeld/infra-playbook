# infra-playbook

Infrastructure as Code (IaC)

After using a shell script to automate my desktop Ubuntu installation from 2011 to 2023, I finally migrated the 2646 lines of code to Ansible. Thanks to [notthebee](https://github.com/notthebee/) for the final push.

During the migration process, I have released the subsequent roles as individual Ansible roles:

| Name           | Description                        |
| -------------- | -----------------------------------|
| [ansible-role-amok_exifsorter](https://github.com/JakobLichterfeld/ansible-role-amok_exifsorter) | An Ansible role to install Amok Exifsorter via download |
| [ansible-role-android_studio](https://github.com/JakobLichterfeld/ansible-role-android_studio) | An Ansible role to install Android Studio via download |
| [ansible-role-calibre](https://github.com/JakobLichterfeld/ansible-role-calibre) | An Ansible role to install Calibre via Binary Installer Download. |
| [ansible-role-latex_texlive](https://github.com/JakobLichterfeld/ansible-role-latex_texlive) | An Ansible role to install LaTeX TeX Live via DVD download |
| [ansible-role-remarkable_templates_and_splashscreen](https://github.com/JakobLichterfeld/ansible-role-remarkable_templates_and_splashscreen) | An Ansible role to change Remarkable Splash Screen and import own templates. |
| [ansible-role-sony_gps_assist_data](https://github.com/JakobLichterfeld/ansible-role-sony_gps_assist_data) | An Ansible role to install Sony-GPS-Assist-Data Script via git checkout. |
| [ansible-role-winehq](https://github.com/JakobLichterfeld/ansible-role-winehq) | An Ansible role to install WineHQ via repository. |

Migration of my shell scripts for automating my Raspberry Pi installations will follow.

## Requirements

It assumes a fresh Ubuntu 22.04 install, access to a non-root user with sudo privileges and a public SSH key.

## Contributing

All contributions are welcome and greatly appreciated!

## Disclaimer

The Playbook is primarily designed for personal use, so it is subject to frequent modifications and glitches. Use it at your own risk and do not anticipate guidance for its installation on your device.