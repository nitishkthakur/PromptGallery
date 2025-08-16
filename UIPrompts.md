## My Version - Standard UI practices
1. When designing borders or boundary lines of neighboring elements, maintain same level for alignment if it makes sense
2. Use FLUENT UI from Micirosoft design practices, buttons, elements, fonts, font hieratchies and color themes.
3. Select elegant and professional colors. Follow the primary color, lighter version of primary and complementary color (if reqd).
4. Define 3 levels of Font Hierarchies. use Segoe font.
5. Use Alpine and HTMX for JS
6. Make the UI extremely clean and elegant for professional use. Design it keeping senior leadership in mind
7. DO not use emojis anywhere
8. Default to dark theme unless the user asks for it.
9. Implement as much functionality on the backend as possible. Only if Frontend JS is thhe clear favourite, prefer using JS for functionality.

##Follow these overall rules:
1. Think before implementing
2. Dont destroy or break existing functionality
3. For complex changes or debugging, anticipate potential issues before even trying


## Claude version
## Version 1: Complete Guidelines

### Design Perspective - Professional & Elegant UIs

#### Typography & Visual Hierarchy
- **Font System**: Use system fonts (SF Pro, Segoe UI, Roboto) or professional typefaces like Inter, Source Sans Pro
- **Hierarchy**: Establish clear type scale (H1: 32px, H2: 24px, H3: 20px, Body: 16px, Small: 14px)
- **Font Weights**: Limit to 2-3 weights maximum (Regular 400, Medium 500, Semibold 600)
- **Line Height**: Use 1.4-1.6 for body text, 1.2-1.3 for headings
- **Letter Spacing**: Subtle tracking on headings (-0.01em to 0.02em)

#### Color Strategy
- **Primary Palette**: Choose 1-2 core brand colors with 5-7 tonal variations each
- **Neutral Scale**: 7-9 carefully calibrated grays from white to near-black
- **Semantic Colors**: Success (green), warning (amber), error (red), info (blue)
- **Text Colors**: High contrast ratios (4.5:1 minimum, 7:1 preferred)
- **Background Strategy**: Subtle off-whites/grays instead of pure white

#### Layout & Spacing
- **Grid System**: 12-column responsive grid with consistent gutters
- **Spacing Scale**: Geometric progression (4px, 8px, 12px, 16px, 24px, 32px, 48px, 64px)
- **Component Padding**: Internal spacing follows spacing scale consistently
- **Section Margins**: Generous whitespace between major sections (48px-96px)
- **Container Widths**: Max-width constraints (1200px-1440px) with proper centering

#### Visual Elements
- **Borders**: 1px solid borders, subtle border-radius (4px-8px maximum)
- **Shadows**: Minimal, realistic shadows (0 1px 3px rgba(0,0,0,0.1))
- **Icons**: Consistent icon family (Heroicons, Lucide, Feather), 16px-24px sizes
- **No Decorative Elements**: Avoid emojis, excessive gradients, or playful illustrations
- **Subtle Interactions**: Gentle hover states, smooth transitions (200-300ms)

#### Content Organization
- **Information Architecture**: Clear navigation hierarchies, logical grouping
- **Data Tables**: Clean headers, alternating row colors, proper alignment
- **Forms**: Logical field grouping, clear labels, validation states
- **Cards**: Consistent padding, clear content hierarchy, subtle elevation

### Coding Perspective - Technical Implementation

#### Technology Stack
- **Default Framework**: Alpine.js for reactive behavior, HTMX for server interactions
- **CSS Strategy**: Utility-first approach (Tailwind CSS) with custom component classes
- **Progressive Enhancement**: Core functionality works without JavaScript
- **Semantic HTML**: Proper HTML5 elements, ARIA attributes for accessibility

#### Performance Optimization
- **Asset Loading**: Compress images, use WebP format, lazy loading for below-fold content
- **CSS Optimization**: Purge unused styles, critical CSS inlining
- **JavaScript**: Minimal bundle sizes, tree-shaking, async/defer loading
- **Caching Strategy**: Proper cache headers, versioned assets

#### Responsive Design
- **Mobile-First**: Design for smallest screen, progressively enhance
- **Breakpoints**: 640px (sm), 768px (md), 1024px (lg), 1280px (xl)
- **Flexible Layouts**: CSS Grid and Flexbox for adaptive components
- **Touch Targets**: Minimum 44px clickable areas on mobile
- **Content Strategy**: Hide/show content appropriately across devices

#### Cross-Browser Compatibility
- **Browser Support**: Modern browsers (Chrome, Firefox, Safari, Edge)
- **CSS Fallbacks**: Graceful degradation for newer CSS features
- **Testing**: Regular testing across target browsers and devices
- **Polyfills**: Minimal, targeted polyfills only when necessary

#### Code Quality & Maintenance
- **Component Architecture**: Reusable, self-contained components
- **State Management**: Clear data flow, minimal global state
- **Error Handling**: Graceful error states, user-friendly messages
- **Documentation**: Code comments for complex logic, component documentation
- **Accessibility**: WCAG 2.1 AA compliance, keyboard navigation, screen reader support

---

## Version 2: Essential Guidelines (Top Must-Haves)

### Design Essentials

1. **Typography Hierarchy**: Use system fonts with clear scale (H1: 32px, H2: 24px, Body: 16px) and 2-3 font weights maximum
2. **Neutral Color Palette**: Professional grays (7-9 shades) with 1-2 brand colors, ensuring 4.5:1 contrast ratios
3. **Consistent Spacing**: Geometric spacing scale (8px, 16px, 24px, 32px) applied uniformly across all components
4. **Minimal Visual Noise**: No emojis, subtle shadows (0 1px 3px rgba(0,0,0,0.1)), clean borders (1px), minimal border-radius (4-8px)
5. **Executive-Friendly Layout**: Clear information hierarchy, generous whitespace, scannable content organization

### Coding Essentials

1. **Alpine.js + HTMX**: Default stack for reactive UI and server communication with progressive enhancement
2. **Mobile-First Responsive**: CSS Grid/Flexbox with standard breakpoints (640px, 768px, 1024px, 1280px)
3. **Cross-Browser Compatibility**: Test on Chrome, Firefox, Safari, Edge with appropriate fallbacks
4. **Performance Optimization**: Compressed assets, minimal JavaScript bundles, lazy loading for images
5. **Accessibility Compliance**: WCAG 2.1 AA standards, proper ARIA attributes, keyboard navigation support

### Implementation Priority
- **Backend-First Functionality**: Implement core features server-side, enhance with frontend JavaScript
- **Semantic HTML Foundation**: Proper HTML5 structure before adding interactive enhancements
- **Component Reusability**: Build modular, self-contained UI components for consistency
