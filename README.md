# CVE-2023-3124
CVE-2023-3124 Proof of Concept

This is a proof of concept (PoC) exploit for CVE-2023-3124, a vulnerability in WordPress Elementor Pro plugin.

- Description:
The Elementor Pro plugin for WordPress is vulnerable to unauthorized data modification due to a missing capability check on the update_page_option function in versions up to, and including, 3.11.6. This makes it possible for authenticated attackers with subscriber-level capabilities to update arbitrary site options, which can lead to privilege escalation.

- Note:
This high-level overview is for educational purposes only. Understanding the vulnerability and its impact can help improve security practices and develop effective defenses against similar attacks.
