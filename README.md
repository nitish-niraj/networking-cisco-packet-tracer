<div align="center">
  <h1>🌐 CAP478 — Data Communication & Networking Laboratory</h1>
  <strong>Lovely Professional University</strong>
  <br /><br />
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=750&lines=Cisco+Packet+Tracer+Lab+Portfolio;Subnetting+%7C+Routing+%7C+Services;\"These+are+the+labs+that+I+have+done+during+my+course\"" alt="Animated headline" />
  <br />
  <img src="https://img.shields.io/badge/Labs-30%2B-38bdf8?style=for-the-badge" alt="Labs badge" />
  <img src="https://img.shields.io/badge/Tool-Cisco%20Packet%20Tracer-22c55e?style=for-the-badge&logo=cisco" alt="Packet Tracer badge" />
  <img src="https://img.shields.io/badge/Course-CAP478-6366f1?style=for-the-badge" alt="Course badge" />
</div>

---

## 🚀 Why this repo?
This is a colorful, learner-friendly launchpad for networking basics, routing, and services—built entirely in Cisco Packet Tracer. Every `.pkt` in the root is ready to open and explore.

## 🎯 Course Snapshot
- **University:** Lovely Professional University  
- **Course:** CAP478 — Data Communication and Networking Laboratory  
- **Goal:** A quick visual guide for juniors to study, tinker, and verify networking concepts.

### ✅ Course Outcomes
- CO1: Understand the fundamental concepts of data flow and criteria for transmission media selection.  
- CO2: Demonstrate IP allocation and subnet creation techniques.  
- CO3: Contrast static and dynamic routing protocols.  
- CO4: Assess application-layer services (HTTP, DNS, DHCP, SMTP, FTP) in real networks.

### 📚 Text Books & References
1. **CCNA 200-301 Official Cert Guide** — Wendell Odom (Pearson Education, Singapore)  
2. **Computer Networks** — Andrew S. Tanenbaum, David J. Wetherall (Pearson)

## 🧭 Learning Map (start anywhere, follow the glow)
**Networking basics**
- ✅ Demonstration of Packet Tracer installation and interface tour.  
- ✅ Design a peer-to-peer network; test with `ping`, send PDUs in Real-Time and Simulation modes.  
- ✅ Build two isolated networks to contrast hub vs switch behavior.  
- ✅ Create a hybrid topology (bus backbone + 3 stars); verify connectivity with `ping` and PDUs.

**Connectivity between networks & routing**
- ✅ Connect two networks using a single router and enable inter-network communication.  
- ✅ Link multiple networks (router per network) with **static routing**.  
- ✅ Repeat with **dynamic routing (RIP)** and observe convergence.  
- ✅ FLSM challenge: Subnet `197.34.21.0/24` so every subnet supports ≥56 hosts using static routes.

**Configuring network services**
- ✅ Configure an **HTTP server** and browse via IP in Real-Time and Simulation modes.  
- ✅ Configure **DNS** for two domains and reach both HTTP servers via names.  
- ✅ Configure **DHCP** and verify dynamic IP assignment in the local network.  
- ✅ Configure **DHCP** again (server-based) to watch live leases populate.

## 🎒 Lab Vault (click to expand)
<details>
<summary>🔌 Networking basics & topologies</summary>

- [hub.pkt](./hub.pkt) — Hub behavior and collisions  
- [startopologies.pkt](./startopologies.pkt) — Classic topologies starter  
- [mesh topologies.pkt](./mesh%20topologies.pkt) — Mesh redundancy  
- [Assing1.pkt](./Assing1.pkt), [Exercise.pkt](./Exercise.pkt) — Practice builds  
- [TOPOLOGY.pkt](./TOPOLOGY.pkt), [26.pkt](./26.pkt), [l1.pkt](./l1.pkt), [recoup.pkt](./recoup.pkt) — Class drills
</details>

<details>
<summary>🛰️ Routing & IP design</summary>

