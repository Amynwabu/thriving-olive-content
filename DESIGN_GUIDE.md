# Thriving Olive - Design & Visual Elements Guide

## Hero Section Enhancements

This guide documents the visual design improvements made to the Thriving Olive home page hero section.

---

## ✅ COMPLETED: Glowing Box Shadow Effect

### What Was Added
A glowing box shadow effect has been applied to the hero section container to create a premium, luminous appearance.

### Technical Details
**Shadow Properties:**
- **Color**: Gold/Amber (#DC882470) - matches the "RESET TO THRIVE" headline color
- **Blur**: 88px - creates soft, diffused glow
- **Spread**: 48px - extends glow outward
- **X Offset**: 0 - centered horizontally
- **Y Offset**: 0 - centered vertically
- **Opacity**: Alpha channel at 0.70 for transparency

### How to Verify
1. Go to WordPress Admin: `/wp-admin/post.php?post=2778&action=edit`
2. Select the hero container block
3. Open **Settings** → **Block** → **Style**
4. Expand **Box Shadow** section
5. You'll see the gold glow settings applied

### Where to Edit
- **Path**: Hero Container Block → Style Tab → Box Shadow → Normal
- **Color Picker**: Currently set to #DC882470
- **Blur/Spread Sliders**: Blur=88, Spread=48

---

## TODO: Transparent Logo on Hero

### What Needs to Be Done
Add a transparent logo image to the hero section for brand consistency and visual impact.

### Design Specifications

**Logo Requirements:**
- **Format**: PNG with transparent background
- **Size**: 200-300px width (responsive)
- **Opacity**: 15-20% transparency (semi-transparent white or brand color)
- **Position**: Top-right or center-right of hero
- **Color**: White or light gold with transparency
- **Style**: Elegant, minimal, matches the coaching aesthetic

### Implementation Steps

#### Option 1: Use Existing Logo (If Available)
1. WordPress Admin → Home Page Editor
2. Inside hero container, click "Add Block"
3. Select **Image** block
4. Click **Media Library**
5. Select logo image
6. Set image width to 250px
7. Set opacity/blend mode in image settings
8. Position and align as needed

#### Option 2: Create/Upload New Logo
1. **Prepare logo file**:
   - Design or find a logo (PNG with transparency)
   - Size: 500x500px or larger (will be scaled down)
   - Filename: `thriving-olive-logo.png`

2. **Upload to WordPress**:
   - WordPress Admin → Media → Add New
   - Drag & drop the PNG file
   - Click "Upload"

3. **Add to Hero Section**:
   - Home Page Editor → Click inside hero container
   - Click "Add Block" → select "Image"
   - Click "Media Library"
   - Select the logo you just uploaded
   - Configure settings (see below)

### Image Block Settings

Once the logo image is inserted:

1. **Click the image** to select it
2. **Open Settings** (right panel)
3. **Under Style tab**, configure:
   - **Width**: Set to 20% or 250px
   - **Height**: Auto (maintains aspect ratio)
   - **Opacity**: Lower to 15-20% for transparency
   - **Alignment**: Center or Right

4. **Optional CSS Class** (for advanced styling):
   - Add class like `hero-logo` if custom styling needed

### CSS for Semi-Transparent Effect

If you need to add custom CSS opacity, add to theme custom CSS:
```css
.hero-logo {
  opacity: 0.18;
  mix-blend-mode: screen; /* Optional: blends logo nicely */
}
```

---

## Hero Section Current Design

### Colors
- **Primary Overlay**: Teal/Dark Green (rgba from background blend)
- **Headline "RESET TO THRIVE"**: Gold/Amber (#D4A574 approx)
- **Subheading Text**: Light tan/cream
- **Glow Effect**: Gold/Amber (#DC882470)
- **Background**: Coaching scene photo with gradient overlay

### Fonts & Typography
- **Headline**: Large, bold, uppercase
- **Subheading**: Medium weight, readable
- **Button**: "Register Now" in teal/green

### Layout
- **Hero Height**: ~1000px (full screen on desktop)
- **Content Centered**: Text and button centered
- **Image Position**: Default (center)
- **Responsive**: Adapts to mobile devices

---

## Next Steps

1. **Prepare Logo**: Create or source a transparent logo PNG
2. **Upload to WordPress**: Media library
3. **Insert in Hero**: Add image block inside hero container
4. **Configure Opacity**: Set to 15-20%
5. **Test on Mobile**: Ensure it looks good on all screen sizes
6. **Adjust Position**: Move if needed for better balance
7. **Update Documentation**: Document any custom CSS used

---

## Brand Color Palette Reference

| Element | Color | Hex Code | Usage |
|---------|-------|----------|-------|
| Primary Headline | Gold/Amber | #D4A574 | "RESET TO THRIVE" |
| Glow Effect | Gold/Amber | #DC882470 | Box shadow on hero |
| Overlay | Teal/Green | Custom | Background blend |
| Text (Light) | Cream | #E8D4C0 | Subheadings |
| Button | Teal | #2B7A78 | CTA elements |

---

## Testing Checklist

- [ ] Glowing shadow visible on hero (desktop view)
- [ ] Glowing shadow visible on hero (mobile view)
- [ ] Logo displays (once added)
- [ ] Logo is transparent/semi-transparent
- [ ] Logo positioned correctly
- [ ] Logo doesn't overlap important text
- [ ] Logo responsive on mobile
- [ ] Glow color complements logo
- [ ] Overall premium feel achieved
- [ ] Text readability not compromised

---

## Resources

- **WordPress Editor**: https://thrivingolive.com/wp-admin/post.php?post=2778&action=edit
- **Live Hero Section**: https://thrivingolive.com/ (scroll to top)
- **Brand Guidelines**: See BRAND_COLORS.md (to be created)

---

*Last updated: January 30, 2026*
