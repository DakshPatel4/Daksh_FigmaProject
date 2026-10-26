# Olive & Ember — Restaurant Website Design

## Project Overview
**Olive & Ember** is a modern, warm, and welcoming restaurant website concept. This README documents the visual direction and page structure so the design can be recreated or organized in **Figma**.

> This is a frontend/design concept. Online ordering, payments, and reservations are demo interactions only.

## Design Goals
- Make the restaurant feel welcoming, premium, and approachable.
- Showcase food photography and menu prices clearly.
- Help visitors quickly browse the menu and find reservation details.
- Keep the experience responsive across desktop, tablet, and mobile.

## Visual Style
- **Brand personality:** warm, natural, handcrafted, contemporary.
- **Primary color:** Terracotta `#BB4A2F`
- **Secondary color:** Deep forest green `#213A2D`
- **Page background:** Warm ivory `#FAF6EF`
- **Card surface:** Soft white `#FFFDF8`
- **Main text:** Dark charcoal `#29271F`
- **Muted text:** Warm gray `#766F64`
- **Borders:** Sand `#E8DFD2`
- **Heading typeface:** Georgia / elegant serif
- **Body typeface:** Inter or a similar clean sans-serif
- **Shapes:** Rounded pills for buttons and filters; softly rounded cards.
- **Photography:** Large, appetizing food photos with warm natural lighting.

## Figma File Setup
Create a Figma design file named **Olive & Ember — Restaurant Website**. Suggested pages:

1. **Cover** — Project title, palette, and design preview.
2. **Desktop Website** — Main website at 1440 px wide.
3. **Tablet Website** — Responsive layout around 768 px wide.
4. **Mobile Website** — Mobile layout around 390 px wide.
5. **Components** — Buttons, navigation, menu cards, filters, form fields, and cart elements.
6. **Styles** — Color and typography styles.

This README describes the design system; it does not itself create or export a `.fig` file.

## Website Sections

### 1. Announcement Bar and Navigation
- Announcement: “A little taste of something wonderful · Open daily 11 AM – 10 PM”
- Brand mark and **olive & ember** wordmark.
- Navigation links: Home, Our Menu, Our Story, Reservations.
- Order button with a cart item count.

### 2. Hero Section
- Eyebrow: “Good food, good mood”
- Main headline: “Made with love. Served with flavour.”
- Short restaurant introduction.
- Primary CTA: **Explore the menu**
- Secondary CTA: **Our little story**
- Social proof: guest rating, fresh ingredients, and “Since ’18”.
- Large food photograph with decorative freshness badge and floating note.

### 3. Menu Section
- Section heading: “Something for every craving.”
- Filter chips: All dishes, Starters, Mains, Pizza, Desserts, Drinks.
- Responsive food-card grid.
- Each card includes a food image, item name, description, rating, category, price in Indian rupees, and add button.

#### Sample Menu and Prices
| Item | Category | Price |
|---|---|---:|
| Burrata & Tomatoes | Starters | ₹249 |
| Golden Arancini | Starters | ₹199 |
| Garden Pesto Pasta | Mains | ₹349 |
| Wild Mushroom Risotto | Mains | ₹399 |
| Margherita Classic | Pizza | ₹299 |
| Roasted Veggie Pizza | Pizza | ₹349 |
| Tiramisu Cloud | Desserts | ₹199 |
| Berry Cheesecake | Desserts | ₹179 |
| Citrus Fizz | Drinks | ₹129 |
| Iced Vanilla Latte | Drinks | ₹149 |

### 4. Our Story Section
- Restaurant photograph.
- Heading: “More than a meal. It’s a feeling.”
- Short brand story.
- Feature list: Seasonal & fresh, Made with love, Locally inspired, Come together.

### 5. Reservation Section
- Deep green background with contrasting light text.
- Heading: “Good times are better around a table.”
- Form fields: name, email, date, guests, and optional note.
- CTA: **Request a table**.
- The prototype displays a demo message and does not submit a real reservation.

### 6. Footer
- Brand wordmark and short tagline.
- Quick links to Menu, Our Story, and Contact & Bookings.
- Copyright / demo label.

### 7. Cart Drawer
- Slides in from the right.
- Displays selected food items, quantities, item prices, and estimated total in ₹.
- Supports quantity increase/decrease.
- Checkout is a demo only; no payment or order is processed.

## Components to Create in Figma
- Announcement bar
- Header / navigation
- Primary and secondary buttons
- Eyebrow label
- Hero food image frame
- Rating and statistic blocks
- Menu filter chips (default, active, hover)
- Food menu card
- Add-to-cart button
- Reservation input, select, and form button
- Restaurant feature / perk row
- Footer
- Cart drawer and quantity controls
- Toast notification

Use **Auto Layout** for navigation, buttons, cards, form rows, and footer groups. Use component variants for button states, active filters, and cart states.

## Responsive Layout Guidance
- **Desktop (1440 px):** two-column hero and story sections; four-column menu grid.
- **Tablet (768 px):** compact navigation; two-column menu grid; reduced section spacing.
- **Mobile (390 px):** stacked hero and story; compact navigation; two-column menu cards where readable, switching to one column on very narrow screens; reservation form stacked vertically.

## Accessibility Notes
- Maintain readable text contrast on terracotta and green backgrounds.
- Give food images descriptive alt text.
- Keep interactive targets large enough for touch.
- Show active menu filters clearly.
- Label every reservation field and provide visible focus states in the final implementation.

## Assets
The website prototype references food and restaurant photos from Unsplash. For a Figma handoff, place properly licensed image assets in the Figma file and keep image credits/licensing details where required. An internet connection is needed for the remote photos in the current HTML prototype.

## How to Use This README
1. Create the Figma pages listed above.
2. Define the colors and typography as shared styles.
3. Build reusable components before laying out the full pages.
4. Recreate desktop first, then adapt the same components for tablet and mobile.
5. Add prototype links for the navigation, menu filters, cart drawer, and reservation CTA.
6. Compare the final Figma frames with the HTML website and keep spacing, colors, and labels consistent.

## Project Scope
- **Included:** visual design guidance, responsive page plan, menu content, and frontend concept.
- **Not included:** a native Figma `.fig` file, backend, database, live reservation system, payment processing, or real order submission.
