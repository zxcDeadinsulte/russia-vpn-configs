# <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNTljeGk4d3lzZnU3Mm1peDBienFpbmEyb3JmaDB5N21tMW9oczIwdyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/8p1WPEOeDWFCksfe18/giphy.gif" width="45">  Free VPN configurations that work in Russia

[![Stars](https://img.shields.io/github/stars/igareck/vpn-configs-for-russia?style=flat)](https://github.com/zxcDeadinsulte/public-vpn-configs/stargazers)
[![Issues](https://img.shields.io/github/issues/igareck/vpn-configs-for-russia?style=flat&color=0e75b6)](https://github.com/zxcDeadinsulte/public-vpn-configs/issues)
[![last commit][1]][1]

[1]: https://custom-icon-badges.demolab.com/github/last-commit/igareck/vpn-configs-for-russia?logo=history&logoColor=white&color=0e75b6&style=flat

**🌐 Язык: [Русский](README.md) | 🌐 Language: [English](README-EN-US.md)

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="20"> A collection of public and free, auto-updating and auto-checked VPN configurations tested to work within the Russian Federation (`VLESS` / `VMess` / `Shadowsocks` / `Hysteria2` / `Tuic` / `Trojan` and others).

For bypassing Roskomnadzor (RKN) blocks.

The collection is filtered by category into black and white CIDR and SNI lists.

Each configuration is a TXT subscription that can be imported into any client you need (`v2rayN`, `Streisand`, `NekoBox`, `Throne` and others).

Once every 1–2 hours, before publishing, configs pass automated health checks on a server in Russia; slow and non-working ones are filtered out.

Real tests are performed for reachability, latency, and speed — not just a regular auto-collection and deduplication. From November 13 to December 28 I did everything manually; on December 28 I finished a script that automated and sped up the checking process while keeping the same high-quality “manual” result.

Classic VPNs (OpenVPN, WireGuard, etc.) haven’t worked for a long time — and it doesn’t matter whether your subscription is paid or not.

That’s why it’s important to use configurations verified to work specifically in Russia, so you can stay online.

It’s also important to update public configs frequently, because they tend to appear quickly — and stop working just as quickly. That’s why I added auto-updating with auto-checking/auto-tests, so every user in Russia can always get the freshest list of high-quality VPN configurations without extra junk.

## 🔴 ATTENTION FOR USERS OUTSIDE RUSSIA!

❗❗❗ IF YOU ARE NOT IN RUSSIA (CHINA, IRAN, OR ANY OTHER COUNTRY), USE ONLY CONFIGURATIONS FROM THE "BLACK LIST" ("BLACK_SS+All_RUS.txt", "BLACK_VLESS_RUS.txt" and "BLACK_VLESS_RUS_mobile.txt").

The "WHITE LIST" (WHITE) will NOT help you, because the "WHITE LIST" is configured ONLY to bypass specific and the strongest restrictions INSIDE Russia! For other countries, the "WHITE LIST" will be a practically non-working, slow, and useless option!

The "BLACK LIST" (BLACK LIST) is an "international VPN option" and contains the fastest public configurations available on the internet!

THANK YOU FOR YOUR ATTENTION!

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3Yml0MndhcDZ6dzFuYjY3aG0yNWowN2Rqbnp1aTV2cXNvb3FvMnluMiZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/MxryCOQuSYVVD0SPyp/giphy.gif" width="40"> How do I use these configurations on my device?

1) The most convenient way to add VPN configurations on your device is via a *“subscription”* or *“subscription group”* in v2rayN, Throne, v2rayNG, NekoBox, Streisand or Karing.

2) Copy the URL of the Github txt file. After copying the link, in the app you need to press “Add from clipboard”, or use the usual “Add” button -> “Configure manually” -> type “Subscription” -> paste the link to the txt file and set a subscription name.

3) Scan the subscription QR code from the next section. QR is even easier: press “Add” -> “Scan QR code” and the app will create a subscription automatically; you’ll only need to rename it on your phone and press “Update” if the config list didn’t load immediately.
   
   QR codes are located under the subscription link — click the arrow labeled “QR code”.
   
4) How to check which configs/servers are alive and working right now?

   Click the whole subscription (its name at the top) or an individual config; usually you need to press and hold to bring up a menu. Choose, *attention!*, *“Test real latency”* or *“Latency”*! Not “TCP Ping” or “ICMP Ping” — those won’t show real VPN server availability. The ones that respond with green numbers are the ones to use. Pick the smallest numbers: the smaller the number, the lower the latency and the faster the server will respond.

5) It is strongly recommended to enable subscription auto-update at least 2 times a day (every 12 hours), and even more often during long holidays. Configurations are updated every hour, because they stop working over time. If you enable updates, you’ll always have the freshest version of the subscription with working configs and no extra “junk”.

