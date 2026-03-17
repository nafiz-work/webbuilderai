# Template Variables — Handyman Website Template

Every field below must be replaced per client. Organized by file and location.

---

## GLOBAL BUSINESS INFO (used across all 3 files)

| Variable | Current Value | Used In |
|----------|--------------|---------|
| Business Name | Swinging Hammer Home Repair, LLC | All files, nav, footer, schema, meta, privacy, terms |
| Business Name (short) | Swinging Hammer | Nav logo, footer brand, OG tags |
| Business Tagline | Home Repair, LLC | Nav logo subtext |
| Phone Number | (281) 685-8549 | Nav, hero CTA, contact meta, footer, schema, FAQ answer, areas note, privacy, terms |
| Phone (tel: format) | +12816858549 | Hero button href, nav href, schema |
| Email | bobby@swinginghammer.com | Footer mailto, contact footer, schema, privacy, terms |
| Website URL | https://swinginghammer.com | Canonical, OG url, schema url, schema logo, schema image |
| City | Houston | Title, meta description, OG, geo tags, schema, hero, about, all copy |
| State | TX | Schema, geo tags |
| State (full) | Texas | (removed, but may need for license badge) |
| Founded Year | 2006 | Hero badge, schema foundingDate, about text |
| Years in Business | 20+ | About stat, footer copy, value props |

---

## index.html — HEAD / META TAGS

| Line Area | Variable | Current Value |
|-----------|----------|--------------|
| `<title>` | Page title | Houston Handyman Services \| Swinging Hammer Home Repair - Licensed & Insured Since 2006 |
| `meta description` | SEO description | Houston's trusted handyman since 2006. Licensed & insured pros for drywall repair... Call (281) 685-8549. |
| `meta keywords` | SEO keywords | Houston handyman, handyman services Houston TX, drywall repair Houston... |
| `meta author` | Author | Swinging Hammer Home Repair, LLC |
| `link canonical` | Canonical URL | https://swinginghammer.com/ |
| `og:url` | OG URL | https://swinginghammer.com/ |
| `og:title` | OG title | Houston Handyman Services \| Swinging Hammer Home Repair |
| `og:description` | OG description | Houston's trusted handyman since 2006... |
| `og:image` | OG image URL | https://swinginghammer.com/images/hanyman%20hero.webp |
| `og:image:alt` | OG image alt | Swinging Hammer Home Repair — Houston's trusted handyman since 2006 |
| `og:site_name` | Site name | Swinging Hammer Home Repair |
| `twitter:title` | Twitter title | (same as OG) |
| `twitter:description` | Twitter desc | (same as OG) |
| `twitter:image` | Twitter image | (same as OG) |
| `twitter:image:alt` | Twitter alt | (same as OG) |
| `geo.region` | Region code | US-TX |
| `geo.placename` | City | Houston |
| `link icon` | Favicon path | images/hanyman_logo.png |
| `apple-touch-icon` | Icon path | images/hanyman_logo.png |

---

## index.html — SCHEMA MARKUP (LocalBusiness)

| Field | Current Value |
|-------|--------------|
| name | Swinging Hammer Home Repair, LLC |
| description | Houston-based handyman company specializing in... |
| telephone | +12816858549 |
| email | bobby@swinginghammer.com |
| url | https://swinginghammer.com |
| logo | https://swinginghammer.com/images/hanyman_logo.png |
| image | https://swinginghammer.com/images/hanyman%20hero.webp |
| address.addressLocality | Houston |
| address.addressRegion | TX |
| geo.latitude | 29.7604 |
| geo.longitude | -95.3698 |
| areaServed (array) | Houston, Katy, Sugar Land, Pearland, Missouri City, Friendswood, Cypress, Spring, The Woodlands, League City |
| openingHours (weekday) | Mon-Fri 07:00-18:00 |
| openingHours (weekend) | Sat 08:00-16:00 |
| priceRange | $$ |
| foundingDate | 2006 |
| hasOfferCatalog (9 services) | Drywall Repair & Patching, Door Installation & Repair, Interior Painting, etc. |
| aggregateRating.ratingValue | 5.0 |
| aggregateRating.ratingCount | 50 |
| aggregateRating.reviewCount | 50 |
| sameAs (social URLs) | facebook.com/swinginghammer, instagram.com/swinginghammer, g.page/swinginghammer |

