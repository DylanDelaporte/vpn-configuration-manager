# vpn-configuration-manager

Generate server and client ovpn configuration files.

## How to

- Clone project `git clone https://github.com/DylanDelaporte/vpn-configuration-manager.git`
- Update `vpn-configuration-create` script with your parameters (certificate information and client remote)
- Set execution rights `chmod +x vpn-configuration-create` (no need root login)
- Create your server configuration `./vpn-configuration-create <name> --server` and client configuration `./vpn-configuration-create <name> --client` a folder with the same name will contain all generated files
