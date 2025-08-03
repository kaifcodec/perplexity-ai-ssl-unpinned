# 🧠 Perplexity AI v2.51.2 - Decrypted & Debug-Ready APKs

This repo contains reverse-engineered versions of the **Perplexity AI** app (`v2.51.2`) for Android — prepped for analysis, interception, and tooling.

---

## 📂 Included APKs

| File Name | Description |
|-----------|-------------|
| `Perplexity_2.51.2(spilt_apk).apk+` | 🧩 Raw split APK set as extracted from device or Play Store |
| `Perlexity_ai_antisplit.apk` | 🔧 Merged (anti-split) universal APK, installable on any device |
| `Perplexity_ai_2.51.2_ssl_unpinned.apk` | 🔓 SSL Pinning removed — ready for MITM, Frida, Burp, etc. |

---
## ⚠️ You may need to pause play protect scanning for Android 13+

---

## 🔐 SHA-1 Hashes

Verify file integrity using:

```bash
shasum <file>.apk

File	SHA-1

Perplexity_2.51.2(spilt_apk).apk+	1528868c5f9789cb78e2948003a245a73d389478
Perplexity_ai_2.51.2_ssl_unpinned.apk	9c5ae23d928a18d69970c686ecea0ff272a98587
Perlexity_ai_antisplit.apk	996a39623ea7f8f88c894bf15714f2a67b93ab29

```

---

🚧 About the SSL Unpinned Build

This version has been:

Decompiled via apktool

Patched to remove all SSL pinning mechanisms

Rebuilt and optionally resigned (if needed for install)

Verified for compatibility with Frida, Burp Suite, MITMproxy, etc.


This allows full interception and analysis of all network traffic, including HTTPS endpoints.


---

# 🧪 Use Cases

- 🔍 API reverse engineering

- 🧪 App traffic analysis

- ⚙️ Custom automation or AI interaction scripts

- 🔐 Certificate trust debugging on Android



---

⚠️ Legal Disclaimer

> This repo is provided strictly for educational, research, and debugging purposes.
All rights to the original app belong to Perplexity AI, Inc.
Do not use these files for commercial redistribution, impersonation, or malicious purposes.
> The author will not be responsible for any type of data loss or bans.

> If you use this beyond personal use the author will not be responsible for any type of harm you cause.



---

📎 Notes

These APKs are not modified beyond what’s stated.

If you’re the app developer and want this taken down, feel free to reach out via GitHub issues or email directly to me kaifcodec@gmail.com



---

🧰 Quick Tip

Use with:

adb install Perplexity_ai_2.51.2_ssl_unpinned.apk
frida -U -n com.perplexity.ai


---

> 📁 For deep-divers, all .smali diffs and patch notes can be optionally added in a future commit.



---
