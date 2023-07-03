partition disk: rootfs, [intermediate], data
install rootfs ubuntu LTS
configure apt sources to follow latest
update to latest: apt update && apt dist-upgrade && do-release-update && apt update && apt dist-upgrade
tweak alt-tab
tweak workspaces 3x3
tweak sudoers to keep env and to enable insults
configure EN-US and/or FR-CH
configure users: admin + parent and/or kid1,2
Also need a user with root access for ansible to run
configure hostname (zalug-<host>)
install git vim python mypy pylint libreoffice firefox
configure firefox: morning coffee, tree style tab, swiss transfer, no script
configure printer
configure wifi home+work
install LaTeX TeXlive
install ansible deploy lint
install nginx mysql/mariaDB php phpmd phpmyadmin
install Qt (recettes)
load mysql database (from where?)
clone config files (vash) and install (symlinks etc) + config username (local)
clone xonqnopp + config username (local) + configure nginx
clone nidji + config username (local) + configure nginx
clone recettes + config username (local)
clone flying + config username (local)
clone ansible + config username (local)
configure synology homeserver file server (with credentials)

Maybe find a way to setup a cron job and/or daemon to sync some files with home server when available automatically? Warning threats...
