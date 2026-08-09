# Build a Premium Website for SAMMOHAK Unisex Salon

You are an expert UI/UX designer, frontend engineer, and full-stack web developer.

Build a complete, production-quality, highly polished website for **SAMMOHAK Unisex Salon**, a premium salon located in Jaipur, Rajasthan.

The website should feel like it was designed by a **top-tier luxury beauty/fashion branding agency**, not like a generic salon template.

The supplied salon PDF/menu is the primary source of truth for the business information, service names, categories, and pricing. Carefully inspect the supplied PDF before implementing the service/pricing sections.

---

## 1. BUSINESS INFORMATION

**Business Name:**  
SAMMOHAK Unisex Salon

**Tagline:**  
Elegance • Style • Perfection

**Address:**  
171/5, Sector-17,  
Haldighati Marg,  
Pratap Nagar,  
Jaipur - 302033, Rajasthan, India

**Phone:**  
+91 9119169110

**Rating:**  
4.9 / 5

**Total Reviews:**  
495

**Instagram:**  
The Instagram URL/handle has not yet been provided. Create a configurable placeholder and DO NOT invent the username.

---

# 2. CORE OBJECTIVE

The website's primary goal is:

**Convert visitors into salon appointments.**

Within approximately 5 seconds of opening the website, visitors should understand:

1. What SAMMOHAK is
2. Where it is located
3. What services it provides
4. That it has a 4.9 rating with 495 reviews
5. How to book an appointment

Primary CTA:

**Book Appointment**

Secondary CTA:

**WhatsApp Us**

Additional CTAs:

- Call Now
- Explore Services
- View Price Menu
- Get Directions
- Plan Your Bridal Look

---

# 3. DESIGN DIRECTION

Do NOT create a generic pink salon website.

Do NOT use a standard Bootstrap-looking layout.

Do NOT make it look like a cheap local-business template.

The design should combine:

- Indian luxury
- Modern editorial fashion
- Premium beauty studio
- Boutique salon
- Sophisticated minimalism

The existing SAMMOHAK branding has a strong dark brown/chocolate and gold visual identity.

Use this as inspiration but modernize it for the web.

### Primary palette

Dark Espresso:

#351B19

Deep Chocolate/Burgundy:

#4A2824

Champagne Gold:

#D6B56D

Soft Gold:

#E8D29A

Warm Ivory:

#F8F1E7

Warm Beige:

#E9D6BD

White:

#FFFFFF

Do NOT overuse gold.

Do NOT make the entire website brown.

Use approximately:

- 50–60% ivory/cream/neutral
- 20–30% dark chocolate
- 5–10% champagne gold
- remaining area for photography and white space

The overall appearance should feel expensive and calm.

---

# 4. TYPOGRAPHY

Use premium Google Fonts.

Recommended:

### Headings
Cormorant Garamond

Alternative:
Playfair Display

### Body
DM Sans

Alternative:
Inter

Use an elegant serif for major headings and clean sans-serif typography for supporting text.

Use uppercase labels with subtle letter spacing.

Optional decorative script:

Great Vibes / Allura

BUT ONLY for tiny decorative elements.

Never use script fonts for:

- paragraphs
- navigation
- prices
- buttons
- important information

Typography should resemble a luxury fashion magazine.

---

# 5. TECHNOLOGY

Use a modern production-ready stack.

Preferred:

- React
- TypeScript
- Vite
- Tailwind CSS
- Framer Motion
- Lucide React

Use reusable components.

Use clean architecture.

Keep business data separate from UI components.

Create a central configuration/data structure for:

```text
BUSINESS_NAME
TAGLINE
PHONE
WHATSAPP_NUMBER
ADDRESS
INSTAGRAM_URL
GOOGLE_REVIEWS_URL
GOOGLE_MAPS_URL
```

This should make future updates extremely easy.

---

# 6. IMPORTANT: INSPECT THE PROVIDED PDF

Before creating the pricing/service sections:

