# Nuora A/B Testing Methodology

## Testing Platform

**Tool:** Elevate A/B (`https://elevateab.app`)

---

## Traffic Split Configuration

- **Split Ratio:** 50/50 between Control and Variation
- **Traffic Isolation:** Yes (isolated traffic for clean measurement)
- **Device Targeting:** Mobile only
- **Country Targeting:** United States only
- **Visitor Type:** All Visitors (new + returning)

---

## Standard Test Setup

1. Control always runs on the main PDP URL: `https://mynuora.com/products/feminine-balance-gummies-1`
2. Variation runs on a separate test URL (e.g., `/products/nuora-vaginal-probiotic-super-deal`)
3. Traffic is split 50/50 at the page level
4. Tests typically run for 12-24 hours minimum to collect sufficient data

---

## Key Metrics Tracked

### Primary Metrics
- Conversion Rate (%)
- Revenue ($)
- Revenue Per Visitor ($)
- Orders
- AOV ($)

### Secondary Metrics
- Add to Cart Rate (%)
- Reached Checkout Rate (%)
- Checkout Completed Rate (%)
- Average Session Duration (sec)
- Profit ($)
- Profit Per Visitor ($)
- Shipping Revenue ($)

### Purchase Type Breakdown
- One-Time Purchases (count)
- Subscription Purchases (count)

---

## Traffic Sources (Typical Distribution)

| Source | Approximate Share |
|--------|------------------|
| Facebook | ~65-70% |
| Instagram | ~13-15% |
| Direct | ~9-11% |
| Google | ~8-9% |
| Other | ~2-3% |

---

## Statistical Significance

- Tests continue until statistical significance is reached
- Probability to win is tracked in real-time
- Minimum sample size target: ~1,000+ visitors per variation

---

## Notes

- All tests are mobile-first since majority of traffic is mobile
- US customers are primary target demographic
- Tests are typically short-duration (12-24 hours) due to high traffic volume
