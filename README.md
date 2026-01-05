# Yet Another Filter Project
yafp is a filtering blocklist project compatible with [PiHole](https://pi-hole.net/) and [AdGuardHome](https://adguard.com/en/adguard-home/overview.html). This is a non-aggregated, manually updated and categorized blocklist. Contributions, corrections and classifying domains and subdomains are welcome. The goal of this project, although personal, is to provide a solid blocklist back to the community as well as fast commits and issue resolving.


[domains_junk](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_junk)
=  prevents:
reregistering of once legitimate domains,
short lived ad servers,
dead entries to prevent reregistering

[domains_malicious](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_malicious)
&&
[subdomains_malicious](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/subdomains_malicious)
=  prevents:
phishing,
command and control,
various types of scams,
fake shopping,
reregistering of known malicious domains.
Includes IOCs, IOAs and IOFAs from various security threat reseach blogs and projects

[domains_ads](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_ads)
&&
[domains_clickadu](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_clickadu)
&&
[domains_akis2net](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_akis2net)
&&
[domains_ab1nnet](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_ab1nnet)
&&
[subdomains_ads](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/subdomains_ads)
=  prevents:
advertisements,
tracking,
analytics

[domains_dns](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_dns)
&&
[subdomains_dns](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/subdomains_dns)
=  prevents:
encrypted dns resolution,
canary domains

[domains_adult](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_adult)
=  prevents:
dating,
porn,
escorts,
games,
ai,
live streams


[domains_adshield](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_adshield)
&&
[domains_admiral](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_admiral)
&&
[domains_antiad](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_antiad)
&&
[subdomains_adshield](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/subdomains_adshield)
=  prevents:
domains that use these anti-ad domains and the anti-ad domains themselves

[subdomains_revocation](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/subdomains_revocation)
=  prevents:
privacy concerns when using OCSP (Online Certificate Status Protocol) and CRL (Certificate Revocation List)

[domains_typos](https://raw.githubusercontent.com/NoGitHubForYou/yafp/refs/heads/main/domains_typos)
=  prevents:
typosquatting,
misspellings by users,
misspellings by developers