---

## index.html — SCHEMA MARKUP (FAQPage)

Each FAQ entry (6 total):
- Question text
- Answer text (some contain phone number and city names)

---

## index.html — SCHEMA MARKUP (WebSite)

| Field | Current Value |
|-------|--------------|
| name | Swinging Hammer Home Repair |
| url | https://swinginghammer.com |

---

## index.html — NAV

| Element | Current Value |
|---------|--------------|
| Logo text (line 1) | Swinging Hammer |
| Logo text (line 2) | Home Repair, LLC |
| Nav phone number | (281) 685-8549 |
| Nav phone href | tel:+12816858549 |
| Services dropdown (9 items) | Drywall Repair, Door Installation, Interior Painting, Carpentry & Trim, Fixture Installation, Fence Repair, Pressure Washing, Tile & Grout Repair, Gutter Cleaning & Repair |

---

## index.html — HERO SECTION

| Element | Current Value |
|---------|--------------|
| Badge text | Serving Houston Since 2006 |
| Heading line 1 | Your Trusted |
| Heading line 2 (accent) | Houston Handyman |
| Subheading | No job too small. From drywall and doors to carpentry and painting, we show up on time, work clean, and get it done right. |
| CTA button 1 text | Call Now |
| CTA button 1 href | tel:+12816858549 |
| CTA button 2 text | Get a Free Estimate |
| Trust badges (3) | Licensed & Insured, No Crazy 4-Hour Windows, Locally Owned |
| Background image | images/hanyman%20hero.webp |
| Background image alt | Swinging Hammer Home Repair — professional handyman services in Houston, TX |

---

## index.html — VALUE PROPS (3 items)

Each item has:
- Icon (SVG)
- Title (e.g., "Licensed & Insured", "Always On Time", "20+ Years Experience")
- Description text

---

## index.html — LICENSE / INSURANCE BAR (3 badges)

| Badge | Fields |
|-------|--------|
| Badge 1 | Title: "Licensed Contractor", Description: "Fully licensed professional..." |
| Badge 2 | Label: "Fully Covered", Title: "$1M Liability Insurance", Description |
| Badge 3 | Label: "Surety Bond", Title: "Bonded & Trustworthy", Description |

---

## index.html — SERVICES (JavaScript `data.services` array — 9 items)