1. Inspect the supplied SAMMOHAK PDF.
2. Extract the actual service categories.
3. Extract service names.
4. Extract prices.
5. Preserve pricing accurately.
6. Do not invent services.
7. Do not invent prices.
8. Do not invent business claims.

If the PDF contains a logo or usable branding asset, use it appropriately.

The PDF is the source of truth.

---

# 7. WEBSITE STRUCTURE

Build the following sections:

1. Premium Navbar
2. Hero
3. Trust/Ratings
4. Services
5. Signature Experiences
6. About
7. Interactive Service Menu
8. Bridal & Makeup
9. Gallery
10. Instagram
11. Reviews
12. Location
13. Booking CTA
14. Footer
15. Floating WhatsApp/Booking controls

---

# 8. NAVBAR

Desktop:

Logo

Home  
Services  
Menu  
Gallery  
About  
Reviews  
Contact

Right side:

**Book Appointment**

button.

Initially the navbar can overlay the hero.

When scrolling:

- sticky navbar
- subtle backdrop blur
- ivory/dark background transition
- slight shadow
- smooth 250ms transition

Mobile:

Elegant hamburger menu.

The mobile menu should animate smoothly from the top/right.

Do not create a clumsy sidebar.

---

# 9. HERO SECTION

Create a cinematic premium hero.

Use a high-quality editorial salon/beauty image.

Prefer:

- sophisticated Indian bridal beauty
- luxury salon interior
- premium hair styling
- elegant beauty treatment

Avoid cheesy stock photography.

Hero text:

**WELCOME TO**

# SAMMOHAK

**UNISEX SALON**

Small tagline:

**Elegance • Style • Perfection**

Supporting text:

"Where beauty meets artistry, and every detail is designed around you."

Buttons:

**Book an Appointment**

**Explore Services**

Visual treatment:

- large serif typography
- editorial image
- subtle gold decorative lines
- sophisticated negative space
- cinematic image reveal
- very subtle parallax

Do NOT overload the hero with animations.

---

# 10. TRUST SECTION

Immediately after the hero:

## 4.9 / 5

★★★★★

**495 Reviews**

Text:

"Trusted by hundreds of clients in Jaipur"

Animate the number subtly when entering the viewport.

Do not fabricate additional statistics.

Add:

**Read Our Reviews**

button.

Create a configurable:

GOOGLE_REVIEWS_URL

Do not invent the URL.

---

# 11. SERVICES

Heading:

**Beauty, Styled Your Way.**

Description:

"From everyday grooming to unforgettable bridal moments, discover a complete range of salon experiences."

Create premium service cards for:

### Hair

Cuts, styling, colour and treatments.

### Skin & Facial

Facials, skin rituals and treatments.

### Makeup

Bridal, reception, engagement, party and groom makeup.

### Nails

Manicure, pedicure, gel extensions and nail artistry.

### Beauty

Beauty treatments, grooming and waxing.

### Aesthetic

Modern aesthetic treatments.

### Eyelashes

Natural, classic, hybrid, volume and open-eye extensions.

Cards should include:

- premium image
- category
- short description
- Explore button

Hover:

- image zoom
- slight card lift
- subtle gold border
- elegant shadow
- smooth 300ms transition

---

# 12. SIGNATURE EXPERIENCES

Create a visually impressive section.

Heading:

**Signature Experiences**

Show selected premium services.

Examples:

Hair:
- Keratin Treatment
- Smoothening Treatment
- Hair Botox
- Balayage
- Highlights

Skin:
- Hydra Facial
- Jeannot Facial
- O3 Facial
- Chemical Peel

Makeup:
- Bridal Makeup
- Reception Makeup
- Engagement Makeup
- Party Makeup
- Groom Makeup

Nails:
- Hard Gel Extensions
- Soft Gel Extensions
- Nail Art
- French Art
- Chrome
- Ombre

Eyelashes:
- Natural
- Hybrid
- Classic
- Volume
- Open Eye

Each item:

Service name  
Short description  
Price  
Book button

