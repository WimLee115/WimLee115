# Wim — `WimLee115`

**Securityspecialist in opleiding (ESF Plus-traject) · bouwer van verifieerbare beveiligings- en privacytools · Nederland**

Ik bouw beveiligingsgereedschap dat werkt zonder dat je iemand hoeft te
vertrouwen — ook mij niet. Geen account, geen cloud, geen belofte op erewoord.
Kloon de repo, lees de code, controleer de handtekening, en beslis dan zelf. Wat
je niet kunt controleren, moet je niet geloven.

**Soeverein** — jouw data, jouw sleutels · **Lokaal** — geen cloud, geen account · **Verifieerbaar** — getest en ondertekend · **Open** — AGPL waar het telt

> **EN — in short:** I'm retraining into information security through a Dutch
> ESF Plus programme, on top of a portfolio of security & privacy tooling you can
> verify yourself — across C, Rust, Python, TypeScript and Kotlin. Highlights: an
> out-of-tree Wi-Fi 6 kernel driver, signed audit-grade web recon, cryptographic
> proof-of-existence, and a blue/red/purple detection-engineering suite. Open to
> security roles in the Netherlands (SOC / blue team, detection engineering,
> appsec, security tooling). Contact: **almass-only@protonmail.com**.

---

## Waar ik nu sta

- Bezig met omscholing tot **Securityspecialist ICT** via een **ESF Plus**-traject (2026).
- Richting: **detection engineering / blue team**, netwerk- en wifi-security,
  toegepaste cryptografie en application security.
- **Open voor een securityrol** in Nederland — junior/medior, met een
  bewezen bouw- en zelfstudieachtergrond.

## Opleiding & certificering

Eerlijk over de status: dit is waar ik mee bezig ben, niet wat al op een muur hangt.

- **CompTIA Security+** — in voorbereiding (met een eigen offline studiehub).
- **ITIL 4 Foundation** en **EXIN Information Security Foundation (ISO/IEC 27001)** — in studie via [project115](https://github.com/WimLee115/project115).
- Doorlopend: hands-on netwerk-, wifi- en detectiewerk in eigen labs (zie hieronder).

## Vaardigheden

| Gebied | Waarmee |
|---|---|
| **Talen** | Rust · C · Python · TypeScript · Kotlin · Shell |
| **Blue team / detection** | detection engineering, tamper-evident logging, adversary emulation met dekkingsscore, IDS-achtige host- en netwerkdetectie |
| **Red / offensief** | geautoriseerde recon, wifi (monitor mode + injectie), pentest-scope afgedwongen in code |
| **Netwerk & systeem** | Linux out-of-tree kerneldrivers (DKMS), 802.11-monitoring, netwerkverkenning |
| **Cryptografie** | Ed25519-ondertekening, OpenPGP (sequoia), AES-256-GCM / ChaCha20-Poly1305, SHA-256 + OpenTimestamps |
| **Werkwijze** | open source (AGPL waar het telt), ondertekende releases, "elke belofte een test", verifieerbare builds |

---

## Uitgelicht werk

**[rtl8852au-build](https://github.com/WimLee115/rtl8852au-build)** — out-of-tree Wi-Fi 6 USB-driver · ★8
`C` · kernel 6.17–7.0 · DKMS · stabiele monitor mode · web-dashboard
Out-of-tree Linux-driver voor Realtek RTL8852AU / RTL8832AU. Werkende monitor mode
en injectie op moderne kernels — de basis onder mijn wifi-securitywerk.

**The French Trilogy** — blue / red / purple detection-engineering in Rust *(privécode, op aanvraag in te zien)*
Een drieluik dat samenwerkt: **MonsieurWim** (blauw) doet host-inbraakdetectie met
een escalatieladder en een tamper-evident bewijsketen; **ÉpouseWim** (rood) is
offensief gereedschap met de pentest-scope in de code verankerd — een doel buiten
de opdracht compileert niet eens — en een tamper-evident logboek; **Ni de gauche
ni de droite** (paars) laat rood echt handelen en meet hoofdloos of blauw het
betrapt, en scoort de detectiedekking in een verifieerbaar rapport. Nederlandstalig,
harde crate-grenzen bewaakt in CI, elke belofte gedekt door een test.

**[wimsalabim](https://github.com/WimLee115/wimsalabim)** — audit-grade web-security & privacy-recon
`Python` · AGPL-3.0 · [![pypi](https://img.shields.io/pypi/v/wimsalabim?style=flat-square&label=pypi&color=555)](https://pypi.org/project/wimsalabim/)
Ed25519-ondertekende rapporten, SARIF 2.1-uitvoer, geen vendor-spin. `pip install wimsalabim`.

---

## Meer projecten

**[keytool](https://github.com/WimLee115/keytool)** — OpenPGP-sleutelbeheer
`Rust` · AGPL-3.0 — Curve25519 via sequoia-openpgp; sleutels landen in de gpg-keyring, gpg-agent bewaakt het privémateriaal. Library first, dunne CLI erop.

**[pvank](https://github.com/WimLee115/pvank)** — cryptografisch bewijs van bestaan
`TypeScript` · AGPL-3.0 — SHA-256 + OpenTimestamps, verankerd in de Bitcoin-blockchain. Bewijs dat een document op een dag bestond — geen notaris, geen vertrouwen. Met browser-extensie ([pvank-extension](https://github.com/WimLee115/pvank-extension), MV3).

**[LeeCrypt](https://github.com/WimLee115/LeeCrypt)** — Android-encryptietoolkit
`Kotlin` · ★1 — AES-256-GCM en ChaCha20-Poly1305, biometrische sleutelopslag, steganografie, overdracht via NFC en QR.

**[security-research](https://github.com/WimLee115/security-research)** — disclosures & write-ups
Responsible disclosures, CTF- en labnotities. Uitsluitend geautoriseerde doelen.

**[project115](https://github.com/WimLee115/project115)** — offline examentrainer
`TypeScript` — ITIL Foundation (v5) en EXIN ISO/IEC 27001. Proefexamens onder echte condities, spaced repetition, volledig offline.

---

## Onderzoek & documentatie

- **[Dossier608](https://github.com/WimLee115/Dossier608)** — langlopend onderzoeksdossier (Nederlandse bewindvoeringssector).
- **[ECLI-s](https://github.com/WimLee115/ECLI-s)** — verzameling Nederlandse rechtspraak over bewind, mentorschap en curatele.
- **[github-leesmij](https://github.com/WimLee115/github-leesmij)** — GitHub uitgelegd in gewoon Nederlands.

## Gearchiveerd

Publiek en te klonen, maar er beweegt niets meer.

- **PrivacyTools** en **repolyzer** — stil sinds 26 februari 2026.
- **hacknet-protocol-game** — alleen LICENSE en README publiek; de code staat privé.

---

## Contact

- **Voor werkgevers en recruiters:** **bvanrooij@hotmail.nl**
- **Kwetsbaarheden:** GitHub Security Advisories op de betreffende repo.
