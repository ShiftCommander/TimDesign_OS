---
name: TimDesign
colors:
  primary: '#F5F5F0'  # Paper-like white
  secondary: '#E0E0E0'  # Light gray for backgrounds
  surface: '#FFFFFF'    # Pure white for surfaces
  on-surface: '#333333'  # Dark gray for text
  error: '#FF4D4D'      # Red for error states
  outline: '#CCCCCC'    # Light gray for outlines
  muted: '#B0B0B0'      # Soft gray for muted text
typography:
  body-md:
    fontFamily: 'Mona, sans-serif'
    fontSize: '16px'
    fontWeight: '400'
  headline:
    fontFamily: 'Hubot, serif'
    fontSize: '36px'
    fontWeight: '700'
  label:
    fontFamily: 'Mona, sans-serif'
    fontSize: '14px'
    fontWeight: '500'
  monospace:
    fontFamily: 'Courier New, monospace'
    fontSize: '14px'
    fontWeight: '400'
spacing:
  base: 8  # Base unit in px
  scale: [0, 8, 16, 24, 32, 40, 48, 56, 64]  # Common steps
rounded:
  sm: 4
  md: 8
  lg: 16
motion:
  duration: 
    fast: '150ms'
    medium: '300ms'
    slow: '500ms'
  easing: 
    easeInOut: 'cubic-bezier(0.4, 0, 0.2, 1)'
shadows:
  sm: '0 1px 3px rgba(0, 0, 0, 0.1)'
  md: '0 4px 6px rgba(0, 0, 0, 0.1)'
  lg: '0 10px 15px rgba(0, 0, 0, 0.1)'
z-index:
  dropdown: 1000
  modal: 2000
  overlay: 3000
---

## Overview
TimDesign aims to create a premium web experience that embodies the essence of high-end real estate and architecture. The design language is minimalistic, airy, and light, evoking a sense of calm and luxury. The interface should feel like a curated gallery, allowing photography and whitespace to shine while guiding users toward inquiries seamlessly.

## Color system
The color palette is centered around a paper-like white as the primary color, complemented by soft grays for backgrounds and outlines. Text colors are chosen for high readability against these surfaces, adhering to WCAG standards for contrast. Use the primary color for backgrounds and secondary for surfaces, ensuring sufficient contrast for text.

## Typography
The typography hierarchy emphasizes elegance and legibility. Use the 'Hubot' serif font for headlines to convey sophistication, while 'Mona' serves as the body font for clarity. Maintain consistent font sizes and weights to create a clear visual hierarchy, ensuring that headlines stand out without overwhelming the content.

## Layout & spacing
The layout should prioritize whitespace and alignment, creating a spacious feel. Use a grid system that adapts responsively, maintaining consistent margins and padding based on the defined spacing scale. Ensure that all components are designed to be reusable in Webflow, with clear class naming conventions for easy implementation.

## Components
- **Buttons**: Primary and secondary variants with hover and pressed states.
- **Inputs**: Clear and concise fields with labels, maintaining accessibility.
- **Cards**: Image-led project cards with subtle hover effects.
- **Nav**: Light integrated navigation with creative interaction states.
- **Footers**: Calm and concise, providing essential links and contact information.
- **Forms**: Intuitive contact forms with clear labels and error handling.

## Motion & interaction
Keep motion minimal and purposeful. Use subtle transitions for hover states and interactions, respecting user preferences for reduced motion. Ensure that all animations are lightweight and enhance the user experience without overwhelming the content.

## Do's and Don'ts
- **Do**: Use ample whitespace to create a calm layout.
- **Do**: Ensure all images are intentionally cropped and aligned.
- **Don't**: Overload the interface with heavy graphics or animations.
- **Don't**: Use dark luxury clichés or overly decorative elements.

## Starter checklist
- Validate color contrast ratios against WCAG guidelines.
- Ensure typography is legible across all devices.
- Check that all components are reusable in Webflow.
- Confirm responsive behavior on mobile and desktop.
- Test interactions for accessibility and performance.