Use actual prices from the PDF.

---

# 13. INTERACTIVE SERVICE MENU

This is one of the most important parts of the website.

Do NOT dump the entire menu into one giant text block.

Build a beautiful interactive pricing system.

Desktop:

Elegant two-column layout.

Left side:

Categories

Right side:

Services and prices.

Categories:

- Hair Care – Female
- Hair Ritual
- Hair Textures
- Hair Colour
- Hair – Male
- Skin Ritual
- Facial
- Beauty – Female
- Waxing
- Pedicure
- Manicure
- Makeup
- Nail Artistry
- Aesthetic
- Eyelash Extensions

Mobile:

Use accordions.

Add filter tabs:

All  
Hair  
Skin  
Beauty  
Nails  
Makeup  
Aesthetic  
Lashes

Each service should display:

**Service Name**

**₹Price**

Optional:

Starting from  
Per sitting  
Per nail  
Per finger

depending on the PDF.

Add:

**Book This Service**

button.

Clicking it should open the booking modal with that service automatically selected.

---

# 14. MENU DATA

Use the exact pricing from the supplied PDF.

Known menu data includes:

### FEMALE HAIR CARE

Hair Wash — ₹300  
Blow Dryer — ₹300  
Hair Wash and Blow Dryer — ₹500  
Hair Cut — ₹600  
Bob Cut — ₹1000  
Hair Straightening / Curls / Tongs — ₹800  
Deep Conditioning Wash — ₹800  
Fringe / Flick — ₹300  
Baby Girl Hair Cut — ₹300

### HAIR RITUAL

L'Oreal Hair Spa — ₹1000  
Milk Shake Cocktail Hair Spa — ₹3000  
Milk Shake Moisture Plus Ritual — ₹2500  
Milk Shake Argan Ritual — ₹2500  
Milk Shake Energizing Blend Ritual — ₹2500  
Milk Shake Integrity Nourishing Ritual — ₹2500  
Ola Plex Hair Treatment — ₹3000  
Anti Dandruff Treatment — ₹2000  
Oil Head Massage — ₹600

### HAIR TEXTURES

Keratin Treatment — Starting ₹3500  
Smoothening Treatment — Starting ₹4000  
Kerasmooth Treatment — Starting ₹6000  
Hair Botox — Starting ₹5000

### HAIR COLOUR

Root Touch-Up — ₹1200  
Global Hair Colour — Starting ₹3500  
Balayage Hair Colour — Starting ₹4500  
Highlights Hair Colour — Starting ₹5000

### HAIR – MALE

Hair Cut — ₹300  
Baby Boy Cut — ₹250  
Beard Cut — ₹200  
Hair Styling — ₹200  
Shaving — ₹200  
Oil Head Massage — ₹400  
D-Tan — ₹400  
D-Tan & Cleanup — ₹1500  
Beard Colour — ₹500  
24K Gold Pack — ₹1200

### SKIN

Lotus — ₹700  
O3 — ₹1000  
D-Tan — ₹400  
Instant Skin Brightening Mask — ₹1200  
Brightening Algae Mask — ₹600  
Rebalancing Algae Mask — ₹600  
Rejuvenating Mask — ₹600

### FACIAL

Lotus Facial — ₹1500  
O3+ Facial — ₹2000  
Jeannot Instant Glow Facial — ₹3000  
Jeannot Brilliance White Facial — ₹3000  
Jeannot Hydra Boost Facial — ₹2200  
Jeannot Infinite Youth Facial — ₹2500  
Jeannot Shine Control Facial — ₹3100  
Urban Men's Facial — ₹2000  
O3 Meladerm Facial — ₹2500

### BEAUTY

Baby Polishing — ₹3500  
O3+ Body Polishing — ₹4500  
Bleach — ₹500  
Eyebrow — ₹50  
Upper Lip — ₹50  
Forehead — ₹50  
Face Wax — ₹500  
Side Locks — ₹200

### PEDICURE

