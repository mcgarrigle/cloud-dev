# Deploy and configure a development VM in seconds

* Based on Rocky Linux cloud image
* Configured with avahi to advertise VM address via mDNS
* Installs and launches cockpit
* Contains useful utiliies and dev tools
* Configures my preferred set of bash tweaks

## Deployment:

Using https://github.com/mcgarrigle/cloud
```
cloud up
```
... or Whatever tooling iyou use for VM provision, for Terraform see here https://github.com/mcgarrigle/terraform-libvirt
```
vi inventory.yml
ansible-playbook -i inventory.yml site.yml
```
