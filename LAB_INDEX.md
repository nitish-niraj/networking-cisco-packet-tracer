# LAB_INDEX — CAP478 Labs

This file is a curated index of Packet Tracer lab files included in the repository. Open each `.pkt` file with Cisco Packet Tracer.

- `hub.pkt` — Basic hub network demonstrating collisions and broadcast domains.
- `startopologies.pkt` — Examples of common topologies (star, bus, ring basics).
- `mesh topologies.pkt` — Mesh topology design and redundancy examples.
- `router.pkt` — Single router basic configuration and interface setup.
- `3 router.pkt` — Multi-router lab for inter-network connectivity.
- `static router.pkt` — Static routing configuration between networks.
- `static routing.pkt` — Additional static routing scenarios.
- `STATIC & DYNAMIC ROUTER.pkt` — Comparative lab showing static vs dynamic routing.
- `dynamic routing.pkt` — RIP dynamic routing configuration and verification.
- `dynamic routing with 3 router.pkt` — RIP across three routers demonstrating routing convergence.
- `subnetting.pkt` — Subnetting practice (FLSM) and host allocation examples.
- `Subnetting_Solved.pkt` — Solved subnetting exercises for reference.
- `subnating.pkt` — Additional subnetting exercises.
- `http.pkt` — HTTP server configuration and web access via IP.
- `http learning.pkt` — HTTP lab used in lectures/learning demonstrations.
- `http 2nd lec.pkt` — Follow-up HTTP lecture lab.
- `dns.pkt` — Basic DNS server setup and name resolution.
- `server and dns.pkt` — DNS with web servers demonstrating domain-based access.
- `dnsp.pkt` — Additional DNS practice lab.
- `dhcp.pkt` — DHCP server configuration for dynamic IP assignment.
- `dhcp using server.pkt` — DHCP configured with dedicated server appliance.
- `EMAIL.pkt` — Email server configuration and client testing.
- `EMAIL & FTP.pkt` — Combined email and FTP service lab.
- `emailserver2.pkt` — Alternate email server setup.
- `smtp.pkt` — SMTP-specific mail transfer lab.
- `smptp_email.pkt` — Another SMTP/email exercise (typo-preserved filename).
- `ftp.pkt` — FTP server configuration and file transfer tests.
- `CA2.pkt` — Continuous Assessment 2 lab scenario.
- `CA3DCN.pkt` — Continuous Assessment 3 (Data Communication & Networking).
- `Assing1.pkt` — Assignment 1 submission lab.
- `Exercise.pkt` — General practice exercises used in sessions.
- `2 hub dynamic routing.pkt`, `3 hub dynamic routing.pkt` — Hub-based topologies combined with dynamic routing exercises.
- `26.pkt`, `l1.pkt`, `recoup.pkt`, `ip addressing class.pkt`, `routing1.pkt`, `static_test.pkt`, `TOPOLOGY.pkt`, `ca_2.pkt`, `cisco.pkt` — Miscellaneous labs and class exercises (open to inspect contents).

Verification steps (quick checks)

These quick verification steps show how to validate the common labs after opening the `.pkt` in Packet Tracer.

- `hub.pkt`
	- Check: connect two hosts and generate traffic; observe collisions in Real-Time (hubs forward all frames).
	- Commands: use Simulation mode to view broadcast frames and collisions.

- `router.pkt`, `3 router.pkt`
	- Check: from a host in each network, `ping` the other network's host IP.
	- Commands on router: `show ip interface brief`, `show ip route`.

- `static router.pkt`, `static routing.pkt`, `STATIC & DYNAMIC ROUTER.pkt`
	- Check: configure static routes (if not pre-configured), then `ping` across networks and verify with `show ip route`.
	- Verify static routes persist in the routing table.

- `dynamic routing.pkt`, `dynamic routing with 3 router.pkt`
	- Check: ensure RIP is enabled; verify neighbors and learned routes with `show ip route` and `debug ip rip` in simulation.
	- Verify route convergence by shutting down an interface and observing route changes.

- `subnetting.pkt`, `Subnetting_Solved.pkt`, `subnating.pkt`
	- Check: verify host addressing matches the required subnet masks; `ping` between hosts in same subnet and across subnets (via router).
	- Commands: `show ip interface brief` to confirm IPs and masks.

- `dhcp.pkt`, `dhcp using server.pkt`
	- Check: set PC to DHCP, then `ipconfig /renew` (in Packet Tracer PC CLI) and confirm the assigned IP and gateway.
	- Verify DHCP pool using server configuration page.

- `dns.pkt`, `server and dns.pkt`, `dnsp.pkt`
	- Check: on a host, browse to the hostname configured for the HTTP server; DNS should resolve to server IP.
	- Verify DNS records on DNS server appliance.

- `http.pkt`, `http learning.pkt`, `http 2nd lec.pkt`
	- Check: open the web browser on a PC, navigate to server IP or configured hostname, and confirm page loads.

- `ftp.pkt`, `EMAIL.pkt`, `smtp.pkt`, `EMAIL & FTP.pkt`, `emailserver2.pkt`
	- Check FTP: use FTP client on a PC to connect to FTP server, list files and transfer a small file.
	- Check Email: configure client with mail server settings and send a test email between hosts; verify server logs.

- Misc labs (`CA2.pkt`, `CA3DCN.pkt`, `Assing1.pkt`, etc.)
	- Check: follow the lab instructions inside the file; common checks include ping tests, `show` commands on routers/switches, and service verification (HTTP/DHCP/DNS).
