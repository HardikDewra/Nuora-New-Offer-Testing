# Nuora Gummies PDP Offer Report - Resilia-Style Offer (V1)

**Test URL:** `https://mynuora.com/products/nuora-vaginal-probiotic-gummies-2?variant=45614888747148`

**Product:** Nuora Vaginal Probiotic Gummies (60 gummies / 30 servings)

**Status:** Tested variant - CONTROL WON

**Inspiration:** Resilia PDP (`https://resilia.shop`)

---

## A/B Test Results

### Test Configuration
- **Test Name:** Current highest converting offer vs New Resilia Offer
- **Test Date:** Jan 09, 2026
- **Duration:** 5 hours
- **Total Visitors:** 1,004
- **Split:** 50/50
- **Targeting:** Mobile + United States only

### Performance Comparison

| Metric | Control | Resilia Variant (V1) | Difference |
|--------|---------|----------------------|------------|
| Visitors | 505 | 499 | -6 |
| Revenue | $1,607.63 | $1,084.78 | -$522.85 |
| Rev/Visitor | $3.18 | $2.17 | -$1.01 |
| Conv. Rate | 5.94% | 4.21% | -1.73% |
| Orders | 30 | 21 | -9 |
| AOV | $53.59 | $51.66 | -$1.93 |
| Profit | $995.63 | $1,075.78 | +$80.15 |
| Profit/Visitor | $1.97 | $2.16 | +$0.19 |
| Ship. Rev | $4.95 | $49.50 | +$44.55 |

### Funnel Conversion Rates

| Stage | Control | Resilia Variant (V1) |
|-------|---------|----------------------|
| Add to Cart | 12.1% | 8.6% |
| Reached Checkout | 8.3% | 5.4% |
| Checkout Completed | 5.94% | 4.21% |

### Session Duration

| Metric | Control | Resilia Variant (V1) | Change |
|--------|---------|----------------------|--------|
| Avg Session | 34 sec | 30 sec | -11.8% |

### Purchase Type Breakdown

| Type | Control | Resilia Variant (V1) |
|------|---------|----------------------|
| One-Time Purchases | 7 | 0 |
| Subscription Purchases | 23 | 21 |

### Test Outcome

**RESULT: CONTROL WINS**

- Control had higher conversion rate (5.94% vs 4.21%)
- Control had higher revenue ($1,607 vs $1,084)
- Control had more orders (30 vs 21)
- Resilia variant eliminated ALL one-time purchases (7 -> 0)
- Subscription orders remained similar (23 vs 21)
- Session duration dropped slightly (-11.8%)
- 100% subscription rate on variant but at cost of conversion

---

## Offer Structure

This variant uses **"Buy X, Get Y FREE"** bundle naming with product images on each card and **dynamic pricing** based on subscription status.

### Subscribe and Save Pricing

| Bundle Name | Price | Compare Price | Savings | Badge |
|-------------|-------|---------------|---------|-------|
| Buy One | $29.99 | $59.99 | 50% | None |
| Buy 2, Get 1 FREE | $59.99 | $179.97 | 67% | "Most Popular" |
| Buy 3, Get 2 FREE | $89.99 | $299.95 | 70% | "Free Shipping" |

### One-Time Purchase Pricing

| Bundle Name | Price | Compare Price | Savings | Badge |
|-------------|-------|---------------|---------|-------|
| Buy One | $39.99 | $59.99 | 33% | None |
| Buy 2, Get 1 FREE | $79.99 | $179.97 | 56% | "Most Popular" |
| Buy 3, Get 2 FREE | $119.99 | $299.95 | 60% | "Free Shipping" |

### Subscription Module

- **Checkbox style:** Dashed border box with circular checkbox
- **When ON:** Filled circle, yellow/cream background
- **When OFF:** Empty circle, white background with dashed border
- **Copy:** "Save 25% With Automatic Refills"
- **Sub-copy:** "Zero Commitment | Exclusive Discounts | Cancel Anytime"
- **Default state:** Checked (subscription ON)

---

## Key UI Features

### Card Design Elements
- Product image thumbnails on each card (shows actual product packaging with quantity)
- "You save X%" percentage displayed on each card
- Badge in top-right corner ("Most Popular" / "Free Shipping")
- Strikethrough compare price next to sale price
- Cards are vertically stacked
- Prices dynamically update when subscription is toggled

### CTA Button
- Simple "ADD TO CART" text
- Black background, white text

---

## Key Design Differences from Control

| Element | Control | Resilia-Style Variant |
|---------|---------|----------------------|
| Bundle naming | "1 Pack / 2 Packs / 3 Packs" | "Buy One / Buy 2, Get 1 FREE / Buy 3, Get 2 FREE" |
| Product images | None on cards | Product thumbnails on each card |
| Savings display | None | "You save X%" percentage on each card |
| Badges | None | "Most Popular" + "Free Shipping" badges |
| Card layout | Horizontal with radio buttons | Vertical stacked cards |
| Dynamic pricing | Yes (prices change with sub toggle) | Yes (prices change with sub toggle) |
| Subscription toggle | Dashed border checkbox | Dashed border checkbox (similar) |
| Subscription copy | "Save More With Automatic Refills" | "Save 25% With Automatic Refills" |
| Sub savings | Not specified | Explicit "25%" savings stated |
| CTA | "ADD TO CART" | "ADD TO CART" |

---

## Resilia Reference (Inspiration Source)

**URL:** `https://resilia.shop`

### Their UI Elements

- **Product Images:** Thumbnail on each bundle card showing quantity (1 pack, 3 packs, 5 packs)
- **Savings Display:** "You save X%" on each card
- **Badges:** "Most Popular" (black), "Free Shipping" (black)
- **Subscription Checkbox:** Dashed border, "Save 25% with Automatic Refills"
- **Sub-copy:** "Zero Commitment | Exclusive Discounts | Cancel Anytime"
- **Dynamic Pricing:** Prices change when subscription is toggled on/off
- **CTA:** "Add To Cart" with black background

---

## Key Learnings

1. "Buy X, Get Y FREE" naming completely eliminated OTP orders (7 -> 0)
2. Despite 100% subscription rate, overall conversion dropped significantly (-1.73%)
3. The "free" framing may have created perceived commitment that deterred purchases
4. Product images on cards didn't improve conversion
5. Explicit "Save 25%" on subscription didn't drive more subscriptions vs control
6. Dynamic pricing (showing different prices for sub vs OTP) was implemented but still lost
7. CRITICAL INSIGHT: "Get X FREE" bundles frame the purchase as a bigger commitment, which filters out commitment-averse customers entirely rather than converting them
8. Session duration barely dropped (-11.8%) - smallest drop among all variants
9. The variant essentially filtered out OTP-inclined customers without converting them to subscription
10. Even with the OTP option available (via toggle), the "Buy X, Get Y FREE" framing deterred OTP purchases entirely
