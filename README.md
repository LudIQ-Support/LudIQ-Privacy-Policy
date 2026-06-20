# Privacy Policy

[🇫🇷 Version Française](fr.md)

| Metadata | Value |
| :--- | :--- |
| **Application** | LudIQ |
| **Last Updated** | 13 June 2026 |

---

## 1. Introduction

**LudIQ** is a free mobile application designed for board game players. It has been built from the ground up to respect users' privacy and functions primarily offline.

* **Local-First Storage:** Your personal data stays entirely on your device. Your game collection, plays, scores, player profiles (names and photos), and preferences are saved locally in your phone's private storage. No remote server retains a copy of this information.
* **No Accounts, No Ads:** Using the application requires neither account creation nor an email address. The application contains zero advertisements, uses no tracking networks, and does not sell any user data.
* **Minimal External Communication:** The only information leaving your device consists of technical API requests sent to BoardGameGeek to fetch game metadata, and the text of game descriptions sent to a translation service when using the app in French. None of this information can identify you personally.

This policy outlines all data processing activities in full compliance with transparency standards.

---

## 2. Data Controller

The publisher of the LudIQ application acts as the data controller within the meaning of the General Data Protection Regulation (GDPR).

> 📋 **Publisher Information:**
> * **Publisher:** GODINEAU Savinien
> * **Status:** Individual Developer
> * **Registration Number:** Not applicable
> * **Contact Address:** Ludiq.support@gmail.com

For any questions regarding this policy or your data, you can reach out via the email address above.

---

## 3. Data Covered by this Policy

LudIQ acts as a local companion app. To function properly, it processes specific categories of data. The vast majority of this data never leaves your device.

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

| Permission | Purpose in LudIQ | Data Transmission |
| :--- | :--- | :--- |
| **Photos & Camera** | Allows choosing an avatar image for a player or your own profile. | The selected image is copied locally into the app's secure sandbox. **No photos are uploaded to any server.** |
| **Save to Gallery / Storage** | Allows exporting a shareable graphic recap or summary sheet that you generate. | The image is compiled locally and saved directly to your device storage at your explicit request. |
| **Files & Storage Access** | Allows importing or exporting your manual backup file in JSON format via the system share sheet. | You manually choose the target file. The application does not browse or access other files. |

*You can refuse or revoke these permissions at any time via your device's operating system settings. If revoked, the corresponding features will simply become unavailable.*

---

## 5. Third-Party Services and Data Recipients

LudIQ relies on a minimal number of infrastructure services to function. This section details what information is sent, who receives it, and why.

