# Inventory API testimise projekt

Õppeprojekt REST API (laokirjete süsteem) testimiseks — alates testjuhtumite spetsifikatsioonist kuni automatiseerimise, defektide leidmise ja lõpparuandeni.

---

## Tehnoloogiad

- **Node.js** & **Express** — API server (`server.js`)
- **Playwright Test** — API testide automatiseerimine
- **Markdown** — testjuhtumite spetsifikatsioon ja aruandlus

---

## Projekti struktuur

Kõik olulised failid asuvad juurkaustas:
- `server.js` — REST API kood
- `items.api.spec.ts` — Playwright API automaattestid (TC-01...TC-10)[cite: 1]
- `test-cases.md` — testjuhtumite spetsifikatsioon (10 stsenaariumi)[cite: 1]
- `defects.md` — leitud defektide raportid (D-01...D-03)[cite: 1]
- `test-report.md` — testi lõpparuanne ja uuesti testimise tulemused[cite: 1]
- `review-of-team-X.md` — teise meeskonna PR-i ülevaatuse tulemused[cite: 1]

---

## Kiiralustus

### 1. Sõltuvuste paigaldamine
```bash
npm install