Each service object contains:
- `icon` — SVG markup
- `title` — e.g., "Drywall Repair & Patching"
- `desc` — Short description
- `includes` — Array of 6 bullet points (what's included)
- `steps` — Array of 5-6 steps (process)
- `timeline` — e.g., "Half day – 1 day"

**All 9 services:**
1. Drywall Repair & Patching
2. Door Installation & Repair
3. Interior Painting
4. Carpentry & Trim Work
5. Fixture & Appliance Installation
6. Fence Repair & Installation
7. Pressure Washing
8. Tile & Grout Repair
9. Gutter Cleaning & Repair

NOTE: The service names also appear in:
- Nav dropdown menu
- Form `<select>` options
- Footer services list
- Schema hasOfferCatalog

---

## index.html — HOW IT WORKS (3 steps)

Each step:
- Number (1, 2, 3)
- Icon (inline SVG)
- Title (e.g., "Call or Submit a Request")
- Description text

---

## index.html — GALLERY (7 image slots)

Each slot:
- Image `src` path (e.g., images/work-1.jpg through work-7.jpg)
- Image `alt` text (unique per image, includes business name + city)
- Overlay label (e.g., "Drywall Repair", "Door Installation")

---

## index.html — ABOUT SECTION

| Element | Current Value |
|---------|--------------|
| Section label | Our Story |
| Heading | Houston's Most Trusted Home Repair Team |
| Paragraph 1 | We're a Houston-based handyman company... since 2006... |
| Paragraph 2 | Swinging Hammer has risen to become... |
| Paragraph 3 | Give us a call today... |
| Stat 1 | 20+ / Years in Business |
| Stat 2 | 5★ / Google Rating |
| Stat 3 | 100% / Satisfaction Goal |

---

## index.html — WHY US (JavaScript `data.whyUs` array — 4 items)

Each item:
- `icon` — SVG
- `title` — e.g., "Experienced Uniformed Team"
- `desc` — Description text

---

## index.html — REVIEWS (JavaScript `data.reviews` array — 6 items)

Each review:
- `text` — Review body (contains specific service references and business name)
- `name` — Reviewer name (e.g., "E. Klett")
- `date` — Source label (e.g., "Google Review")

Also:
- Star rating display (currently 5.0)
- Rating count label ("Google Reviews")
- Google Review CTA link: https://g.page/swinginghammer

---

## index.html — FAQ (JavaScript `data.faqs` array — 6 items)

Each FAQ:
- `q` — Question text
- `a` — Answer text (some contain phone number, city, service area names)

NOTE: FAQ content should match the Schema FAQPage markup in the `<head>`.

---

## index.html — SERVICE AREAS (JavaScript `data.areas` array — 14 items)

Current list:
Houston, Katy, Sugar Land, Pearland, Missouri City, Friendswood, League City, Stafford, Richmond, Rosenberg, Bellaire, West University Place, Spring, Cypress

Also:
- Note text: "Not sure if we cover your area? Give us a call at (281) 685-8549"

NOTE: Area list should match schema `areaServed` and FAQ answer about areas.

---

## index.html — CONTACT FORM

| Element | Current Value |
|---------|--------------|
| Section title | Request a Free Estimate |
| Section subtitle | Fill out the form and we will get back to you within a few hours. |
| Service dropdown options | (must match services list — 9 services + "Other / Not Sure") |
| Submit button text | Send My Request |
| Meta line 1 | Usually responds within a few hours |
| Meta line 2 phone | (281) 685-8549 |
| Meta line 2 href | tel:+12816858549 |

---

## index.html — FOOTER

| Element | Current Value |
|---------|--------------|
| Google Maps iframe src | Google Maps embed URL for Houston, TX |
| Map iframe title | Swinging Hammer Home Repair service area — Houston, TX |
| Brand name | Swinging Hammer / Home Repair, LLC |
| Brand description | Houston's trusted handyman for over 20 years. Licensed, insured, and always on time. |
| Services list (9 links) | Must match services |
| Company links | About Us, Reviews, FAQ, Service Areas, Get a Quote, Contact (mailto) |
| Copyright text | Swinging Hammer Home Repair, LLC |
| Facebook URL | https://www.facebook.com/swinginghammer |
| Instagram URL | https://www.instagram.com/swinginghammer |
| Google Business URL | https://g.page/swinginghammer |
| Phone in footer | (281) 685-8549 |
| Email in footer | bobby@swinginghammer.com |

---

## index.html — IMAGES (files to replace)

| Image | Path | Purpose |
|-------|------|---------|
| Logo | images/hanyman_logo.png | Favicon, apple-touch-icon |
| Hero background | images/hanyman%20hero.webp | Hero section background |
| Gallery photo 1 | images/work-1.jpg | Gallery — Drywall Repair |
| Gallery photo 2 | images/work-2.jpg | Gallery — Door Installation |
| Gallery photo 3 | images/work-3.jpg | Gallery — Interior Painting |
| Gallery photo 4 | images/work-4.jpg | Gallery — Fence Repair |
| Gallery photo 5 | images/work-5.jpg | Gallery — Carpentry & Trim |
| Gallery photo 6 | images/work-6.jpg | Gallery — Fixture Install |
| Gallery photo 7 | images/work-7.jpg | Gallery — Door Frame Repair |

---

## privacy.html — UNIQUE CONTENT

| Element | Current Value |
|---------|--------------|
| `<title>` | Privacy Policy \| Swinging Hammer Home Repair, LLC |
| `meta description` | Privacy Policy for Swinging Hammer Home Repair, LLC... |
| `link canonical` | https://swinginghammer.com/privacy.html |
| Nav logo text | Swinging Hammer / Home Repair, LLC |
| Page heading | Privacy Policy |
| Last updated date | March 13, 2026 |
| Business name in body (3x) | Swinging Hammer Home Repair, LLC / "we," "us," "our" |
| Contact phone | (281) 685-8549 |
| Contact email | bobby@swinginghammer.com |
| Footer | (identical to index.html footer — same variables apply) |

---

## terms.html — UNIQUE CONTENT

| Element | Current Value |
|---------|--------------|
| `<title>` | Terms of Service \| Swinging Hammer Home Repair, LLC |
| `meta description` | Terms of Service for Swinging Hammer Home Repair, LLC... |
| `link canonical` | https://swinginghammer.com/terms.html |
| Nav logo text | Swinging Hammer / Home Repair, LLC |
| Page heading | Terms of Service |
| Last updated date | March 13, 2026 |
| Business name in body (3x) | Swinging Hammer Home Repair, LLC |
| Service description | ...handyman and home repair services in the Houston, TX metropolitan area |
| Contact phone | (281) 685-8549 |
| Contact email | bobby@swinginghammer.com |
| Footer | (identical to index.html footer — same variables apply) |

---

## SUMMARY — QUICK COUNT

| Category | # of unique fields |
|----------|--------------------|
| Business identity | 5 (name, short name, tagline, phone, email) |
| Location | 5 (city, state, lat/lng, region code) |
| URLs | 5 (website, canonical, facebook, instagram, google) |
| Meta/SEO tags | 15 (title, description, keywords, OG, twitter, geo) |
| Schema markup | ~25 fields across 3 schemas |
| Hero section | 8 (badge, heading, subtext, buttons, trust badges, image) |
| Value props | 6 (3 titles + 3 descriptions) |
| License badges | 6 (3 titles + 3 descriptions) |
| Services | 9 services x 6 fields = 54 |
| How it works | 6 (3 titles + 3 descriptions) |
| Gallery | 7 images + 7 alt texts + 7 labels = 21 |
| About | 8 (heading, 3 paragraphs, 3 stats) |
| Why Us | 8 (4 titles + 4 descriptions) |
| Reviews | 18 (6 reviews x 3 fields) + rating + review link |
| FAQs | 12 (6 questions + 6 answers) — must sync with schema |
| Service areas | 14 area names — must sync with schema |
| Contact form | 10 service dropdown options |
| Footer | 12 (brand, description, map embed, socials, phone, email) |
| Images | 9 files |
| Privacy page | 8 unique fields |
| Terms page | 8 unique fields |
| **TOTAL** | **~250+ replaceable fields** |

---

## DEVELOPER NOTES

1. **Services are the core data model.** Service names must stay in sync across: nav dropdown, services grid, form dropdown, footer list, schema hasOfferCatalog, and gallery labels. Recommend driving all of these from a single config array.

2. **FAQs appear twice.** Once in the `<head>` as Schema FAQPage JSON-LD, and once in the `data.faqs` JS array. These MUST match.

3. **Service areas appear 3 times.** In schema `areaServed`, `data.areas` JS array, and FAQ answer about areas. Keep in sync.

4. **Phone number appears 8+ times** across index.html alone. Use a global variable.

5. **Footer is duplicated** in privacy.html and terms.html with slightly different link paths (index.html# vs #). Recommend a shared footer component.

6. **Google Maps embed URL** needs to be regenerated per client city/address.

7. **Review data** should ideally be pulled from Google Business API rather than hardcoded.

8. **Image filenames** can stay generic (work-1.jpg through work-7.jpg) — just swap the actual files.
