# Zero-Touch Website Business - Strategic Direction 2026

## Executive Summary

**Problem:** Current Shan Tech pricing (£19-39/mo) struggles against loss-leader competitors like Bluehost (£1.49/mo). Manual work for low margins isn't sustainable.

**Solution:** Fully automated AI-powered website generation pipeline where customers self-serve and systems handle everything.

**Business Model:** Volume play at £9.99/mo with near-zero marginal costs.

---

## The Core Concept

**Fully automated pipeline:**
```
Customer fills form → AI generates site → Auto-deploys → Stripe bills → You do nothing
```

**Economics at scale:**
| Customers | Monthly Revenue | Your Time |
|-----------|-----------------|-----------|
| 100 | £999 | 2 hrs/week |
| 500 | £4,995 | 2 hrs/week |
| 1,000 | £9,990 | 3 hrs/week |

---

## Tech Stack

```
Customer Form (Typeform/Tally)
       ↓
n8n Automation Hub
       ↓
Claude API → Generates content
       ↓
Astro Template → Injects content
       ↓
GitHub API → Creates repo
       ↓
Vercel → Auto-deploys (FREE hosting)
       ↓
Stripe → £9.99/mo billing
       ↓
AI Chatbot → Handles support
```

**Cost per site:** ~£0.30 one-time (Claude API)
**Hosting per site:** £0 (Vercel free tier)
**Profit per site:** ~£9.50/mo

---

## Competitive Advantage

| Free Website Guys Model | Our Model |
|-------------------------|-----------|
| One-time affiliate commission (£65) | Recurring revenue (£9.50/mo × forever) |
| Customer locked to Bluehost | Customer on YOUR platform |
| They disappear after sale | You build an asset |
| Need constant new leads | Existing customers compound |

**After 12 months with 100 customers:**
- Them: £6,500 (one-time, gone)
- Us: £1,140/mo ongoing = £13,680/year AND still growing

---

## The Pipeline in Detail

### Step 1: Landing Page
> "Professional Website in 60 Seconds - Free Preview"

### Step 2: Quiz (5 questions)
- Business name?
- Industry? (Salon, Café, Tradesperson, etc.)
- Phone number?
- Pick a color theme
- Upload logo (optional)

### Step 3: AI Generation (Behind scenes)
```
Claude prompt:
"Generate website content for a {industry} called {name}:
- Hero headline (8 words max)
- Tagline (15 words)
- About section (50 words)
- 4 services with descriptions
- Call to action
- Testimonial (realistic, first name only)"
```

### Step 4: Preview
> "Here's your website! Love it? £9.99/mo to publish."

### Step 5: Payment → Auto-deploy → Done

---

## Three Strategic Paths

### Path A: Pure Volume Play (New Brand)

**Separate from Shan Tech:**
- New brand: "60SecondSites" or "InstantWeb"
- £9.99/mo, fully automated
- Target: UK-wide (not just Milton Keynes)
- Goal: 500+ customers

**Pros:** Truly passive, scalable
**Cons:** Competitive, low margins, need marketing spend

---

### Path B: AI-Assisted Premium (Enhance Shan Tech)

**Keep Shan Tech, but use AI internally:**
- AI generates draft site in 2 minutes
- You polish for 15-30 minutes
- Charge £19-29/mo (human-reviewed quality)
- Customers think you built it manually

**Pros:** Higher margins, less volume needed, quality control
**Cons:** Still requires your time (but 90% less)

---

### Path C: Freemium Funnel (Hybrid)

**Free AI sites → Upsell to premium:**
- Truly free basic site (costs you nothing on Vercel)
- Footer: "Upgrade for booking, AI chat, custom domain"
- Convert 10-20% to £29-99/mo plans

**Pros:** Massive lead generation, best of both worlds
**Cons:** More complex, need to manage two tiers

---

## Recommended Approach

