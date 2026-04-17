# Quant Kit Landing Page Style Guide

## Brand Overview

**Quant Kit** is an email-based learning platform teaching R and data analysis to designers. We position quantitative work as a creative practice — not dry statistics, but a craft skill woven into the design process.

**Brand essence:** Bold yet accessible. Nerdy yet inviting. Professional yet quirky.

**Target audience:** Product designers, UX researchers, service designers, and design students who want to add data skills to their palette.

---

## Colour Palette

### Primary Colours

- **White:** `#FFFFFF` (backgrounds, clean space)
- **Light grey:** `#F5F5F5` (alternate sections, cards)
- **Dark grey:** `#3C3C3C` (body text)
- **Almost black:** `#1A1A1A` (headings)

### Accent Colours

- **Coral:** `#FF6B6B` ⭐ (CTAs, highlights, energy)
  - Primary use: buttons, "Data" in hero headline, key phrases, interactive elements
  - Psychology: Warm, inviting, energetic without being aggressive
- **Lighter coral:** `#FFB3B3` (hover states, subtle accents)

### Supporting Colours (from RStudio)

- **Steel blue:** `#4682B4` (code examples, technical elements)
- **Forest green:** `#228B22` (success states, checkmarks)
- **Purple:** `#9370DB` (optional, for variety)

---

## Typography

### Font Families

**Primary:** Inter (clean, modern, excellent readability)
- Headings: Inter SemiBold (600) or Bold (700)
- Body: Inter Regular (400)
- Buttons: Inter Medium (500)

**Accent/Code:** Space Mono (monospace for technical touches)
- Use sparingly for code snippets, technical notes, playful asides
- Font size: 14px typically

### Type Scale

**Desktop:**
- H1 (Hero headline): 72px, weight 700, tight line height (1.2), tight letter spacing (-0.02em)
- H2 (Section headlines): 42px, weight 600
- H3 (Sub-sections): 32px, weight 600
- H4 (Card titles): 24px, weight 600
- Body (Paragraph): 18px, weight 400, line height 1.6
- Large text (Subheadlines): 20px, weight 400
- Small text (Captions, notes): 16px or 14px

**Mobile:**
- H1: 48px
- H2: 32px
- H3: 26px
- H4: 22px
- Body: 18px (maintain readability)

### Type Treatments