- [router.pkt](./router.pkt), [3 router.pkt](./3%20router.pkt), [routing1.pkt](./routing1.pkt)  
- Static: [static router.pkt](./static%20router.pkt), [static routing.pkt](./static%20routing.pkt), [STATIC & DYNAMIC ROUTER.pkt](./STATIC%20&%20DYNAMIC%20ROUTER.pkt)  
- Dynamic (RIP): [dynamic routing.pkt](./dynamic%20routing.pkt), [dynamic routing with 3 router.pkt](./dynamic%20routing%20with%203%20router.pkt), [2 hub dynamic routing.pkt](./2%20hub%20dynamic%20routing.pkt), [3 hub dynamic routing.pkt](./3%20hub%20dynamic%20routing.pkt)  
- Subnetting: [subnetting.pkt](./subnetting.pkt), [Subnetting_Solved.pkt](./Subnetting_Solved.pkt), [subnating.pkt](./subnating.pkt), [ip addressing class.pkt](./ip%20addressing%20class.pkt)
</details>

<details>
<summary>🛠️ Services (HTTP, DNS, DHCP, Email, FTP)</summary>

- Web: [http.pkt](./http.pkt), [http learning.pkt](./http%20learning.pkt), [http 2nd lec.pkt](./http%202nd%20lec.pkt)  
- DNS: [server and dns.pkt](./server%20and%20dns.pkt), [dnsp.pkt](./dnsp.pkt)  
- DHCP: [dhcp.pkt](./dhcp.pkt), [dhcp using server.pkt](./dhcp%20using%20server.pkt)  
- Email: [EMAIL.pkt](./EMAIL.pkt), [smtp.pkt](./smtp.pkt), [smptp_email.pkt](./smptp_email.pkt), [emailserver2.pkt](./emailserver2.pkt)  
- Combo: [EMAIL & FTP.pkt](./EMAIL%20&%20FTP.pkt), [ftp.pkt](./ftp.pkt)
</details>

<details>
<summary>🏁 Assessments & mixed scenarios</summary>

- [CA2.pkt](./CA2.pkt), [CA3DCN.pkt](./CA3DCN.pkt), [ca_2.pkt](./ca_2.pkt)  
- [cisco.pkt](./cisco.pkt), [static_test.pkt](./static_test.pkt) — quick checks
</details>

💡 Need a text-only index? See [LAB_INDEX.md](./LAB_INDEX.md) for short descriptions and verification tips.

## 🛠️ How to open and play
1. Install **Cisco Packet Tracer** (v8.x recommended).  
2. Clone the repo:
   ```bash
   git clone https://github.com/nitish-niraj/networking-cisco-packet-tracer.git
   ```
3. Double-click any `.pkt` file to launch it in Packet Tracer.  
4. Toggle **Real-Time** to watch live traffic or **Simulation** to step through PDUs.

## 🌈 Suggested path for juniors
1) Basics → `hub.pkt`, `startopologies.pkt`  
2) IP addressing → `subnetting.pkt`, `Subnetting_Solved.pkt`  
3) Static routing → `static routing.pkt`  
4) Dynamic routing (RIP) → `dynamic routing.pkt`  
5) Services → `http.pkt`, `dnsp.pkt`, `dhcp using server.pkt`, `EMAIL & FTP.pkt`  
6) Challenge → Try the FLSM subnetting task for `197.34.21.0/24` and verify with `ping`.

## 🧪 Quick verification commands
- On routers: `show ip interface brief`, `show ip route`, `debug ip rip` (for RIP labs).  
- On PCs: `ping <ip>`, `ipconfig /renew`, web browser for HTTP/DNS, FTP/Email clients for service labs.

## 👩‍💻 Author
Student — CAP478: Data Communication and Networking Laboratory (Lovely Professional University)

## 🪪 License
Educational use for CAP478 coursework at Lovely Professional University.

---

**Last Updated:** December 2025