### Phase 1: Quick Win (Path B)
1. Build the AI pipeline (2-3 weeks)
2. Use it to create Shan Tech sites in minutes
3. Your cost per site: ~£0.30
4. Your time per site: 30 mins instead of 5-10 hours
5. Immediate profit margin improvement

### Phase 2: Experiment (Path A)
1. Launch separate automated brand
2. £9.99/mo, zero touch
3. Spend £200/mo on Facebook ads
4. See if unit economics work
5. If yes → scale. If no → you learned for £200.

---

## Build Timeline

| Week | Task |
|------|------|
| 1 | Create 3 Astro templates (salon, café, tradesperson) |
| 2 | Set up n8n + Claude API integration |
| 3 | Connect to GitHub + Vercel auto-deploy |
| 4 | Add Stripe + landing page |
| 5 | Test with 10 free users |
| 6 | Launch with Facebook ads |

**Total build:** ~40-60 hours
**Cash investment:** Under £50

---

## Automation Components

### Lead Generation (Automated)
- Facebook ads → Lead form → n8n → Auto-response
- SEO content (AI-generated blog posts)
- Footer viral loop ("Website by [Brand] - Get yours free")

### Customer Communication (Automated)
- AI chatbot handles 90% of support queries
- Automated onboarding email sequence
- Stripe handles billing notifications

### Website Creation (Automated)
- Claude API generates content
- Template system injects content
- GitHub API creates repo
- Vercel auto-deploys

### Ongoing Maintenance (Automated)
- Static sites = zero maintenance
- Uptime monitoring (UptimeRobot)
- SSL automatic (Vercel/Cloudflare)

---

## Financial Projections

### Year 1 Targets

| Month | Customers | MRR | Notes |
|-------|-----------|-----|-------|
| 3 | 50 | £499 | MVP launched |
| 6 | 150 | £1,499 | Marketing optimized |
| 9 | 300 | £2,999 | Word of mouth kicks in |
| 12 | 500 | £4,999 | Sustainable passive income |

### Cost Structure

| Item | Monthly Cost |
|------|--------------|
| n8n Cloud | £20 |
| Claude API (500 sites) | £15 |
| Vercel | £0 (free tier) |
| Cloudflare | £0 (free tier) |
| Stripe fees | ~3% of revenue |
| **Total** | **~£35 + 3%** |

### Break-even
- 4 customers = break-even on costs
- Everything after = profit

---

## Risk Mitigation

| Risk | Mitigation |
|------|------------|
| AI generates bad content | Human review step initially, improve prompts |
| Templates look too similar | Create 10+ variants, randomize elements |
| Support overwhelm | AI chatbot + clear limitations in ToS |
| Low conversion | A/B test landing page, improve onboarding |
| High churn | Add stickiness (custom domain, email forwarding) |
| Competition | Focus on local/niche markets initially |

---

## Success Metrics

### North Star Metric
**Monthly Recurring Revenue (MRR)**

### Supporting Metrics
- Customer Acquisition Cost (CAC) - Target: <£20
- Lifetime Value (LTV) - Target: >£100 (10+ months retention)
- Churn Rate - Target: <10% monthly
- Support Tickets per Customer - Target: <0.5/month

---

## Next Steps

1. **Decide on path:** Pure automation (Path A) vs AI-assisted (Path B) vs Hybrid (Path C)
2. **Build MVP:** 2-3 week sprint to create core pipeline
3. **Test with beta users:** 10 free sites to validate quality
4. **Launch marketing:** Facebook ads with £200/mo test budget
5. **Iterate:** Improve based on data

---

## The Bottom Line

The "Free Website Guys" make money from Bluehost affiliate commissions. We can make MORE money by:

1. **Keeping the hosting revenue** (not giving to Bluehost)
2. **Building recurring revenue** (not one-time affiliate)
3. **Using AI to eliminate labor costs**
4. **Using free hosting** (Vercel/Cloudflare) to eliminate infrastructure costs

This is a viable path to £5,000+/mo passive income within 12 months.

---

*Document created: January 2026*
*Status: Strategic planning*
