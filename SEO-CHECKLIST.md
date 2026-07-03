# Local Guardian — SEO Status & Checklist

Domain: **https://localguardiankerala.in** · Last updated: 2026-07-03

---

## 1. What is DONE (on-page SEO)

| Item | Status |
|---|---|
| Keyword-optimised `<title>` + meta description on every page | ✅ |
| Meta keywords tag (note: ignored by Google, kept for minor engines) | ✅ |
| Keywords woven into visible copy, headings, service names | ✅ |
| Image `alt` text with keywords | ✅ |
| Canonical URL on every page | ✅ |
| Open Graph tags (link previews) — home page | ✅ |
| JSON-LD structured data (ProfessionalService + 7-service catalog) — home page | ✅ |
| `sitemap.xml` (3 pages) | ✅ |
| `robots.txt` (reference files excluded from indexing) | ✅ |
| Mobile responsive + working mobile nav | ✅ |
| Descriptive internal links between pages | ✅ |

---

## 2. Keyword → Page mapping

### index.html (Home) — primary landing page
Optimised for:
- NRI Property Management / NRI Property Management Services
- Property Management Services / Property Management Kerala
- Property Caretaking Services / Property Caretaker / Care Taker of House / Caretaking Properties
- Home Watch Services / Property Monitoring
- Home Inspection Services / Property Inspection Services
- Cleaning & Maintenance / Property Maintenance Services / House Maintenance Services / Property Repair Services
- NRI Property Maintenance
- Vacant Property Management
- Tenant Management / Tenant Verification / Rent Collection Services / Rental Income Support
- Property Tax Assistance
- Airport Pickup and Drop / Airport Pickup and Drop Service

### about.html
Optimised for:
- Property Management Firm
- Property Management Companies in Kerala
- Remote Property Management
- NRI Property Management Services (secondary)
- Property Caretaking Services / NRI Property Maintenance (secondary)
- ABS Group (brand)

### contact.html
Optimised for:
- NRI Property Management Services (enquiry intent)
- Property Management Kerala
- Property Caretaker / Home Inspection Services (secondary)
- Rent Collection Services / Property Tax Assistance (secondary)
- Airport Pickup and Drop Service (secondary)

### Keywords with WEAK / shared coverage (need dedicated pages later)
Every keyword above competes on a shared page. These clusters have no
dedicated page yet, which limits ranking potential:
- Airport Transfer Service / Airport Pick Up Service (only a bullet + form option today)
- Remote Property Management (meta text only, thin visible copy)
- Property Repair Services (one bullet word)
- Rental Income Support (implied, not explicit on-page)

---

## 3. PENDING — implement later

### High impact
- [ ] **Dedicated service pages** (agreed: not now). One page per keyword cluster,
      interlinked from the home services cards:
      - `property-caretaking-home-watch.html` — caretaking, caretaker, home watch, monitoring, inspections
      - `property-maintenance-repair.html` — maintenance, cleaning, repair, NRI property maintenance
      - `tenant-management-rent-collection.html` — tenant verification, tenant management, rent collection, rental income support
      - `vacant-property-management.html` — vacant plots, dark-site management
      - `airport-pickup-drop.html` — airport transfer, pick up, pickup and drop
      - `property-tax-assistance.html` — property tax, TDS, filings
- [ ] **Google Search Console** — verify domain, submit `sitemap.xml` (nothing indexes until this + hosting are live)
- [ ] **Google Business Profile** listing (critical for "property management companies in Kerala" local-pack results) — needs a real street address
- [ ] **Backlinks / citations** — Justdial, Sulekha, IndiaMART, NRI forums and Kerala business directories

### Medium impact
- [ ] Replace Unsplash stock images with real photos, self-hosted, WebP-compressed, keyword filenames (e.g. `nri-property-management-kerala.webp`)
- [ ] FAQPage JSON-LD schema on the home FAQ section (rich results)
- [ ] BreadcrumbList JSON-LD on about/contact pages
- [ ] Open Graph + Twitter Card tags on about.html and contact.html (home only, today)
- [ ] Blog/articles for long-tail searches ("how NRIs can manage property in Kerala", "power of attorney for NRI property")
- [ ] Real social profile URLs (Facebook/Instagram links are `#` placeholders) + add them to JSON-LD `sameAs`

### Technical / housekeeping
- [ ] Confirm HTTPS + single canonical host (www vs non-www 301 redirect) once hosted
- [ ] Custom 404 page
- [ ] Google Analytics 4 (or similar) to measure which keywords convert
- [ ] Run Lighthouse/PageSpeed after hosting; consider self-hosting fonts & deferring JS if scores are low
- [ ] Keep `<lastmod>` in `sitemap.xml` updated when pages change
- [x] Contact email confirmed and updated site-wide to `care@localguardiankerala.in` (2026-07-03)
- [ ] Delete `about_page_reference.html` / `referenceindex.html` before deploying (blocked in robots.txt meanwhile)
