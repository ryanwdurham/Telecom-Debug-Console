# 📡 Telecom Debug Console

**Telecom Debug Console** is a browser-based simulator that visualizes **IMS / SIP + TLS call flows**, giving developers and test engineers a realistic debugging experience without requiring a live call. It is designed for learning, testing, and demoing telecom signaling and media stack behavior.

Click here to use:  https://ryanwdurham.github.io/Telecom-Debug-Console/ 
---

## Features

- **Simulated TLS handshake** with cipher suites, certificate, and OCSP status
- **SIP message flow**: REGISTER, INVITE, 100/180/200 responses, ACK, BYE
- **Full SDP body** for media negotiation
- **JWT / OAuth token logs** for authentication simulation
- **RTP stats over simulated call duration**: bitrate, jitter, packet loss
- **Error scenarios**: 401 Unauthorized, 503 Service Unavailable, Expired Certificate
- **Animated swimlanes** showing Caller → Server → Callee flow
- **Color-coded logs**: TLS, SIP, RTP, JSON, and error highlighting

---

## Use Cases

- Telecom engineers learning SIP / IMS call flows
- QA & test engineers simulating VoIP calls without a live environment
- Educational demos of signaling, TLS handshakes, and media negotiation
- Experimenting with error handling in SIP / TLS environments

---


