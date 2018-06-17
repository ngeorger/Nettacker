OWASP Nettacker Transforms
=======================
This folder mainly contains the source code for the `canari` package for the Nettacker. All
the commands of the canari framework to generate the profile or the mtz file will have to be run from
here.
* `nettacker_transforms/` - This contains the main code for the transforms
* `__init__.py` - This is the module instantiation file for this folder
* `canari.conf` - This is the configuration file for `canari`. This is not to be disturbed.
* `nettacker_transforms.conf` - This is the configuration file for the nettacker transforms.
Please mention your home-directory for the OWASP-Nettacker main folder here. For eg:
`home-directory = /home/wizard/OWASP-Nettacker/`
* `nettacker_transforms.mtz` - This is the maltego transform file that will be imported into the
maltego framework. You can generate this using command :
``` canari create-profile nettacker_transforms -w ~/OWASP-Nettacker/lib/transactions/maltego/nettacker_transforms/src```
* `.mrbob.ini` - This is generated by framework on its own