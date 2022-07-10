## Description
A base Ubuntu machine with almost no initial conifiguration, that gets provisioned via Ansible with playbooks that comply with several benchmarks' security policies (including CIS).

Once the machine is provisioned, lynis registers that this machine jumps from an initial score of 52 (before provisioning) to a score of 82 (after updating the system and provisioning).

However, you should evaluate the hardening level your organization or environment requires and disable some of the 
recommendations if they are not compatible with your current infrastructure or policies. Take into account that some of the tasks that have developed might isolate your machine.