# Description
This folder contains all necessary files to get running a hardened Windows 10 Education machine.
The base Windows 10 Education machine gets provisioned via ansible with CIS-compliant playbooks that improve the security of said machine.

Because of how the synced folder is configured for the 'controller' node, the necessary Ansible roles will be copied to the provisioning folder directly from the provisioners directory present at the root of the project. This has been done like this to prevent having to manually copy the necessary Ansible roles and have them duplicated and potentially outdated. If you wish to just work with the windows_hardened subproject and copy it elsewhere, bear in mind you'll need to change the appropriate paths and location of Ansible roles.

# Additional software included
The machine has CLARA already available to be able to test the system's compliance.