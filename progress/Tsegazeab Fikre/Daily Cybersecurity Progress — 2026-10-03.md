# 📅 2026-10-03 — Tsegazeab Fikre

**Roadmap Track:** Web Security

## ✅ What I Did Today

- Continued working on the **INSA mentor-assigned project tasks** using the vulnerable crAPI application.
- Performed black-box testing of the crAPI web application and discovered an **IDOR (Insecure Direct Object Reference)** vulnerability.
- Identified the API endpoint responsible for accessing order information and confirmed that manipulating the referenced ID could expose **another user's order history**.
- Investigated the vulnerability from an API security perspective to understand how improper authorization controls can lead to unauthorized access to other users' data.
- Continued practicing **Cross-Site Scripting (XSS)** through PortSwigger Web Security Academy labs after learning XSS concepts on another platform.
- Continued working toward my goal of reaching **50% progress on PortSwigger Web Security Academy**.

## 📚 What I Learned

- **IDOR / Broken Access Control:** Learned how applications can expose other users' resources when API endpoints fail to properly verify whether the authenticated user is authorized to access the requested object.
- **API Security:** Improved my understanding of how vulnerabilities can exist directly within API endpoints even when the web application's normal functionality appears to enforce access controls.
- **Vulnerability Verification:** Learned the importance of confirming the actual security impact of a suspected vulnerability rather than stopping after identifying an unusual response.
- **XSS:** Continued strengthening my understanding of different XSS scenarios through hands-on PortSwigger labs.
- **Practical Pentesting:** Improved my ability to move from discovering an endpoint to testing how its parameters affect authorization and data access.
- **Continuous Learning:** Reinforced the importance of practicing the same vulnerability class across different platforms and applications to build stronger practical understanding.

## 🚧 Blockers

- Some of the crAPI testing required additional investigation to understand the API behavior and determine whether the observed access was actually unauthorized.
- Balancing the INSA project assignment with PortSwigger practice required managing time between project work and individual learning goals.

## 🎯 Plan for Tomorrow

- Continue working on the **INSA-assigned crAPI security testing tasks**.
- Investigate additional API security vulnerabilities and access-control issues.
- Continue solving **PortSwigger XSS labs** to strengthen practical XSS skills.
- Continue working toward the goal of reaching **50% PortSwigger progress**.
- Improve my ability to document discovered vulnerabilities clearly and professionally.

## 🔥 Daily Reflection

> Today, I gained more practical experience in API security by discovering and validating an IDOR vulnerability in crAPI that allowed access to another user's order history. At the same time, I continued practicing XSS through PortSwigger labs to strengthen what I have already learned. Working on both the INSA project and PortSwigger is helping me connect theoretical knowledge with real hands-on penetration testing experience.