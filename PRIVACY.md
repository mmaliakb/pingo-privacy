# Privacy Policy — Pingo: Network Tools

**Last updated: July 15, 2026**

This Privacy Policy describes how Pingo ("the app", "we") handles information when you use the Pingo network utility app for iOS.

## The Short Version

Pingo does not collect, store, transmit, sell, or share any personal data. There are no accounts, no analytics, no advertising, and no tracking of any kind. All tools run locally on your device.

## Data Collection

We collect **no data whatsoever**. Specifically, the app contains:

- No user accounts or registration
- No analytics or crash-reporting SDKs
- No advertising SDKs or identifiers
- No server operated by us — the app never sends anything to us

## How the Network Tools Work

Pingo's tools necessarily communicate over the network to perform the actions **you** initiate. This traffic goes directly from your device to the target you specify and is never routed through or recorded by us:

- **Ping, Traceroute, Port Check** send standard network packets to the host you enter.
- **IP Scanner** probes devices on your own local network. iOS asks for the Local Network permission before this works; the results are shown to you and stay on your device.
- **DNS Lookup** and **Whois** send your query to public DNS and whois servers, as any lookup tool must.
- **SSH Client** connects directly from your device to the server you specify. Your host, username, password, and session data are held in memory only for the duration of the session — they are **not** saved to disk, synced, or transmitted anywhere else.
- **Speed Test** opens speedtest.net (operated by Ookla, LLC) inside the app. Your use of that page is governed by Ookla's own privacy policy: https://www.ookla.com/privacy

## Data Storage

The app does not maintain any database of your activity. Results shown on screen (ping output, scan results, lookup responses) exist only in the app's memory and are gone when you clear them or close the app.

## Permissions

- **Local Network** — requested only so the IP Scanner can discover devices on your network. It is never used for tracking.

## Children's Privacy

Pingo does not collect data from anyone, including children under 13.

## Changes to This Policy

If a future version of the app ever changes how data is handled, this policy will be updated and the "Last updated" date revised before that version is released.

## Contact

If you have any questions about this policy, contact us at:

**Email:** cetin@ak-vit.com.tr