| Service | Transmitted Data | Purpose | Provider & Privacy Link |
| :--- | :--- | :--- | :--- |
| **BoardGameGeek** | Search keywords and game IDs. *(No personal data, names, or stats are ever sent)*. | Fetches real-time public game information (titles, artwork, ratings, descriptions, and trending games). | BoardGameGeek<br>🔗 [Privacy Policy](https://boardgamegeek.com/privacy) |
| **Game Catalogue** | Technical read-only API requests for public ranking data. | Populates the discovery engine within the "Explore" tab with game suggestions. | Supabase & Cloudflare<br>*(No personal data involved)* |
| **Translation Service** | English game descriptions. *(Triggered only if the app is set to French)*. | Automatically translates game descriptions into French for user readability. | DeepL API<br>🔗 [Privacy Policy](https://www.deepl.com/privacy) |
| **Technical Hosting** | Technical metadata (such as network IP address) needed to route internet packets. | Secure routing of API requests and performance edge-caching of public game data. | Cloudflare Workers<br>🔗 [Privacy Policy](https://www.cloudflare.com/privacypolicy/) |

### 🔒 Strict No-Tracking Guarantee
For absolute clarity, LudIQ **does not use**:
* Any analytics or audience measurement tools.
* Any advertising networks or trackers.
* Any third-party crash reporting suites (e.g., Firebase Crashlytics).
* Any Firebase ecosystem features.

The current version of the application is 100% free, contains no ads, and features no in-app purchases.

### 5.5. Protection Provided by Third Parties
We only routing requests through infrastructure providers that offer stringent data protection safeguards. Where metadata passes through these networks, providers are legally bound to ensure a level of security compliant with applicable data protection laws.

---

## 6. Legal Bases for Processing

In accordance with **Article 6 of the GDPR**, data processing activities are justified under the following legal frameworks:
1. **Contractual Performance / Core Service Delivery:** Local storage of your collection, plays, player profiles, and preferences is necessary to deliver the core features of the companion app you actively use.
2. **Legitimate Interest:** Fetching public game information and providing automated French translations is justified by our legitimate interest in delivering a functional, readable, and localized user experience.
3. **Consent:** Access to your camera, photos, or storage rests entirely on your explicit consent, granted via the native system permission prompts when you initiate those actions.

---

## 7. Transfers Outside the European Union

Depending on the technical providers, certain routing metadata (such as IP addresses) may be processed outside the European Economic Area (EEA)—specifically by **Cloudflare, Inc.** in the United States.

These infrastructure transfers are safeguarded using **Standard Contractual Clauses (SCCs)** approved by the European Commission, alongside the providers' certified compliance mechanisms. This metadata contains no user-identifying data.

---

## 8. Data Retention

* **Local Data:** All data described in Section 3.1 is retained on your device indefinitely, as long as the application remains installed. It is wiped instantly and permanently upon deleting the app.
* **Network Requests:** Technical API requests sent to BoardGameGeek, the translation engine, and intermediary workers are stateless and are not linked to any user profile. Server caches for public game data are temporary.

---

## 9. Your Rights

Under the GDPR, you hold rights of access, rectification, erasure, restriction, objection, and portability regarding your personal data.

Because LudIQ is built on a decentralized, local-first architecture, **you can exercise almost all of these rights directly without contacting us**:
* **Access & Portability:** You can view all data within the app interface or export your complete database into a standard JSON file at any time.
* **Rectification:** You can manually edit games, match entries, scores, and player profiles directly in the settings.
* **Erasure:** You can delete individual entries, reset the Explore cache, or completely uninstall the app to instantly purge all records.

If you wish to withdraw system permissions, you can do so at any time via your phone's Settings app. To exercise any right requiring our direct intervention, contact us at **Ludiq.support@gmail.com**. We will respond within the statutory one-month timeframe.

You also have the right to lodge a complaint with a supervisory authority. In France, this is the **CNIL** (Commission Nationale de l'Informatique et des Libertés) at [www.cnil.fr](https://www.cnil.fr).

---

## 10. Security

Your local data is protected by your device's native operating system security, including application sandboxing and hardware-level encryption (if enabled on your phone). All network traffic detailed in Section 5 is forced over secure, encrypted connections (**HTTPS**).

*Recommendation: Since no system is entirely foolproof, we highly advise protecting your mobile device with a secure passcode or biometric authentication, and performing regular JSON data backups.*

---

## 11. Protection of Minors

LudIQ is a general-audience application and is not specifically targeted at children. We do not knowingly collect personal data from minors. If you believe a child has inadvertently transmitted data to us, please contact us immediately.

Note that player profiles and names you enter may include household members or friends, including children. This information **remains strictly on your device**. By entering this information, you confirm that you have the appropriate right or authority to input it locally.

---

## 12. Changes to this Policy

This privacy policy may be updated from time to time to reflect application updates or regulatory shifts (for instance, if future versions introduce optional paid modules or in-app purchases). Material changes will be highlighted within the app or on the hosting page prior to taking effect. The "Last Updated" date at the top will always reflect the latest revision.

---

## 13. Contact

For any inquiries regarding your privacy or this policy, please contact:

* **Email:** Ludiq.support@gmail.com
* **Publisher:** GODINEAU Savinien
* **Policy URL:** https://ludiq-support.github.io/LudIQ-Privacy-Policy/
