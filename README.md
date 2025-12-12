# Yet Another Filter Project
yafp is a filtering blocklist project compatible with [PiHole](https://pi-hole.net/) and [AdGuardHome](https://adguard.com/en/adguard-home/overview.html). This is a non-aggregated, manually updated and categorized blocklist. Contributions, corrections and classifying domains and subdomains are welcome. The goal of this project, although personal, is to provide a solid blocklist back to the community as well as fast commits and issue resolving.


[domains_junk](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_junk)
=  prevents:
some typosquatting,
reregistering of once legitimate domains,
short lived ad servers

[domains_malicious](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_malicious)
&&
[subdomains_malicious](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/subdomains_malicious)
=  prevents:
phishing,
command and control,
various types of scams,
fake shopping,
reregistering of known malicious domains.
Includes IOCs and IOFAs from various security threat reseach blogs and projects

[domains_ads](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_ads)
&&
[domains_clickadu](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_clickadu)
&&
[domains_exoclick](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_exoclick)
&&
[domains_webair](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_webair)
&&
[subdomains_ads](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/subdomains_ads)
=  prevents:
advertisements,
tracking,
analytics
