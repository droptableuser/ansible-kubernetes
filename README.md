# ansible-kubernetes

This repository provides ansible scripts for my walkthrough of [kubernetes-the-hardway](//github.com/droptableuser/kubernetes-the-hard-way) 

## Copyright

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

## Target Audience
This repository is for people who would like to see how someone would bootstrap a kuberentes cluster, with minimal automation.

## Prerequistes

### Ansible

* Ansible 7.2.0
* SSH-Keys for a user with administrative rights (sudo) deployed onto all SBCs. Repeat for every SBC you have: ``` ssh-copy-id user@bpi ```
