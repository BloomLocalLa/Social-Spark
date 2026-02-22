# Project: Bloom Local Marketing / Social Spark

## Overview
Social media marketing content calendar and planning system for Bloom Local, a landscaping business in Scott, Louisiana. Contains complete Spring 2026 social media campaign (February 18 - June 15) with ready-to-post content for Facebook, Instagram, and TikTok.

## Business Information
| Field | Value |
|-------|-------|
| Company | Bloom Local |
| Owner | Brittany Domingue |
| Location | Scott, LA (Acadiana region) |
| Phone | (337) 561-8136 |
| Website | www.bloomlocal.co |
| Services | Landscaping, flower beds, mulching, outdoor living spaces |

## Key Files

| File | Purpose |
|------|---------|
| `index.html` | Interactive content calendar with all posts, copy buttons, and flagging system |
| `spring-2026-social-media-plan.md` | Source strategy document with campaign overview |

## Content Calendar Structure

### Campaign Phases
- **Phase 1 (Feb 18 - Mar 15):** Early Bird - "Spring Prep Starts Now"
- **Phase 2 (Mar 16 - Apr 30):** Spring Launch - "Transform Your Outdoor Space"
- **Phase 3 (May 1 - Jun 15):** Late Spring - "Summer-Ready Landscapes"

### Weekly Posting Schedule
| Day | Facebook | Instagram | TikTok |
|-----|----------|-----------|--------|
| Monday | Educational | Carousel/Reel | Quick tip |
| Wednesday | Before/After | Reel | Transformation |
| Friday | CTA/Service | Feed + Stories | Trending |
| Sunday | Community/BTS | Stories only | - |

## Features in index.html
- **Copy buttons:** Click to copy post content + hashtags
- **Flag system:** Mark posts for revision (persists in localStorage)
- **Sticky nav:** Quick jump to any week
- **Print/PDF:** Button to save as PDF
- **Responsive:** Works on mobile

## Instructions for Claude

### Content Guidelines
- **No discounts/promotions:** Bloom Local doesn't offer discounts - they're already affordable for the market
- **CTA focus:** Free consultations, scheduling, quality of work
- **Tone:** Professional but approachable, educational, community-focused
- **Local focus:** Acadiana, Lafayette, Scott LA references

### Brand Colors
```css
--bronze-gold: #B59663;
--slate-blue: #5B6478;
--sage-green: #A8B89A;
```

### Hashtag Sets
**Facebook (3-5):** #BloomLocal #ScottLA #LafayetteLandscaping #AcadianaGardens

**Instagram (15-20, rotate):**
- Local: #ScottLA #LafayetteLouisiana #Acadiana #SouthLouisiana
- Industry: #LandscapeDesign #OutdoorLiving #GardenTransformation
- Engagement: #BeforeAndAfter #CurbAppeal #BackyardGoals

**TikTok (3-5):** #LandscapingTikTok #GardenTok #Louisiana #SatisfyingVideos

## Local Development
```bash
# Serve the content calendar locally
npx http-server -p 5176 -c-1

# Access at
http://127.0.0.1:5176
```

## Repository
**GitHub:** https://github.com/BloomLocalLa/Social-Spark

## Related Project
This marketing folder is part of the larger Bloom Local website project at:
`C:\Users\toddo\Desktop\Bloomwebsite\`

See main project CLAUDE.md for website/backend documentation.

## Recent Activity
| Date | Activity |
|------|----------|
| 2026-02-21 | Created complete 17-week content calendar with all posts written |
| 2026-02-21 | Added flagging system for post revision tracking |
| 2026-02-21 | Removed all discount messaging per business policy |
| 2026-02-21 | Added sticky navigation and copy buttons |
| 2026-02-22 | Pushed to GitHub (BloomLocalLa/Social-Spark) |
