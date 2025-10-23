# Shopify Custom Sections Portfolio

A collection of production-ready custom Shopify sections built with Liquid, CSS3, and JavaScript. Each section is fully customizable through the Shopify theme editor.

## Sections Included

### 1. Advanced Hero
Premium hero section with video backgrounds, parallax scrolling, and smooth animations.

**Features:**
- Video backgrounds (YouTube/Vimeo) with mobile fallback
- Parallax scrolling effect
- Gradient overlay with customizable colors
- Fade-up animations on page load
- Animated scroll indicator
- Multiple button styles (primary, secondary, outline)
- Block-based content system
- Fully responsive

**Tech:** Shopify Liquid, CSS3, JavaScript  
**Location:** `/advanced-hero/advanced-hero.liquid`

---

### 2. Product Grid
Multi-column product grid with animations, filtering, and customizable layouts.

**Features:**
- 2-5 column layouts (client controls)
- Staggered fade-in animations
- Image hover effects
- Automatic sale badge display
- Price display with sale strikethrough
- Collection selector (choose which products to display)
- Customizable colors for all elements
- Mobile responsive (1-2 columns mobile, up to 5 desktop)

**Tech:** Shopify Liquid, CSS3  
**Location:** `/product-grid/product-grid.liquid`

---

### 3. Testimonial Carousel
Interactive carousel for displaying customer testimonials with ratings and author info.

**Features:**
- Smooth carousel with prev/next navigation
- Click-to-navigate dot indicators
- Star ratings (1-5 stars)
- Author images with fallback backgrounds
- Block-based system (add unlimited testimonials)
- Auto-rotate option (optional)
- Fade-in animations
- Mobile responsive

**Tech:** Shopify Liquid, CSS3, JavaScript  
**Location:** `/testimonial-carousel/testimonial-carousel.liquid`

---

### 4. Before/After Slider
Interactive image comparison slider for showcasing transformations.

**Features:**
- Draggable slider handle for image comparison
- Click anywhere to jump positions
- Touch support for mobile devices
- Custom before/after labels
- Smooth clip-path transitions
- Optional additional description
- Visual button indicator
- Fade-in animations

**Tech:** Shopify Liquid, CSS3, JavaScript  
**Location:** `/before-after-slider/before-after-slider.liquid`

---

## Installation

### Option 1: Copy Individual Sections
1. Download the section file (e.g., `advanced-hero.liquid`)
2. In Shopify admin: Online Store → Themes → Edit code
3. Go to Sections folder
4. Create new section and paste the code

### Option 2: Using Shopify CLI
```bash
shopify theme pull --store=your-store.myshopify.com
# Copy section files to your /sections/ folder
shopify theme dev --store=your-store.myshopify.com
```

---

## Customization

Each section includes full theme editor controls for:
- **Colors** - Headings, text, buttons, backgrounds, overlays
- **Layout** - Column counts, heights, spacing
- **Typography** - Font sizes, alignment
- **Animations** - Enable/disable parallax, adjust speeds
- **Content** - Via block system (easy for non-technical users)

All changes are real-time in the theme editor.

---

## Features Across All Sections

✅ Smooth animations and transitions  
✅ Mobile-first responsive design  
✅ Performance optimized  
✅ Accessibility compliant (WCAG)  
✅ Respects `prefers-reduced-motion`  
✅ Full theme editor customization  
✅ No external dependencies  
✅ Clean, documented code  

---

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

---

## Performance

All sections are optimized for:
- Fast load times
- Minimal CSS/JS
- Lazy loading where applicable
- Efficient animations (using `transform` and `opacity`)
- No render-blocking scripts

---

## Code Quality

- Clean, readable Liquid code
- Semantic HTML
- Modern CSS (CSS Grid, Flexbox)
- Vanilla JavaScript (no jQuery)
- Comprehensive inline comments
- BEM-style class naming

---

## Screenshots

See individual section folders for screenshots showing:
- Desktop previews
- Mobile previews
- Theme editor customization options
- Animation examples

---

## Support

Each section is self-contained and can be used independently. No dependencies between sections.

For questions about implementation or customization, refer to the Shopify theme development documentation.

---

## License

These sections are provided as portfolio examples.

---

## Author

Abdul Khaliq  
Shopify Theme Developer | React Developer

**Links:**
- GitHub: https://github.com/Abdul102-ux
- Upwork: https://www.upwork.com/freelancers/~01592be08464fa6112?mp_source=share

---

## Changelog

### v1.0 (Current)
- Advanced Hero Section
- Product Grid Section

### v1.1 (Upcoming)
- Testimonial Carousel Section
- Before/After Slider Section