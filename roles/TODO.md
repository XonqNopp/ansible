??? partition disk: rootfs, [intermediate], data + tmpfs
install rootfs ubuntu (LTS?)
??? configure apt sources to follow latest
do-release-update
tweak alt-tab
tweak workspaces 3x3
tweak sudoers to keep env and to enable insults
configure EN-US and/or FR-CH
configure users: admin + parent and/or kid1,2
Also need a user with root access for ansible to run
Configure ssh hosts/config ansible.builtin.known_hosts
configure hostname (zalug-<host>) ansible.builtint.hostname
configure firefox (one role for each): morning coffee, tree style tab, no script
configure printer
configure wifi homes x2 (abricots) + work x2
install LaTeX TeXlive ansible.builtin.script/shell/command
install ansible deploy lint (cross-check package names)
ansible.builtin.git remote=upstream
clone config files (vash) and install (symlinks ansible.builtin.file) + config username (local) + config github token
nginx config: ansible.builtin.service name state=started/stopped/restarted/reloaded enable=true/false (for boot) or ansible.builtin.systemd?
clone xonqnopp + config username (local) + configure nginx + config github token + MySQL database
clone nidji + config username (local) + configure nginx + config github token + MySQL database
clone recettes + config username (local) + config github token + install Qt
clone flying + config username (local) + config github token
clone ansible + config username (local) + config github token
configure synology homeserver file server (with credentials)

Maybe find a way to setup a cron job and/or daemon to sync some files with home server when available automatically? Warning threats...


Abricotier: abricotier-<username>
User
HIN
Firefox
Office
Mail
Calendar
Media
Wifi
Printer
Thunderbird (mail client) + launch at startup
