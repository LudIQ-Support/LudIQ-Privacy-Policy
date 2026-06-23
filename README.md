# Privacy Policy — Dicea

[🇫🇷 Version Française](fr.md)

| Metadata | Value |
| :--- | :--- |
| **Application** | Dicea |
| **Last Updated** | 20 June 2026 |

---

## 1. Introduction

**Dicea** is a free mobile application designed for board game players. It has been built from the ground up to respect users' privacy and functions primarily offline.

* **Local-First Storage:** Your personal data stays entirely on your device. Your game collection, plays, scores, player profiles (names and photos), and preferences are saved locally in your phone's private storage. No remote server retains a copy of this information.
* **No Accounts, No Ads:** Using the application requires neither account creation nor an email address. The application contains zero advertisements, uses no tracking networks, and does not sell any user data.
* **Minimal External Communication:** The information that leaves your device consists of the technical requests sent to BoardGameGeek to display game details, the downloading of game images from BoardGameGeek's image delivery network, and the text of game descriptions sent to a translation service when you use the application in French.

🔒 **Important Distinction (Content vs Metadata):** The content of these requests includes none of the data you have entered in the application: not your name, your player profiles or your statistics. However, as with any internet connection, these requests mandatory transmit technical connection data, such as your **IP address**, which may constitute personal data under the GDPR. This data is used solely to route the request through intermediary networks and serves neither to identify you personally nor to build a profile.

---

## 2. Data Controller

The publisher of the Dicea application acts as the data controller within the meaning of the General Data Protection Regulation (GDPR).

> 📋 **Publisher Information:**
> * **Publisher:** GODINEAU Savinien
> * **Status:** Individual Developer
> * **Registration Number:** Not applicable
> * **Contact Address:** Ludiq.support@gmail.com

For any questions regarding this policy or your data, you can reach out via the email address above.

---

## 3. Data Covered by this Policy

Dicea acts as a local companion app. To function properly, it processes specific categories of data. The vast majority of this data never leaves your device.

### 3.1. Data Stored Locally on Your Device
The following data is stored exclusively within the application's private storage sandbox. It is never transmitted to the publisher, nor is it accessible by the publisher or any third party:
* **Your Collection:** Owned games, wishlists, expansions, and favorites.
* **Your Plays:** Game sessions, dates, durations, formats, and participating players.
* **Your Statistics:** Match results per player, historical logs, and summaries.
* **Player Profiles:** Names or nicknames you manually input, along with any local photos or avatars chosen for profiles.
* **Your Preferences:** Language settings, display configurations, filters, and cached search parameters in the Explore tab.

✏️ **User Control:** You retain complete control over this data. You can modify or delete it at any time directly within the application, or manually export it in **JSON format**. Uninstalling the application permanently wipes all of this data from your device.

### 3.2. Data Exchanged with Third-Party Services
Certain features require a network connection to fetch online databases. The exact mechanics of these exchanges are detailed in **Section 5**.

---

## 4. Device Permissions

The application may request access to specific system features. These permissions are only triggered by an explicit action on your part and remain strictly limited to their core purpose.

| Permission | Purpose in Dicea | Data Transmission |
| :--- | :--- | :--- |
| **Photos & Camera** | Allows choosing an avatar image for a player or your own profile. | The selected image is copied locally into the app's secure sandbox. **No photos are uploaded to any server.** |
| **Save to Gallery** | Allows exporting a shareable graphic recap or summary sheet that you generate. | The image is compiled locally and saved directly to your device storage at your explicit request. |
| **Files & Storage Access** | Allows importing or exporting your manual backup file in JSON format via the system share sheet. | You manually choose the target file. The application does not browse or access other files. |

*You can refuse or revoke these permissions at any time via your device's operating system settings. If revoked, the corresponding features will simply become unavailable.*

---

## 5. Third-Party Services and Data Recipients

Dicea relies on a minimal number of infrastructure services to function. This section details what information is sent, who receives it, and why.