Classic Pedicure — ₹600  
Nourishment Pedicure — ₹750  
D-Tan Pedicure — ₹800  
Candle Therapy Pedicure — ₹1000  
Tangled Pedicure — ₹1300  
Classic Foot Massage — ₹500

### MANICURE

Classic Manicure — ₹500  
Nourishment Manicure — ₹650  
D-Tan Manicure — ₹700  
Candle Therapy Manicure — ₹800  
Tangled Manicure — ₹1000

### MAKEUP

BRIDAL:

Air Brush — ₹21000  
HD — ₹18000  
Mineral — ₹15000

RECEPTION / ENGAGEMENT:

Air Brush — ₹15000  
HD — ₹12000  
Mineral — ₹10000

PARTY:

Air Brush — ₹7000  
HD — ₹5000  
Mineral — ₹2500

GROOM:

Air Brush — ₹5000  
HD — ₹4000  
Mineral — ₹3500

### NAIL ARTISTRY

Hard Gel Extension — ₹1200  
Soft Gel Extension — ₹900  
Gel Nail Paint — ₹500  
Nail Extension Removal — ₹300  
Gel Paint Removal — ₹300  
Nail Ombre Art — ₹500  
Nail French Art — ₹500  
Matte Coat — ₹200  
Chrome — ₹50 per nail  
Foil Art — ₹100 per nail  
Miller Art — ₹100 per finger  
Sprinkle Glitter — ₹100 per finger

Display:

"Accessories / Jewels / Rhinestones are chargeable separately."

"Toe Nail Charges are same as above."

### AESTHETIC

Chemical Peel — ₹3000  
Hydra Facial — ₹5000  
Derma Roller — ₹2000  
Comedones Extraction — ₹3000  
Face Slimming — ₹1000 per sitting  
Acne Treatment — ₹1000 per sitting

### EYELASH EXTENSIONS

Natural — ₹2500  
Hybrid — ₹3500  
Classic — ₹3500  
Volume — ₹4000  
Open Eye — ₹4000

---

# 15. WAXING TABLE

Create a premium responsive pricing table.

Columns:

Service | Normal | Rica | Peel-off

Rows:

Half Arms — ₹100 — ₹200 — —
Full Arms — ₹200 — ₹400 — —
Half Leg — ₹200 — ₹350 — —
Full Leg — ₹400 — ₹750 — —
Under Arms — ₹100 — ₹150 — ₹250
Back & Front — ₹450 — ₹800 — ₹1000
Bikini — ₹1250 — ₹1500 — ₹2000
Full Body — ₹1200 — ₹2500 — —

On mobile, convert this to stacked cards or horizontally scrollable accessible table.

Do NOT allow the table to break the mobile layout.

---

# 16. BRIDAL SECTION

Make this one of the most visually impressive areas.

Large Indian bridal editorial image.

Heading:

**Your Moment. Your Beauty. Your Signature.**

Display:

### BRIDAL

Air Brush — ₹21,000  
HD — ₹18,000  
Mineral — ₹15,000

### RECEPTION / ENGAGEMENT

Air Brush — ₹15,000  
HD — ₹12,000  
Mineral — ₹10,000

CTA:

**Plan Your Bridal Look**

Click should open WhatsApp with:

"Hello SAMMOHAK Salon, I would like to enquire about bridal makeup."

---

# 17. ABOUT

Heading:

**Where Elegance Meets Perfection.**

Copy:

"SAMMOHAK Unisex Salon brings together hair artistry, beauty, skincare, makeup and modern grooming in one refined destination in Jaipur."

Do not invent years of experience, awards, celebrity clients or unsupported achievements.

Use beautiful editorial imagery.

---

# 18. GALLERY

Build a premium masonry gallery.

Filters:

All  
Hair  
Makeup  
Nails  
Skin  
Beauty  
Bridal

Features:

- image hover zoom
- overlay
- category
- lightbox
- next/previous controls
- keyboard support
- smooth opening animation

Use consistent editorial imagery.

Prioritize Indian beauty/salon imagery.

