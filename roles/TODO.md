# Prio high

playbook to do updates. But need ssh through network... Or gateway (RPi)?

tweak sudoers to keep env and to enable insults
configure EN-US and/or FR-CH
configure users: admin + parent and/or kid1,2 - disable default (if any) BUT be careful not to block ansible access - also generate ssh keys if needed
Configure ssh hosts/config ansible.builtin.known_hosts - also do ssh-copy-id
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
desktop backgrounds
parental control
configure printer


Abricotier: abricotier-<username>
User
HIN
Firefox
Office
Mail
Calendar (thunderbird?), synced with cabinet
Media VLC
Wifi
Printer
Thunderbird (mail client) + launch at startup


### Phones

Android+ansible?????

update
configure google account
install apps:
- whatsapp, configure???
- threema, configure???
- maps.me, configure???
- google maps, configure???
- cff, configure???
- gmail, configure???
- firefox, possible to configure links?
- instagram, configure???
- rts info
- youtube, configure???
- anylist, configure???
- resair, configure???
- gps tracker
- suissemobile, configure???
- ds file, configure???
- ds finder, configure???
- ds audio, configure???
- ds photos, configure???
- twint raiffeisen+ubs, configure???
- raiffeisen photo tan
- raiffeisen mobile scan
- UBS access, configure???
- danstonchat
- klapp, configure???
- freesurf cff, configure???
- anibis, configure???
- rega, configure???
- rettemi.ch, configure???
- local.ch, configure???
- alertswiss, configure???
- google traduction
- groupe mutuel, configure???
- meteoswiss, configure???
- mobility, configure???
- planets
- plant.net
- postcard creator, configure???
- publibike???
- qoqa, configure???
- reka, configure???
- splash, configure???
- swisstopo???
- x/twitter, configure???
configure apps only with wifi (disable mobile data)
configure wifi networks (same as computers)
parental control



# Prio low

Low should not be started before we have a usable solution

??? partition disk: rootfs, [intermediate], data + tmpfs
install rootfs ubuntu (LTS?)
Also need a user with root access for ansible to run
??? configure apt sources to follow latest
do-release-update
tweak alt-tab
tweak workspaces 3x3
Maybe find a way to setup a cron job and/or daemon to sync some files with home server when available automatically? Warning threats...
