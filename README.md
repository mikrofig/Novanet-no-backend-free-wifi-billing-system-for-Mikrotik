
# 📡 NOVANET FREE WiFi Billing SYSTEM

This system allows MikroTik owners to accept Paystack payments directly on their routers without needing a VPS,vpn or a monthly billing service.

## 🚀 Deployment
1. Connect to your MikroTik via WinBox.
2. Open **Terminal**.
3. Paste the Deployment Script found in `/scripts/setup.rsc`.
4. Enter your Paystack Key in the `login.html` file.

## Features
- **Auto-Retry Logic:** Prevents login collisions.
- **Trial System:** Built-in 3-minute free trial using `localStorage`.
- **Anti-Hacker:** DevTools blocking and Right-Click disabling.
- **PC-Block Ready:** (Optional) JavaScript-based device detection.
