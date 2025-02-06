This script is created for common issue with Pterodactyl and Docker for most gameservers... so we created this script to fix and provide solution for community

Solution to this problem: https://github.com/pterodactyl/panel/issues/459
Reference to iptables NAT tutorial: https://www.karlrupp.net/en/computer/nat_tutorial

ip-mapper-nft.sh — Maps container IPs to public IPs set in their environment from the panel.

Examples:
   sh ip-mapper.sh
   sh ip-mapper.sh --list <all | uuid>
   sh ip-mapper.sh --remove <all | uuid>

Options:
   --list <all | UUID>      Lists active rules added by the script.
   --remove <all | UUID>    Removes rules added by the script.
   --help                   Shows this message.
