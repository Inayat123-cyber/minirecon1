# minirecon1
# 🛰️ MinRecon – Minimal Recon Tool for Bug Bounty Hunters

**MinRecon** is a super-lightweight, Bash-based reconnaissance tool built for ethical hackers, penetration testers, and bug bounty hunters working with limited resources. Created by **Inayat Hussain**, this script is optimized for systems with as little as 4GB RAM, such as low-end laptops or virtual machines.

---

## 🎯 Why MinRecon?

In modern bug bounty workflows, recon is the foundation. But not everyone has access to high-end machines or powerful VPS setups. **MinRecon** was designed for:

- ✨ Beginners starting recon with basic hardware
- 💻 Low-resource environments (bare metal, VMs, Replit)
- 🔄 Quick one-shot recon tasks

---

## 🚀 Features

- 🧭 Domain input and one-click recon
- 🔍 Subdomain enumeration
- 🌐 HTTP probing (check live hosts)
- 🛡️ Port scanning (optional)
- 💡 Highly optimized for speed and size
- 🧠 Beginner-friendly and fully modular

---

## 📦 Requirements

MinRecon is written in pure Bash and uses a few essential CLI tools:
- `curl`
- `dig`
- `ping`
- `whois`
- `nslookup`
- `host`
- `nmap` (optional)
> 📌 All tools come pre-installed in most Parrot OS/Kali/Ubuntu distros.

---

## 🔧 Installation

```bash
chmod +x minrecon.sh
./minrecon.sh

🖥️ How to Use

    Run the script:

./minrecon.sh

Enter your target domain (e.g. example.com)

Let the script perform:

    DNS information lookup

    Subdomain gathering (basic)

    Live host detection

    Whois and IP info

    Optional nmap scan

Results will be printed in terminal and saved in:

    results/domain-name-YYYY-MM-DD.txt

📷 Screenshot (Example Output)

Target: example.com
IP Address: 93.184.216.34
Subdomains Found: www, mail, admin
Open Ports: 80, 443
Live: Yes

👤 Author

Built with care by Inayat Hussain (Inayat Raj Chohan)

    🔗 LinkedIn

    🧠 Facebook: Inayat Raj Chohan

    🐙 GitHub: https://github.com/your-github-username

⚠️ Disclaimer

This tool is for educational and authorized penetration testing only. Use responsibly and only on assets you have permission to test.
🌟 Support

If you find this tool helpful, please star the repo and share with fellow hackers. Every bit of encouragement helps in my journey as a self-taught cybersecurity professional with limited resources.


---

## 🔸 GitHub Short Description
When creating the repo, use this in the "Description" field:

> Lightweight domain recon tool for ethical hackers and bug bounty hunters with low-end set
