# 🚫 Adult Content Domain Filter — Family Protection Tool [Educational] 2026

![Downloads](https://img.shields.io/badge/Downloads-77K+-blue?style=for-the-badge&logo=github)
![User Rating](https://img.shields.io/badge/User%20Rating-4.6/5-gold?style=for-the-badge&logo=star)
![Latest Version](https://img.shields.io/badge/Latest%20Version-2.5.0-green?style=for-the-badge&logo=github)
![Platform](https://img.shields.io/badge/Supported-All%20Platforms%20%7C%20Pi--hole%20%7C%20DNS-informational?style=for-the-badge&logo=pihole)

The **🚫 Adult Content Domain Filter** is a **free** domain blocklist that protects families from explicit adult content with **zero cost**. No payment required. This comprehensive filter aggregates thousands of pornographic domains into a single, automatically updated blocklist — perfect for Pi-hole, DNS filters, and parental control systems. Updated daily to catch new adult websites.

<div align="center">

[![Download Adult Content Domain Filter](https://img.shields.io/badge/Download-purple?style=for-the-badge&logo=github)](https://github.com/Bon-Appetit/porn-domains)

</div>

<div align="center">
<img width="1200" height="600" alt="PORN-og" src="https://github.com/user-attachments/assets/cc2665f9-cb89-48c7-808b-da4a3f7bd695" />

</div>

---

## 🚫 The Purpose

Protecting children and families from accidental exposure to explicit content is essential. This free blocklist aggregates thousands of adult domains into one comprehensive, automatically updated list. Instead of building from scratch, it combines the excellent work of multiple sources — giving you complete protection with zero cost.

---

## 💡 Key Capabilities

**Adult Content Domain Filter** provides complete protection against explicit websites for free.

- ✅ **Comprehensive blocklist** — thousands of pornographic domains
- ✅ **Auto-updated daily** — catches new adult websites automatically
- ✅ **Pi-hole compatible** — works with any DNS filter
- ✅ **Free protection** — zero cost, no payment, no subscription
- ✅ **Family-friendly** — create a safe browsing environment
- ✅ **Open source** — transparent and community-maintained

---

## ⚙️ Features

### 🚫 Blocklist Features

| Feature | Description |
|---------|-------------|
| **📋 Adult Domains** | Thousands of pornographic websites blocked |
| **🔄 Auto-Update** | New domains added daily (see April 20, 2026 update) |
| **🧹 Deduplicated** | Clean, redundant-free list |
| **✅ Allowlist** | Domains incorrectly flagged (false positives) |
| **🔍 Live Search** | Search interface to check specific domains |
| **📊 Meta.json** | Automated fetching URLs (no hardcoded links) |

### 🛠️ Compatibility

| Platform | Support |
|----------|---------|
| **🔵 Pi-hole** | ✅ Full compatibility |
| **🌐 DNS Filter** | ✅ Works with any DNS blocker |
| **🖥️ Hosts File** | ✅ Can be converted to hosts format |
| **🛡️ Firewall** | ✅ Domain-based blocking |
| **📱 Family DNS** | ✅ Works with OpenDNS, Cloudflare Gateway |

### 📦 Included Resources

| File | Purpose |
|------|---------|
| **📄 block.HASH.txt** | Main blocklist (deduplicated + cleaned) |
| **✅ allow.HASH.txt** | Allowlist for false positives |
| **📁 meta.json** | Current filenames for automated fetching |
| **📋 CSV files** | Source data for transparency |

---

## 📊 Feature Overview

| Feature | Basic DNS | Adult Content Domain Filter |
|---------|-----------|----------------------------|
| **Adult Domain Coverage** | Limited | ✅ Comprehensive (thousands) |
| **Auto-Update** | Manual | ✅ Daily automatic |
| **False Positive Handling** | None | ✅ Built-in allowlist |
| **Pi-hole Compatible** | Varies | ✅ Yes |
| **Cost** | Free (but incomplete) | ✅ Zero cost (complete) |

---

## 🛠️ Installation Guide

### Pi-hole Installation (Recommended)

1. **🚫 Access** your Pi-hole admin panel
2. **📋 Go to** Group Management → Adlists
3. **➕ Add** the following blocklist URL:
   ```
   https://raw.githubusercontent.com/Bon-Appetit/porn-domains/main/block.HASH.txt
   ```
   *(Get the latest HASH from meta.json)*
4. **🔄 Update** Gravity (Tools → Update Gravity)
5. **✅ Done** — Adult content is now blocked

### Manual DNS Filter Installation

1. **📥 Download** the blocklist from GitHub
2. **📂 Import** into your DNS filter (AdGuard, NextDNS, etc.)
3. **⚙️ Configure** to block all listed domains
4. **✅ Enable** automatic updates (daily recommended)

### Hosts File Installation (Windows/Linux/macOS)

1. **📥 Download** the blocklist
2. **📝 Convert** domains to hosts format (or use provided format)
3. **📂 Append** to `/etc/hosts` (Linux/macOS) or `C:\Windows\System32\drivers\etc\hosts` (Windows)
4. **💾 Save** and flush DNS cache

[![Download Adult Content Domain Filter](https://img.shields.io/badge/Download-purple?style=for-the-badge&logo=github)](https://github.com/Bon-Appetit/porn-domains)

### Live Domain Search

1. Go to the search interface: https://bon-appetit.github.io/domain-search/
2. Enter any domain to check if it's in the blocklist
3. See if it's blocked or allowed

### Reporting False Positives

1. Check if domain is incorrectly flagged
2. Submit to allowlist via GitHub issues
3. Domain will be removed in next update

---

## 📥 System Requirements

| Component | Minimum |
|-----------|---------|
| **Platform** | Pi-hole, DNS filter, hosts file, any OS |
| **Storage** | ~5 MB for blocklist |
| **Memory** | Depends on DNS software |
| **Internet** | Required for updates |
| **Update Frequency** | Daily recommended |

---

## 💡 Usage Tips

- **Set up auto-update** — daily updates catch new adult sites
- **Check allowlist** — review false positives periodically
- **Use live search** — verify domains before reporting
- **Combine with other filters** — add malware and tracking lists
- **Monitor logs** — see which domains are being blocked

---

## ❓ Frequently Asked Questions

**Q: Is this really free?**  
A: Yes — completely free. Zero cost. No payment. Open source. Donations are welcome but not required.

**Q: What is this list?**  
A: A comprehensive collection of domains used for explicit adult content like porn websites. Automatically updated daily.

**Q: How accurate is it?**  
A: Very accurate, but false positives can happen. The project includes an allowlist for incorrectly flagged domains.

**Q: Does it work with Pi-hole?**  
A: Yes — it's fully compatible with Pi-hole and other DNS filters.

**Q: How often is it updated?**  
A: Daily — the latest update was April 20, 2026 (see GitHub commit history).

**Q: Can I use this commercially?**  
A: Yes — but if you use it in a commercial product, please consider donating to support the project.

**Q: What is the license?**  
A: CC BY-SA 4.0 — you must credit the project if you share or use the list.

**Q: Is it legal?**  
A: Yes — it's a blocklist for filtering content. Local laws vary; you're responsible for compliance.

**Q: Who maintains this?**  
A: Bon-Appetit on GitHub, with contributions from the community (6 contributors, 2,476+ commits).

**Q: How many domains are blocked?**  
A: Thousands — the list is too large to view directly on GitHub. Use the live search interface.

**Q: Can I contribute?**  
A: Yes — see the Contributing section on GitHub to add or remove domains.

**Q: What if a domain is incorrectly blocked?**  
A: Submit it to the allowlist via GitHub issues. The maintainers will review and remove it.

---

## ☑️ Guidelines

- ☑️ For family protection and educational use
- ☑️ Combine with other safety measures
- ☑️ Review false positives regularly
- ☑️ Respect local laws and regulations
- ☑️ Donate if using commercially

---

## 📚 Resources

| Page | Description |
|------|-------------|
| **📋 Changelog** | Latest updates and changes |
| **📜 Policy** | Domain inclusion/exclusion criteria |
| **🤝 Contributing** | How to add or remove domains |
| **👥 Contributors** | Everyone who helped |
| **💝 Sponsors** | Project supporters |
| **🆘 Support** | Help and contact options |

---

## 🏁 Summary

Protect your family from adult content for free. **Adult Content Domain Filter** provides a comprehensive, auto-updated blocklist of thousands of pornographic domains with zero cost. No payment. No subscription. Just install, update, and browse safely.

**One list. Complete protection. Zero cost.**

---

<div align="center">

[![Download Adult Content Domain Filter](https://img.shields.io/badge/Download-purple?style=for-the-badge&logo=github)](https://github.com/Bon-Appetit/porn-domains)

**Version 2.5.0** — Family protection tool. Updated daily. Zero cost. No payment.

</div>
