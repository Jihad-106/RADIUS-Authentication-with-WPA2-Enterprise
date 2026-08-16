# RADIUS Authentication with WPA2-Enterprise

This lab demonstrates how **WPA2-Enterprise** can be used to secure a wireless network with centralized authentication through a **RADIUS server**.

The network consists of a wireless router, RADIUS/AAA server, switch, router, and wireless client devices. The wireless network uses **WPA2-Enterprise**, where users authenticate using individual credentials instead of a shared Wi-Fi password.

The **RADIUS server** is responsible for validating the user's username and password. When a wireless client attempts to connect, the authentication request is forwarded to the RADIUS server. If the credentials are valid, access is granted; otherwise, the authentication request is rejected.

### Key Concepts

* **WPA2-Enterprise** — Provides enterprise-level wireless authentication.
* **802.1X** — Framework used for network access authentication.
* **RADIUS** — Centralized server responsible for user authentication.
* **AAA** — Provides Authentication, Authorization, and Accounting services.
* **PEAP** — Authentication method used for protecting user credentials.

### Authentication Flow

`Wireless Client → Wireless Router/AP → RADIUS Server → Accept/Reject`

The lab also demonstrates that changing the RADIUS user's password affects wireless access, confirming that authentication is being handled by the centralized RADIUS server.

### Objective

The main objective of this lab is to understand how **WPA2-Enterprise, 802.1X, and RADIUS work together to provide centralized and user-based wireless authentication**.
