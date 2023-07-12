# Ansible roles for my personal computer

See also https://github.com/13pgeiser/ansible_debian
and 
https://github.com/13pgeiser/debian_stable_preseed



## Notes on ansible.builtin

script is better than command which is better than shell which is better than raw.
But script only executes a local script (upload then execute).
So:

* Use script if we can make a script file with all the instructions
* Use command if we just want to run a command without creating a dedicated file
* Use shell if we want to do some fancy stuff like piping or redirecting the output

Better than script is to make ansible module. How???
