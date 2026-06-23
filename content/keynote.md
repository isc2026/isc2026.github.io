+++
title = 'Keynotes'
date = 2026-06-23
menu = 'main'
weight = 6
+++

### Title: LINE-Break: Cryptanalysis and Reverse Engineering of Letter Sealing

**Speaker**: [Diego F. Aranha](https://dfaranha.github.io/) (Aarhus University)
{{< figure src="/img/diego_f_arannha.jpg" class="left" width="200">}}

**Date**: October 29, 2026 \
**Abstract**: We present a security analysis of the messaging service known as LINE, a popular platform used daily by millions of users in East Asia.
More specifically, we focus on its underlying custom end-to-end-encryption (E2EE) protocol known as Letter Sealing v2, which we evaluate with respect to modern E2EE security guarantees.
Our findings show that Letter Sealing design and implementation allow a TLS Machine-in-the-Middle (MITM) attacker or malicious server to violate integrity, authenticity and confidentiality of communications.
We experimentally verified our attacks against the authentic LINE application using an MITM attack on an iOS device.
We discuss our findings in comparison to the state-of-the-art E2EE protocol Signal, and conclude that Letter Sealing does not satisfy the requirements expected from a modern E2EE messaging protocol.
This is joint work with Adam Blatchley Hansen and Thomas Kingo Mogensen, with material available at [https://www.linebreak.info](https://www.linebreak.info)

**Biography**: Diego F. Aranha is an Associate Professor of Computer Science at Aarhus University, Denmark.
He holds a Ph.D. from the University of Campinas and collects faculty experience across three universities.
His work sits at the intersection of Cryptography and Computer Security, with a particular focus on the efficient implementation of cryptographic algorithms and the security analysis of real-world systems.
He has been lucky to receive the Google Latin America Research Award for privacy twice, the MIT TechReview's Innovators Under 35 Brazil Award for work in electronic voting, the IACR Test-of-Time Award for work in pairing-based cryptography.



---

### Title: From Smartphones to Cloud: Trustworthy Foundations for Digital Sovereignty

**Speaker**: [Shweta Shinde](https://www.shwetashinde.org/) (ETH Zurich)

{{< figure src="/img/shweta-shinde.jpg" class="left" width="200">}}

**Date**: October 28, 2026 \
**Abstract**:
As computing moves increasingly to the cloud and AI-powered services, a fundamental question emerges: who truly controls our data and computation?
Today's systems force users to trust phone operating system vendors and cloud providers i.e., entities whose interests often conflict with user privacy and security.
In this talk, I will present how to build systems that enable trustworthy sovereignty, where users can verify who controls their computation rather than blindly trusting cloud operators and management software.

I will demonstrate this vision by exposing and addressing trust failures across three critical architectural layers of modern computing.
First, with Sovereign Smartphone, I will show how we enable users to reclaim control of their smartphones for running security-critical applications like encrypted messaging and password managers in isolation from both the operating system and manufacturer backdoors.
Second, building Sovereign Smartphone revealed a deeper problem: Ahoi attacks, a new class of interrupt-based vulnerabilities that break the security guarantees of all major CPU-based trusted execution environments by exploiting fundamental assumptions about how processors handle hardware interrupts.
Finally, I will expose an emerging attack surface in processors and accelerators used in the cloud, where we exploit interconnects to completely bypass security, and how to detect and patch such vulnerabilities.

We will conclude with practical paths toward building systems where trust is verified rather than assumed, enabling genuine digital sovereignty for individuals, organizations, and nations.

**Biography**:
Shweta Shinde is a tenure-track Assistant Professor in the Department of Computer Science at ETH Zürich, where she leads the Secure & Trustworthy Systems (SECTRS) group.
Her research focuses on building fundamentally secure large-scale systems.
She has a track record of uncovering real-world vulnerabilities in confidential computing environments,  based on insights that emerge from the understanding gained through her work to secure them.
Her defensive research has translated into deployed solutions, with real-world impact extending well beyond the academic setting. Prior to joining ETH Zürich, she was a postdoctoral scholar at the University of California, Berkeley, and completed her PhD at the National University of Singapore.

