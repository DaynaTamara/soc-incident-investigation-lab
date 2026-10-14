TryHackMe Lab: FakeBank Security Investigation

Overview

- Platform: TryHackMe
- Room: Think Like a Hacker
- Focus: Basic web security and authentication
- Status: Completed

Objective

Learn how to identify an insecure bank transfer page and understand why authentication is essential for protecting sensitive financial operations.

Tools and Techniques

- DIRB: Used to discover web directories and hidden pages in the lab environment.
- Web browser: Used to access and investigate the simulated banking application.
- Security analysis: Evaluated the risks of allowing access to a bank transfer page without requiring login.

Findings

During the lab, I discovered a bank transfer page in the simulated FakeBank application. The exercise demonstrated the risk of allowing users to access sensitive financial functionality without proper authentication.

Security Recommendations

- Require users to authenticate before accessing bank transfer functionality.
- Enforce server-side authorization checks for sensitive operations.
- Validate transactions on the server.
- Monitor suspicious activity and unauthorized access attempts.

Key Learnings

- Discovered how directory enumeration can reveal accessible web pages.
- Learned why hiding a URL is not a substitute for proper access control.
- Understood the importance of authentication and authorization in protecting financial applications.

Disclaimer

This activity was completed in TryHackMe's authorized training environment for educational purposes.
