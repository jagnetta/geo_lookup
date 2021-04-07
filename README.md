
This script will attempt to resolve NAPTR for Fuze's public GeoDNS domain by using a Public DNS Server in the chosen country.  Enter a 2 letter country code (e.g., gb, de, au, etc.).
The command issued is:
dig @SERVER NAPTR edge.uc.fuze.site +short

Usage: ./geo_lookup <2 Letter Country Abbreviation>.

This script references https://public-dns.info/#countries and the lists of DNS servers found on pages like https://public-dns.info/nameserver/gb.txt for example.  The script uses the country code provided to find the first IP address from such a list on the public-dns.info website.