7) Configs (especially from White lists) may not turn green immediately in the “real latency” check; very often you need to ping 2–3–4 times to see newly available servers.

8) Install a few different clients on your phone — sometimes different clients will see different available servers. This is due to differences in client settings during config checks.

You can also add everything manually one-by-one by copying the contents of each txt file into v2rayN and others, but subscriptions are convenient because they update automatically on your device after updates on Github — without needing to delete and copy again — simplifying the process.

## 🧩 Apps for configs on PC and phone:

###  <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3amtqMmQxOGh0aG0waGk5OGhhNG5odmdob2k1bWc4ejNyZ3E3N2Y2bCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/xUS4Fp5i6iIn2Y1EYT/giphy.gif" width="25"> Windows/Linux/MacOS

Install the official v2rayN or Throne (successor of Nekoray) client, run it in “Administrator” mode, add a config/subscription, update it, you’ll get a list, run “real latency” checks, then sort by ping, pick a green one with the smallest number by pressing Enter, and finally enable “VPN mode / TUN mode”.

**1)** **v2rayN:**
  
   *I recommend v2rayN because it works stably and has been proven to handle thousands of configs of different protocols at once (my personal max is 150,000). It’s the most universal client. It works using Xray, Sing-Box, Mihomo together.*

   https://github.com/2dust/v2rayN/releases
  
   `v2rayN-windows-64.zip` for Windows
  
   `v2rayN-linux-64.deb` for Linux (Ubuntu)
  
   `v2rayN-macos-64.dmg` for MacOS

**2)** **Throne (successor of Nekoray, which is no longer updated since 2024)**:

*Recommended as an alternative working client after v2rayN.*

   https://github.com/throneproj/Throne/releases

   `Throne-1.0.8-windows64-installer.exe` for Windows
  
   `Throne-1.0.8-debian-x64.deb` for Linux (Ubuntu)
  
   `Throne-1.0.8-macos-arm64.zip` for MacOS

**3)** **Karing:**

   https://github.com/KaringX/karing/releases

   `karing_1.2.10.1300_windows_x64.exe` for Windows
  
   `karing_1.2.10.1300_linux_amd64.deb` for Linux (Ubuntu)
  
   `karing_1.2.10.1300_macos_universal.dmg` for MacOS
   
**4)** **Singbox-launcher:** 

  *A new client worth trying for testing VPN configurations; works together with Sing-Box. Give it a try — the developer is friendly and responsive.*

   https://github.com/Leadaxe/singbox-launcher/releases

   `singbox-launcher-v0.7.1-win64.zip` for Windows
  
   `singbox-launcher-v0.7.1-macos.zip` for MacOS

### <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3aGcxcG8yMGNzOTNmZDE1Z3hob3V3ajU4dmhkdnhsY2doMXFrNXowMyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/oFSDc1Oq12Ie5NJnmA/giphy.gif" width="20"> iOS — use Streisand, Shadowrocket, Karing, V2Box or v2RayTun from the App Store.

  I recommend Streisand: it declares no data collection in the App Store, and all features (including DNS switching) work correctly unlike many similar clients; loading and working with configs is stable.

  Happ is not recommended by users due to unstable performance/ping.

   **1)** `Streisand` https://apps.apple.com/us/app/streisand/id6450534064 
   
   *Best free iOS client with no data collection*

   **2)** `Shadowrocket` https://apps.apple.com/us/app/shadowrocket/id932747118 
   
   *Doesn’t drop connections even after long idle time, no data collection, but paid*

   **3)** `Karing` https://apps.apple.com/us/app/karing/id6472431552
     
   *Opinions about Karing are mixed: some like it, others have connection issues*

   **4)** `V2Box` https://apps.apple.com/us/app/v2box-v2ray-client/id6446814690

   **5)** `v2RayTun` https://apps.apple.com/us/app/v2raytun/id6476628951
  
### <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODUzYWRwNzNpa3doMDd1bXo4NTlzanJsaTcya3dlNXA4d3c5cnVzNCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/UQJlZ2OcaCA2RLfGiZ/giphy.gif" width="20"> Android — use v2rayNG and NekoBox from GitHub, or v2Box and v2RayTun from Google Play.

 I recommend v2rayNG, because it’s an Android analogue of my favorite PC client v2rayN from the same developer “2dust”.

 Also try NekoBox — users praise it.

 Happ is not recommended by users due to unstable performance/ping.

  **1)** `NekoBox` https://github.com/MatsuriDayo/NekoBoxForAndroid/releases

  **2)** `v2rayNG`  https://github.com/2dust/v2rayNG/releases

  **3)** `v2Box` https://play.google.com/store/apps/details?id=dev.hexasoftware.v2box

  **4)** `v2RayTun` https://play.google.com/store/apps/details?id=com.v2raytun.android&hl=en&pli=1