Avoid:

- obvious low-quality stock photography
- watermarked photos
- cartoon graphics
- unrelated images

---

# 19. INSTAGRAM

Heading:

**Follow the SAMMOHAK Story**

Text:

"See our latest looks, transformations and beauty inspiration."

Button:

**Follow Us on Instagram**

Create:

```text
INSTAGRAM_URL
```

as a single configuration variable.

Do not invent the Instagram username.

If no URL is configured, show the button in a disabled/placeholder state or use a clearly marked temporary link.

---

# 20. REVIEWS

Display prominently:

## 4.9 / 5

★★★★★

**495 Reviews**

Create a sophisticated review section.

IMPORTANT:

Do NOT fabricate testimonials.

Do NOT invent customer names.

Until real review data is provided, show:

"Rated 4.9/5 by 495 customers"

CTA:

**Read Our Google Reviews**

Use:

GOOGLE_REVIEWS_URL

as a configuration variable.

---

# 21. BOOKING SYSTEM

Build a working booking modal.

Fields:

Name  
Phone  
Service  
Preferred Date  
Preferred Time  
Message

Validation:

- name required
- phone required
- service required
- date required
- time required

Button:

**Request Appointment**

Do not build a fake database booking system.

Instead, submit the booking request through WhatsApp.

WhatsApp number:

+91 9119169110

Generate:

"Hello SAMMOHAK Salon,

I would like to book an appointment.

Name: [name]
Phone: [phone]
Service: [service]
Preferred Date: [date]
Preferred Time: [time]
Message: [message]

Thank you."

Open the WhatsApp conversation using the correct WhatsApp URL format.

Also include:

Call Salon  
WhatsApp  
Get Directions

---

# 22. LOCATION

Display:

SAMMOHAK Unisex Salon

171/5, Sector-17,
Haldighati Marg,
Pratap Nagar,
Jaipur - 302033

Phone:

+91 9119169110

Buttons:

**Call Salon**

**WhatsApp**

**Get Directions**

If an exact Google Maps URL is not available, create a configurable:

GOOGLE_MAPS_URL

Do not invent coordinates.

---

# 23. MOBILE EXPERIENCE

Mobile is extremely important.

Create a fixed bottom mobile action bar:

**Call | WhatsApp | Book**

It must not cover content.

Use thumb-friendly buttons.

Mobile menu must be elegant.

Service pricing must be easy to navigate.

Booking should take minimal taps.

Do not create horizontal overflow.

Test at:

375px
390px
412px

widths.

---

# 24. DESKTOP EXPERIENCE

Test at:

1366px
1440px
1920px

Use wide editorial layouts.

Do not stretch text excessively across the screen.

Use max-width containers.

Large sections should have generous vertical spacing.

---

# 25. ANIMATIONS

Use Framer Motion.

Use:

- fade-up
- fade-in
- staggered cards
- image reveal
- subtle parallax
- text reveal
- modal transitions
- counter animation
- hover image zoom
- navigation transition

Animation principles:

Elegant  
Slow  
Subtle  
Premium

Avoid:

- bouncing
- excessive scaling
- spinning
- flashy particle effects
- animation on every element

Respect:

`prefers-reduced-motion`

---

# 26. PREMIUM MICRO-INTERACTIONS

Add:

- gold shimmer on primary CTA hover
- subtle image zoom
- animated gold divider
- elegant underline animation
- soft card elevation
- smooth menu transitions
- button press feedback

Keep everything restrained.

---

# 27. SEO

Implement:

Title:

SAMMOHAK Unisex Salon | Hair, Beauty, Makeup & Skin Salon in Jaipur

Meta description:

"SAMMOHAK Unisex Salon in Pratap Nagar, Jaipur offering premium hair, beauty, makeup, nails, skin, aesthetic and grooming services. Book your appointment today."

Add:

- Open Graph metadata
- Twitter metadata
- canonical URL placeholder
- semantic HTML
- proper heading hierarchy
- LocalBusiness / BeautySalon structured data
- address
- phone
- service categories