- **Headings:** Black (#1A1A1A), bold (600-700), tight spacing
- **Body text:** Charcoal grey (#3C3C3C), regular weight (400)
- **Links:** Black (#000000), underlined, hover to coral (#FF6B6B)
- **Special emphasis:** Coral (#FF6B6B) for key phrases inline

---

## Layout & Spacing

### Grid & Structure

- **Max content width:** 1200px (maintains readability)
- **Section padding:** 100px top/bottom (desktop), 60px (mobile)
- **Container padding:** 24px left/right minimum
- **Element spacing:** 20-24px between paragraphs, 48px between major sections

### Section Rhythm

Alternate between white and light grey backgrounds to create visual rhythm:
- Hero: White
- Problem: Light grey (#F5F5F5)
- What is Quant Kit: White
- The Vibe: Light grey
- About: White
- CTA: Light grey
- Footer: White

### Responsive Approach

Mobile-first, fully responsive:
- Columns collapse to single column on mobile
- Generous touch targets (buttons 46px+ height)
- Maintain 18px body text on mobile (don't shrink)
- Images scale proportionally

---

## Visual Style

### Overall Aesthetic

**Bold minimalism meets playful quirks**

**Not:**
- Corporate/sterile
- Overly technical
- Generic SaaS
- Too trendy/fleeting

**Yes:**
- Clean and spacious
- Confident and approachable
- Designer-friendly
- Slightly nerdy in a charming way

### Design Principles

1. **Generous white space** - Let content breathe, don't cram
2. **Strong hierarchy** - Clear visual distinction between heading levels
3. **Subtle interactions** - Gentle hover states, smooth transitions
4. **Purposeful colour** - Coral used intentionally, not everywhere
5. **Readable first** - Prioritise legibility over decoration

---

## Components

### Buttons

**Primary CTA (Coral):**
- Background: `#FF6B6B`
- Text: `#FFFFFF` (white)
- Padding: 18px 40px
- Border radius: 10px
- Font: Inter Medium, 16px
- Shadow: `0 4px 12px rgba(255, 107, 107, 0.3)`
- Hover: Background `#E85D75`, lift 2px, increase shadow

**Secondary (Outlined):**
- Background: `#FFFFFF`
- Text: `#000000`
- Border: 2px solid `#EAECED`
- Padding: 16px 32px
- Border radius: 8px
- Hover: Background `#F5F5F5`, border `#515856`

### Cards (3-column vibe section)

- Background: `#FFFFFF`
- Border: 2px solid `#EAECED`
- Border radius: 12px
- Padding: 32px
- Transition: all 0.3s ease
- Hover: Border coral (`#FF6B6B`), lift 4px, shadow `0 8px 24px rgba(0, 0, 0, 0.1)`

### Forms

**Input fields:**
- Border: 1px solid `#EAECED`
- Border radius: 6px
- Padding: 14px 16px
- Font: Inter Regular, 16px
- Focus: Border `#FF6B6B`, shadow `0 0 0 3px rgba(255, 107, 107, 0.1)`

**Labels:**
- Font: Inter Medium, 14px
- Colour: Black (`#000000`)
- Margin bottom: 8px

**Form container:**
- Border: 2px solid coral (`#FF6B6B`)
- Border radius: 12px
- Padding: 48px
- Background: White

### Images

**Hero image placeholder:**
- Max width: 800px
- Background: Light grey gradient
- Border: 2px dashed `#EAECED`
- Border radius: 12px
- Padding: 40px

**About photo:**
- Size: 300x300px
- Border: 3px solid coral (`#FF6B6B`)
- Border radius: 12px
- Object-fit: cover

---

## Interaction & Animation

### Hover States

- **Buttons:** Darken background, lift 2px, increase shadow
- **Cards:** Border to coral, lift 4px, add shadow
- **Links:** Colour to coral (`#FF6B6B`)

### Transitions

- **Default timing:** 0.2-0.3s ease
- **Transform effects:** translateY for lifts
- **Colour transitions:** Smooth fade between states

### Scroll Behaviour

- Smooth scroll for anchor links
- Subtle fade-in animations on load (optional, not critical)

---

## Voice & Tone in Design

### Emotional Feel

**Primary emotions to evoke:**
- Confidence ("I can do this")
- Curiosity ("This looks interesting")
- Comfort ("This is for people like me")
- Excitement ("I want to start now")

**Avoid:**
- Intimidation
- Overwhelm
- Boredom
- Generic tech-bro energy

### Visual Personality

**Bold:**
- Large, confident typography (72px hero!)
- High contrast (black on white)
- Generous button sizes
- Clear hierarchy

**Quirky:**
- Coral accent (unexpected, warm)
- Space Mono for technical touches
- Honest copy ("occasional bad metaphors")
- Slightly playful micro-interactions

**Accessible:**
- 18px body text (larger than standard)
- High contrast ratios (AAA compliant)
- Clear labels and instructions
- Simple, uncluttered layouts

**Professional:**
- Clean grid system
- Consistent spacing
- Quality typography
- Refined details

---

## Content Guidelines

### Photography Style (if using images)

**Yes:**
- Real workspace/studio shots
- Authentic RStudio screenshots
- Designer-at-work moments
- Data visualisations as art
- Natural, not staged

**No:**
- Stock photos of people pointing at screens
- Overly polished corporate imagery
- Generic "diverse team in meeting"
- Cheesy technology metaphors

### Iconography

**Use sparingly:**
- Simple, clean icons if needed
- Prefer text over icons when possible

**Avoid:**
- Icon-heavy layouts
- Generic icon libraries
- Icons that need explanation

---

## Accessibility Requirements

### Colour Contrast (WCAG AA minimum)

✅ **All combinations meet AA or better:**
- Black (`#1A1A1A`) on white: 21:1 (AAA)
- Dark grey (`#3C3C3C`) on white: 8.3:1 (AAA)
- Coral (`#FF6B6B`) on white: 4.5:1 (AA for large text)
- White on coral: 4.6:1 (AA)

### Interactive Elements

- Minimum touch target: 44x44px (mobile)
- Clear focus states (coral border + shadow)
- Keyboard navigable
- Form labels properly associated

### Text

- Maintain 18px minimum for body text
- Line height 1.6 for readability
- Left-aligned (not justified)
- Sufficient colour contrast

---

## Do's and Don'ts

### Do:

✅ Use generous white space  
✅ Make coral the star accent (use intentionally)  
✅ Keep layouts clean and uncluttered  
✅ Use large, confident typography  
✅ Maintain high contrast for readability  
✅ Let content breathe  
✅ Add subtle, delightful interactions  
✅ Make mobile friendly and responsive  

### Don't:

❌ Overcrowd with elements  
❌ Use coral everywhere (loses impact)  
❌ Mix too many fonts (stick to Inter + Space Mono)  
❌ Create complex navigation (simple page structure)  
❌ Use generic stock imagery  
❌ Rely on icons to convey meaning  
❌ Make text too small (maintain 18px body)  
❌ Forget mobile experience  

---

## Technical Notes

### Implementation

- **Fonts:** Google Fonts (Inter, Space Mono)
- **Icons/Emojis:** Native system emojis, minimal custom icons
- **Animations:** CSS transitions, no heavy JavaScript
- **Forms:** MailerLite embedded forms
- **Performance:** Optimize images, minimal dependencies

### Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Graceful degradation for older browsers

---

## Inspiration & References

**Visual influences:**
- RStudio interface (clean, functional)
- Designer portfolio sites (personal, crafted)
- Modern learning platforms (accessible, clear)
- Creative studio websites (bold, confident)

**Not like:**
- Generic SaaS landing pages
- Overly corporate data platforms
- Cluttered course marketplaces
- Trendy but inaccessible designs

---

## Key Takeaway

**The landing page should feel like a confident designer talking to other designers about data — bold enough to stand out, accessible enough to feel welcoming, and quirky enough to be memorable.**

Think: "A designer's personal project that happens to be really well-crafted" not "Corporate data training platform."

---

*Last updated: February 2026*