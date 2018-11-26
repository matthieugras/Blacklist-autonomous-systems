# Blacklist-autonomous-systems
IP-Tables script to blacklist some autonomous systems

# Install
Extract anywhere and run make, defaults to `/usr/local/bin`.
Then run: `blacklist-as -u`
to create the configuration and then:
`blacklist-as -i`
to install the service that loads the configuration at boot time.

# Uninstall
run: `blacklist-as -c `
then remove the remaining files in `/usr/local/bin`

# Configuration
By default all incoming connections are blocked, autonomous systems that should completely be blocked can be configured in `/usr/local/bin/as_blacklist.conf`
