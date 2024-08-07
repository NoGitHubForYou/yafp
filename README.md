# Yet Another Filter Project
yafp is a filtering blocklist project compatible with [PiHole](https://pi-hole.net/) and [AdGuardHome](https://adguard.com/en/adguard-home/overview.html). This is a non-aggregated, manually updated and categorized blocklist. Contributions, corrections and classifying domains and subdomains are welcome. The goal of this project, although personal, is to provide a solid blocklist back to the community as well as fast commits and issue resolving.

# Upcoming changes...

POSTED: 08/06/24

Domains listed in files [domains_free_hosting](https://github.com/NoGitHubForYou/yafp/blob/main/domains_free_hosting) and [domains_dynamic_dns](https://github.com/NoGitHubForYou/yafp/blob/main/domains_dynamic_dns) will no longer have their subdomains listed in the file [subdomains_malicious](https://github.com/NoGitHubForYou/yafp/blob/main/subdomains_malicious). These are frequently abused services by malicious actors, too many subdomains to track and list and I personally don't know many legitimate website that would use these services. It's recommended to block <ins>domains_free_hosting</ins> and <ins>domains_dynamic_dns</ins> if you're also blocking [domains_malicious](https://github.com/NoGitHubForYou/yafp/blob/main/domains_malicious)

RESOLVED: N/A
