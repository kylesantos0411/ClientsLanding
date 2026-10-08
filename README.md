# Kyle Santos — Executive Landing Page & Digital Business Card

A luxury, high-craft executive landing page and contactless digital business card designed specifically for business owners, founders, and multi-venture entrepreneurs.

## ✨ Features

- **Luxury Obsidian & Champagne Gold Theme**: Premium dark-mode aesthetic with refined glassmorphism (`backdrop-filter`), subtle metallic halos, and editorial serif typography (`Cormorant Garamond` + `Plus Jakarta Sans`).
- **Exact Mobile-First Executive Card**:
  - Live availability pulse indicator (`Available for consultations`)
  - Direct Business Partner capsule (`Charls Andrada`)
  - Instant One-Click vCard (`.vcf`) generator & address book importer
  - Quick action glass tiles (Call, SMS, Email, Viber)
  - Direct LinkedIn connection badge
- **Executive Scroll Landing Sections**:
  - **Ventures & Companies Portfolio**: TapAndGo NFC Systems, Digital Presence Architecture, Business Systems Advisory
  - **Core Capabilities**: NFC cards, Google Review booster stands, high-performance web platforms, turnkey setup
  - **Consultation & Inquiry Form**: Client intake form with one-tap dispatch
  - **Executive Network Channels**: LinkedIn, Facebook, Instagram
- **In-Person Networking QR Code**: Live interactive QR code modal for scanning directly from smartphone screen
- **Zero-Build & Ultra-Fast**: Pure modern HTML5 + Tailwind CSS + Lucide Icons + QRCode.js. Instant 100/100 Lighthouse performance.

---

## 🚀 How to Deploy to Vercel

### Option 1: Via GitHub (Recommended)
1. Create a new repository on your GitHub account (e.g. `ClientsLanding` or `kyle-santos-executive`).
2. In your terminal inside this folder (`c:\Users\kyle\Downloads\ClientsLanding`), link and push:
   ```bash
   git remote add origin https://github.com/<your-username>/ClientsLanding.git
   git add .
   git commit -m "Initial commit of executive landing page"
   git push -u origin main
   ```
3. Go to [Vercel](https://vercel.com/dashboard) -> Click **Add New...** -> **Project**.
4. Import your newly pushed `ClientsLanding` repository.
5. Framework Preset: **Other** (leave Root Directory as `./`).
6. Click **Deploy**. Vercel will deploy it in seconds with global edge CDN and automatic HTTPS!

### Option 2: Deploy directly via Vercel CLI
If you have Vercel CLI installed:
```bash
vercel
```
Follow the prompt to deploy directly.

---

## ⚙️ Customization

Open `index.html` and edit the `CONFIG` object at line ~425 to update your phone numbers, emails, social links, or venture details:

```javascript
const CONFIG = {
  fullName: "Kyle Santos",
  title: "Entrepreneur & Multi-Business Owner",
  subtitle: "Digital Solutions, NFC Systems & Multi-Venture Leadership",
  company: "TapAndGo / Santos Group",
  phone: "+639194850794",
  email: "kylesantos0411@gmail.com",
  partner: {
    name: "Charls Andrada",
    url: "https://tapandgo.cards/charls"
  },
  socials: {
    linkedin: "https://www.linkedin.com/in/kyle-nero-santos-14287b349",
    facebook: "https://www.facebook.com/share/1C7PU3sCpu/?mibextid=wwXIfr",
    instagram: "https://www.instagram.com/kaiipuccino"
  }
};
```
