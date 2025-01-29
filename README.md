lxc config set core.https_address "[::]:8443"
lxc config set core.https_cert "$(cat lxd.crt)"
lxc config set core.https_key "$(cat lxd.key)"
