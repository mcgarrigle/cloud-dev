Deploy and configure a development VM in seconds

* Based on Rocky Linux cloud image
* Configured with avahi to advertise VM address via mDNS
* Installs and launches cockpit
* Contains useful utiliies and dev tools
* Configures my preferred set of bash tweaks

Deployment:
```
cloud up   # using https://github.com/mcgarrigle/cloud
```
... or Whatever tooling for VM provision, for Terraform see here https://github.com/mcgarrigle/terraform-libvirt
```
vi inventory.yml
ansible-playbook -i inventory.yml site.yml
```
