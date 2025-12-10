# Dynamic DNS Services
A curated list of free and paid Dynamic DNS (DDNS) providers. Useful for self-hosters, homelab users, small businesses, and anyone who needs to keep a stable hostname for a changing IP address.

This list includes API support, update mechanisms, and pricing models.

---

## Table of Contents
- [Free DDNS Providers](#free-ddns-providers)
- [Free & Paid (Freemium) Providers](#free--paid-freemium-providers)
- [Paid DDNS Providers](#paid-ddns-providers)
- [Self-Hosted / Open-Source Options](#self-hosted--open-source-options)

---

## Free DDNS Providers
Providers offering completely free plans.

### **DuckDNS** — https://www.duckdns.org  
**Model:** Free  
Simple and reliable, token-based updates, supports scripts, routers, and containers.

### **Dynu (Free Tier)** — https://www.dynu.com  
**Model:** Free  
Full-feature free tier, supports IPv4/IPv6, custom domains, TXT records, API.

### **Afraid.org (FreeDNS)** — https://freedns.afraid.org  
**Model:** Free  
Large community DNS pool, customizable subdomains, API support.

### **Securepoint DynDNS** — https://www.securepoint.de/en/free-dyndns  
**Model:** Free  
German provider, simple updates, multiple protocols.

---

## Free & Paid (Freemium) Providers
Services offering basic free plans + paid features or upgrades.

### **LockIP** — https://www.lockip.net  
**Model:** Free & Paid  
Clean DDNS interface with API keys, router compatibility, multiple domains, and premium reliability options. Ideal for homelabs and small business setups.

### **No-IP** — https://www.noip.com  
**Model:** Free & Paid  
One of the oldest DDNS providers. Free tier requires periodic confirmation; paid removes restrictions.

### **Dynu (Paid Tier)** — https://www.dynu.com  
**Model:** Free & Paid  
Enhanced reliability, more domains, email alerts, and advanced DNS features.

### **DuckDNS (Donations Only)** — https://www.duckdns.org  
**Model:** Free (donation supported)  
Fully free; users can optionally support via Patreon.

### **Cloudflare (API-based pseudo-DDNS)** — https://www.cloudflare.com  
**Model:** Free & Paid  
Not a traditional DDNS service, but DNS updates via API make it functionally equivalent. Popular with scripts and homelabs.

### **ClouDNS** — https://www.cloudns.net  
**Model:** Free & Paid  
Free tier allows some hostnames; paid adds more zones, monitoring, and DNSSEC.

### **Dynu (Wildcard & email upgrades)**  
Listed above under free, but also offers paid enhancements.

---

## Paid DDNS Providers

### **Dyn (Oracle Dyn DNS)** — https://dyn.com  
**Model:** Paid  
Longtime enterprise DDNS provider. Robust, but no longer free.

### **EasyDNS** — https://easydns.com  
**Model:** Paid  
Managed DNS with DDNS support, DNSSEC, monitoring, and SLA-backed uptime.

### **ChangeIP** — https://www.changeip.com  
**Model:** Paid  
DDNS plus broader DNS options; inexpensive low-tier plans.

### **DNS-O-Matic (OpenDNS/Cisco)** — https://dnsomatic.com  
**Model:** Free but forwarding-only  
Forwards updates to other DDNS services, but requires third-party provider.

---

## Self-Hosted / Open-Source Options
Host DDNS yourself or integrate into routers / homelabs.

### **DDclient** — https://github.com/ddclient/ddclient  
Updater client widely supported by routers, Linux distros, and providers.

### **inadyn** — https://github.com/troglobit/inadyn  
Lightweight, open-source DDNS client supporting many services.

### **PowerDNS + custom update endpoint** — https://www.powerdns.com  
Can be paired with a FastAPI or Nginx endpoint to create your own DDNS platform.

### **Bind + RNDC + update scripts**  
Traditional BIND DNS with custom dynamic updates.

### **nsupdate (RFC2136)**  
Native secure DNS updating mechanism.

---

## Contributing
Pull requests for additional DDNS services, corrections, or self-hosted options are welcome!
