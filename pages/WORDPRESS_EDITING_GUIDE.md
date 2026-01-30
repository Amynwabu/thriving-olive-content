# WordPress Editing Guide - Thriving Olive Home Page

## Quick Summary

You now have a GitHub repository (`thriving-olive-content`) that serves as your **source of truth** for all page content. The improved copy and structure are in `pages/home.md`.

**Workflow:**
1. When you need to update content, edit `pages/home.md` in GitHub first
2. Commit your changes with a clear message (e.g., "Refine hero section copy")
3. Then update the WordPress page to match
4. This keeps your source and live site in sync

---

## Key Improvements Made

### 1. Hero Section
- **Added**: Outcome promise statement
- **Changed**: "A transformational 12-week group coaching for..." to "A transformational 12-week group coaching **program** for..."
- **New subheading**: "Reset emotionally. Realign spiritually. Thrive without apology."

### 2. Pricing Section
- **Clearer formatting**: Fast-action discount is now more prominent
- **Removed confusion**: All currency options (GBP/NGN) are clear

### 3. Content Bullets
- **Fixed formatting**: Split lines like "E book on productivity and Living / Purposefully" are now on single lines
- **Professional tone**: Benefit-focused language throughout

### 4. Testimonials
- **Added locations**: Each testimonial now includes where the person is from (UK, Nigeria, Ghana)
- **Better credibility**: Makes social proof more authentic

### 5. Footer / Contact
- **Fixed address**: Removed confusing "NY 10002" postal code (kept UK-only)
- **Clear phone format**: +44 (0)7 569-9859

---

## How to Edit in WordPress

### Option A: Edit in the Visual Block Editor (Recommended for beginners)

1. **Go to WordPress Admin**: https://thrivingolive.com/wp-admin/
2. **Navigate to Pages**: Click "Pages" in the left sidebar
3. **Find "Home - Front Page"**: Scroll down and click the row to expand it
4. **Click "Edit"**: Opens the page editor
5. **For each section** (hero, pricing, "what's inside", etc.):
   - Find the text block in the editor
   - Click it to select
   - Delete the old text
   - Paste the new text from `pages/home.md`
   - The section will update visually
6. **Click "Save"** (green button, top right) to save changes

### Option B: Edit via Quick Edit (Fastest for text-only changes)

1. **Pages list**: https://thrivingolive.com/wp-admin/edit.php?post_type=page
2. **Hover over "Home - Front Page"**
3. **Click "Quick Edit"**
4. **Make text changes** in the modal that appears
5. **Click "Update"**

### Option C: Edit in Code Editor (For advanced users)

1. In the page editor, click the three-dot menu (top right)
2. Look for "Code Editor" or "HTML" option
3. You can see and edit the raw block HTML directly
4. Useful for fixing formatting issues

---

## Priority Edits (Do These First)

### 1. Hero Section
**Current text** (to find/replace):
```
A transformational 12-week group coaching for high-achieving women
of faith who are tired of pretending they're fine, and ready to finally feel whole again.
```

**New text** (paste this):
```
A transformational 12-week group coaching program for high-achieving women of faith who are tired of pretending they're fine, and ready to finally feel whole again.

Reset emotionally. Realign spiritually. Thrive without apology.
```

### 2. Fix Bonus E-books
**Current** (search for):
```
E book on productivity and Living
Purposefully (Wing Life Like A Champ)
```

**New** (replace with):
```
E-book: Productivity and Living Purposefully (Wing Life Like A Champ)
```

Do the same for the stress management e-book.

### 3. Fix Address
**Current**:
```
177 Garden St
Scotland UK, NY 10002
```

**New**:
```
177 Garden St
Scotland, UK
```

### 4. Add Locations to Testimonials

**For each testimonial**, add the location after the person's name:

**Esther** → **Esther, UK**
**Ruth** → **Ruth, Nigeria**
**Dr. Ebehi** → **Dr. Ebehi, Ghana**

---

## Testing Your Changes

After you save changes in WordPress:

1. **View the live site**: Click "View Page" button in the editor, or go to https://thrivingolive.com/
2. **Check on mobile**: Use browser DevTools (F12) or a phone to test
3. **Look for**:
   - Correct spacing between sections
   - No orphaned "- " characters
   - Bullets displaying properly
   - Contact info is accurate
   - Testimonials have names + locations

---

## If Something Looks Wrong

**Blocks not rendering visually?**
- Refresh the page (Cmd+R or Ctrl+R)
- Try the Code Editor to see the HTML
- Clear browser cache if it persists

**Text formatting broken?**
- Copy from `pages/home.md` and paste as plain text (not rich text)
- Use WordPress's "Paste as Text" option if available

**Need to revert changes?**
- WordPress has a "Revisions" feature
- Click the clock icon or "Revisions" button in the editor
- Restore a previous version

---

## Next Steps After Initial Edit

1. ✅ **Update all sections** in WordPress to match `pages/home.md`
2. **Test the live site** on desktop and mobile
3. **Create a checklist** of other improvements:
   - Brand colors (primary, accent, neutral)
   - Typography (font sizes, weights)
   - Spacing and padding between sections
   - Image optimization
   - Theme updates (consider Astra Pro for more design control)
4. **Consider design polish**:
   - Hero image quality and sizing
   - Button styling consistency
   - Icon upgrades
   - Form styling
5. **Plan next phase**:
   - Mobile responsiveness
   - Contact form optimization
   - Analytics setup
   - SEO optimization

---

## GitHub Workflow Reminder

**Every time you update the site:**

1. Edit `pages/home.md` in GitHub
2. Write a clear commit message (e.g., "Update pricing section copy for clarity")
3. Commit to main branch
4. Update WordPress to match
5. Test on the live site

This keeps your source of truth (GitHub) and live site (WordPress) in perfect sync.

---

## Resources

- **WordPress Block Editor Help**: https://wordpress.org/documentation/article/blocks/
- **Thriving Olive Repo**: https://github.com/Amynwabu/thriving-olive-content
- **WordPress Admin**: https://thrivingolive.com/wp-admin/
- **Live Site**: https://thrivingolive.com/

---

*Last updated: January 30, 2026*
