# Somatic Experience Landing Page - Specification

## 1. Project Overview

**Project Name:** Somatic Experience Landing Page  
**Project Type:** Single-page website with booking functionality  
**Core Functionality:** A calming, immersive landing page for somatic experience therapy sessions with booking capabilities  
**Target Users:** Individuals seeking somatic therapy, bodywork, or mindfulness sessions

---

## 2. UI/UX Specification

### Layout Structure

**Page Sections (in scroll order):**
1. **Hero Section** - Full viewport height, introduction with calming imagery
2. **About Section** - What is somatic experience
3. **Benefits Section** - Why choose somatic work
4. **Services/Pricing Section** - Available session types
5. **Booking Section** - Calendar and booking form
6. **Footer** - Contact info and social links

**Responsive Breakpoints:**
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

### Visual Design

**Color Palette:**
- Primary Background: `#F5F2ED` (warm off-white/cream)
- Secondary Background: `#E8E2D9` (warm beige)
- Primary Text: `#3D3A35` (deep warm charcoal)
- Secondary Text: `#6B6560` (muted brown-gray)
- Accent Color: `#8B7355` (warm earth brown)
- Accent Light: `#A69580` (light taupe)
- Accent Highlight: `#C4B59D` (sand)
- Nature Green: `#7A8B6E` (muted sage green)
- Deep Earth: `#5C4F42` (dark brown)

**Typography:**
- Headings: "Cormorant Garamond", serif (elegant, calming)
- Body: "Nunito Sans", sans-serif (soft, readable)
- Accent/Quotes: "Cormorant Garamond", italic
- H1: 3.5rem / 56px
- H2: 2.5rem / 40px
- H3: 1.75rem / 28px
- Body: 1.125rem / 18px
- Small: 0.875rem / 14px

**Spacing System:**
- Section padding: 120px vertical
- Container max-width: 1200px
- Element spacing: 24px / 32px / 48px
- Border radius: 8px (soft, gentle)

**Visual Effects:**
- Subtle paper texture overlay on backgrounds
- Soft shadows: `0 4px 30px rgba(61, 58, 53, 0.08)`
- Organic, flowing shapes as decorative elements
- Parallax scrolling on hero imagery
- Fade-in animations on scroll (staggered)
- Smooth scroll behavior throughout

### Components

**Navigation:**
- Fixed top navigation, transparent initially
- Background becomes warm cream on scroll
- Logo/name on left, nav links on right
- Mobile: hamburger menu with slide-in panel

**Hero Section:**
- Full viewport background image (nature abstract texture)
- Centered headline and subtext
- Gentle scroll indicator at bottom
- Overlay gradient for readability

**Cards (Benefits/Services):**
- Soft rounded corners
- Subtle shadow
- Icon or small imagery
- Hover: gentle lift effect

**Booking Calendar:**
- Monthly view calendar grid
- Available dates highlighted in sage green
- Selected date shows accent color
- Navigation arrows for month switching
- Time slot selection below calendar

**Booking Form:**
- Name, email, phone fields
- Session type dropdown
- Notes/textarea
- Submit button with loading state
- Success message modal

**Buttons:**
- Primary: Earth brown background, cream text
- Secondary: Transparent with brown border
- Hover: Subtle color shift, gentle scale
- Active: Slight pressed effect

---

## 3. Functionality Specification

### Core Features

1. **Smooth Scrolling**
   - All internal links scroll smoothly
   - Scroll-triggered animations for sections
   - Parallax effect on hero

2. **Navigation**
   - Sticky navigation with background change on scroll
   - Active section highlighting
   - Mobile hamburger menu

3. **Booking Calendar**
   - Display current month with navigation
   - Click to select available dates
   - Show available time slots
   - Form validation

4. **Booking Form**
   - Client information collection
   - Session type selection
   - Date/time confirmation
   - Form validation with error messages
   - Success confirmation

5. **Animations**
   - Fade-in-up on scroll for sections
   - Staggered animation for cards/lists
   - Subtle floating elements
   - Smooth transitions on interactions

### User Interactions

- Click nav links → smooth scroll to section
- Scroll → trigger section animations, change nav
- Click calendar date → select and show time slots
- Click time slot → highlight selection
- Submit form → validation → success message

### Edge Cases

- Invalid date selection handling
- Form validation errors
- Mobile touch interactions
- Reduced motion preference support

---

## 4. Acceptance Criteria

- [ ] Page loads with smooth hero animation
- [ ] Navigation becomes sticky with background on scroll
- [ ] All sections have scroll-triggered fade animations
- [ ] Calendar displays and allows date selection
- [ ] Time slots appear when date is selected
- [ ] Booking form validates required fields
- [ ] Success message shows on form submission
- [ ] Responsive on mobile, tablet, desktop
- [ ] All colors match specification
- [ ] Typography matches specification
- [ ] Nature imagery with abstract texture visible
- [ ] Overall feel is calm, safe, grounded
