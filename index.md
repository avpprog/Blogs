---
layout: default
title: Home
---

# Hi, I'm Aditya Patil 👋

I'm a cybersecurity enthusiast focused on **penetration testing / network security / SOC**.

## What I Write About
- **Linux & CLI** for security work
- **CTF write-ups** (TryHackMe, HackTheBox)
- **Home lab** experiments
- **Recent vulnerabilities** explained simply

---

## Recent Posts
{% for post in site.posts limit:5 %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%b %d, %Y" }}
{% endfor %}

---

## Connect
- [GitHub](https://github.com/avpprog)
- [LinkedIn](https://linkedin.com/in/your-profile)
- [TryHackMe Profile](https://tryhackme.com/p/your-username)
