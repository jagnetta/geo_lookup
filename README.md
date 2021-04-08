
Usage: ./geo_lookup <2 Letter Country Abbreviation>

This script will attempt to resolve NAPTR for Fuze's public GeoDNS domain by using a Public DNS Server in the chosen country.  
Enter a 2 letter country code (e.g., gb, de, au, etc.).  If at least 1 result for a Public DNS Server is found, then the command issued is:

	dig @SERVER NAPTR edge.uc.fuze.site +short +timeout=1

This script references Public DNS Server information from:	https://public-dns.info/#countries

The script uses the country code provided to find the IP addresses of public DNS servers in that country from the corresponding list found at the https://public-dns.info website.