| Service / Infrastructure | Transmitted Data | Purpose of Flows | Provider & Privacy Link |
| :--- | :--- | :--- | :--- |
| **BoardGameGeek (API)** | Search keywords and game IDs. *(Zero user data)*. Routed through an editor proxy. | Fetches real-time public game information (titles, ratings, and descriptions). | BoardGameGeek<br>🔗 [Privacy Policy](https://boardgamegeek.com/privacy) |
| **BGG Image CDN** | Direct HTTP connection to `geekdo-images.com`. Exposes your **IP address** and graphics viewed. | Downloads game artwork, covers, and thumbnails directly to your screen. | Geekdo, LLC (USA)<br>*(Direct flow bypassing the publisher's proxy)* |
| **Game Catalogue** | Technical read-only API requests for public ranking data (top 10000 BGG). *(Zero user data)*. | Populates the discovery engine within the "Explore" tab with game suggestions. | Operated by the publisher<br>*(Database hosted on Supabase, via Cloudflare)* |
| **Translation Service** | English game descriptions. *(Zero user data. Inactive if the app is set to English)*. | Automatically translates public game descriptions into French for user readability. | DeepL API<br>🔗 [Privacy Policy](https://www.deepl.com/privacy) |
| **Technical Hosting** | Technical connection metadata (such as IP addresses) needed to route internet packets. | Secure routing (HTTPS) of API requests and performance edge-caching of public data. | Cloudflare Workers<br>🔗 [Privacy Policy](https://www.cloudflare.com/privacypolicy/) |

### 🔒 Strict No-Tracking Guarantee
For absolute clarity, Dicea does not use any analytics or audience measurement tools, any advertising networks or trackers, any third-party crash reporting suites (such as Firebase Crashlytics), and any features of the Google Firebase ecosystem.

### 5.5. Protection Provided by Third Parties
We only routing requests through infrastructure providers that offer stringent data protection safeguards. Where metadata or connection parameters pass through these networks, providers are legally bound to ensure a level of security compliant with applicable data protection laws.

---

## 6. Legal Bases for Processing

In accordance with **Article 6 of the GDPR**, data processing activities are justified under the following legal frameworks:
1. **Contractual Performance / Core Service Delivery:** Local storage of your collection, plays, player profiles, and preferences is necessary to deliver the core features of the companion app you actively use.
2. **Legitimate Interest:** Fetching public game information (including direct downloading of images), operating the Explore catalogue, and providing automated translations is justified by our legitimate interest in delivering a functional, rich, and localized user experience.
3. **Consent:** Access to your camera, photos, or gallery rests entirely on your explicit consent, granted via the native system permission prompts when you initiate those specific actions.

---

## 7. Transfers Outside the European Union

Depending on the technical providers, certain routing connection data (such as IP addresses and standard technical metadata) may be processed outside the European Economic Area (EEA)—specifically in the United States by **Cloudflare, Inc.** and **Geekdo, LLC**.

These transfers relate exclusively to technical network metadata necessary to deliver internet packets, strictly excluding any data entered by the user. They are safeguarded using **Standard Contractual Clauses (SCCs)** approved by the European Commission, alongside the providers' certified compliance mechanisms.

---

## 8. Data Retention

* **Local Data:** All data described in Section 3.1 is retained on your device indefinitely, as long as the application remains installed. It is wiped instantly and permanently upon deleting the app.
* **Network Requests:** Technical API requests sent to BoardGameGeek, the image CDN, the translation engine, and intermediary workers are stateless and are not linked to any user profile. Server caches for public game data are temporary.

---

## 9. Your Rights

Under the GDPR, you hold rights of access, rectification, erasure, restriction, objection, and portability regarding your personal data.

Because Dicea is built on a decentralized, local-first architecture, **you can exercise almost all of these rights directly without contacting us**:
* **Access & Portability:** You can view all data within the app interface or export your complete database into a standard JSON file at any time.
* **Rectification:** You can manually edit games, match entries, scores, and player profiles directly within the screens.
* **Erasure:** You can delete individual entries, reset the Explore cache, or completely uninstall the app to instantly purge all records.

You may **withdraw your consent** at any time, for example by revoking a permission in your system settings, which will simply make the corresponding features unavailable. To exercise any right requiring our direct intervention, contact us at **Ludiq.support@gmail.com**. We will respond within the statutory one-month timeframe.

You also have the right to lodge a complaint with a supervisory authority. In France, this is the **CNIL** (Commission Nationale de l'Informatique et des Libertés) at [www.cnil.fr](https://www.cnil.fr).

---

## 10. Security

Your local data is protected by your device's native operating system security, including application sandboxing and hardware-level encryption (if enabled on your phone). All network traffic detailed in Section 5 is forced over secure, encrypted connections (**HTTPS**).

*Recommendation: Since no system is entirely foolproof, we highly advise protecting your mobile device with a secure passcode or biometric authentication, and performing regular JSON data backups.*

---

## 11. Protection of Minors

Dicea is a general-audience application and is not specifically targeted at children. We do not knowingly collect personal data from minors. If you believe a child has inadvertently transmitted data to us via email, please contact us immediately so we can remove it.

Note that player profiles and names you enter may include household members or friends, including children. This information **remains strictly on your device**. By entering this information, you confirm that you have the appropriate right or authority to input it locally.

---

## 12. Changes to this Policy

This privacy policy may be updated from time to time to reflect application updates or regulatory shifts. Any change of this nature will be reflected in an updated version of this document prior to taking effect. In the event of a material change, we will highlight it within the app or on the web page hosting this document. The "Last Updated" date at the top will always reflect the latest revision.

---

## 13. Contact

For any inquiries regarding your privacy or this policy, please contact:

* **Email:** Ludiq.support@gmail.com
* **Publisher:** GODINEAU Savinien
* **Policy URL:** https://Dicea-support.github.io/Dicea-Privacy-Policy/
