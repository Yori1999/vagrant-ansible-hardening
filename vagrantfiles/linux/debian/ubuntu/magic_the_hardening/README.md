## Description
This machine is a modification of the original 'Magic The Hardening' machine that you can find here: https://github.com/jose-r-lopez/SSI_Infraestructure_Automation_Materials. The author has kindly allowed to test our Ansible hardening CIS roles that comply with CIS policies on this already hardened machine.

The "base" machine (only provisioned with the original customization and hardening scripts) achieves with a lynis analysis a score of 89. After provisioning the machine with the Ansible CIS-compliant roles, the lynis score of the machine gets to 92.