# Deploy DreamFactory via Ansible

This is the first draft a DreamFactory Ansible playbook. It assumes the following:

1. You are using Ubuntu 16.04+
2. Your target username is vagrant (you can change this)
3. You have setup your Ansible hosts file
4. You have added your public key to the authorized keys file on the target(s)
5. You will insert your own github token

This version uses sqlite for the system database and only has a handful of drivers. More changes to come.