Use the provided rating/review information carefully.

Do not fabricate additional reviews.

---

# 28. ACCESSIBILITY

Implement:

- semantic HTML
- accessible navigation
- keyboard navigation
- focus states
- accessible modal
- accessible accordion
- alt text
- ARIA labels where needed
- sufficient contrast
- reduced-motion support

---

# 29. PERFORMANCE

Optimize:

- images
- lazy loading
- animations
- bundle size
- fonts
- layout shifts

Use responsive image sizing where practical.

Avoid loading huge images unnecessarily.

---

# 30. CODE QUALITY

Use reusable components such as:

Navbar  
Hero  
TrustBar  
ServiceCard  
ServiceGrid  
ServiceMenu  
PricingTable  
BridalSection  
Gallery  
GalleryLightbox  
ReviewSection  
BookingModal  
LocationSection  
Footer  
FloatingWhatsApp  
MobileActionBar

Keep all service/pricing data in structured arrays/objects.

Do not duplicate service markup unnecessarily.

Use TypeScript types for service data.

---

# 31. CONFIGURATION

Create one central configuration object:

```text
business.ts
```

containing:

BUSINESS_NAME
TAGLINE
PHONE
WHATSAPP_NUMBER
ADDRESS
INSTAGRAM_URL
GOOGLE_REVIEWS_URL
GOOGLE_MAPS_URL

I should be able to update business details without searching through multiple components.

---

# 32. FOOTER

Premium footer.

Include:

SAMMOHAK logo

"Elegance • Style • Perfection"

Quick Links:

Home  
Services  
Menu  
Gallery  
About  
Reviews  
Contact

Services:

Hair  
Skin  
Makeup  
Nails  
Beauty  
Aesthetic  
Lashes

Contact:

+91 9119169110

171/5, Sector-17,  
Haldighati Marg,  
Pratap Nagar,  
Jaipur - 302033

Social:

Instagram  
Facebook  
Google Reviews

Copyright.

---

# 33. IMAGE STRATEGY

Use high-quality images that match the brand.

Preferred:

- Indian bridal makeup
- premium hairstyles
- balayage
- hair colour
- nails
- skincare
- eyelash extensions
- salon interior
- men's grooming
- beauty treatments

Image style:

Warm  
Elegant  
Editorial  
Sophisticated  
High-end

Avoid:

- generic smiling stock models
- poor lighting
- overly saturated photography
- images with watermarks
- unrelated beauty images

If using external image URLs, ensure they are reliable and appropriate for production.

Where possible, make the image URLs easy to replace later.

---

# 34. FINAL QUALITY CHECK

After implementation, actually run the application.

Check every page/section.

Check:

Desktop  
Tablet  
Mobile

Test:

Navigation  
Mobile menu  
Smooth scrolling  
Service filters  
Pricing accordions  
Booking modal  
Form validation  
WhatsApp booking  
Phone button  
Gallery lightbox  
Gallery filtering  
Instagram button  
Google Reviews button  
Google Maps button

Fix:

- overflow
- broken links
- layout issues
- inconsistent spacing
- typography problems
- mobile problems
- animation glitches
- accessibility issues
- console errors

Do not leave obvious TODOs.

Do not leave lorem ipsum.

Do not invent business information.

Do not create fake testimonials.

Do not invent Instagram details.

Do not invent Google Maps coordinates.

---

# 35. MOST IMPORTANT DESIGN INSTRUCTION

The finished website should NOT look AI-generated.

It should look like a professionally art-directed luxury salon website.

Think:

**Luxury Indian beauty brand**
+
**Vogue/editorial aesthetic**
+
**Modern boutique salon**
+
**High-converting local business website**

The first impression should communicate:

**ELEGANCE**

**TRUST**

**QUALITY**

**BEAUTY**

**PROFESSIONALISM**

The website should make a potential customer want to book an appointment.

Build the actual working website now, not just a mockup.
After implementation, test the application and fix any errors you encounter.