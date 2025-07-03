# Toppify OR Preppal

> idk lmao 😂

---

## Plans:

| Plan    | Price | Credits/Tokens | Tokens Cost | Profit  | Profit Margin |
| ------- | ----- | -------------- | ----------- | ------- | ------------- |
| Free    | $0    | 10 / 20000     | $0.006      | -$0.006 | LOSS          |
| Starter | $3    | 500 / 1000000  | $0.3        | $2.7    | 90%           |
| Pro     | $5    | 1000 / 2000000 | $0.6        | $4.4    | 88%           |
| Team    | $10   | 2500 / 5000000 | $1.5        | $8.5    | 85%           |

---

## Infrastructure:

| Service                   | Provider          | Monthly Cost Estimate | Notes                                                                 |
| ------------------------- | ----------------- | --------------------- | --------------------------------------------------------------------- |
| Back-End Hosting (API)    | Railway           | \$5–20                | Free tier allows up to \~500 hours/month. Beyond that, pay-as-you-go  |
| Authentication & Database | Supabase          | \$25                  | Pro tier with RLS, auth, and database                                 |
| Object Storage            | Supabase Storage  | \$5–15                | For `.gz` summaries/flashcards. Compressed = low size                 |
| Front-End Hosting         | Vercel / Netlify  | \$0–20                | Free tier may suffice; upgrade if using custom domain or Pro features |
| Email/Auth (optional)     | Supabase SMTP     | \$0                   | For magic links or passwordless login                                 |
| Logging & Monitoring      | Supabase Logs     | \$0                   | Optional but useful                                                   |
| CDN (included)            | Supabase / Vercel | \$0                   | Most providers include CDN support                                    |
| AI API Tokens             | OpenRouter        | Included in pricing   | Already calculated per plan                                           |

#### Which concludes to a total of **$35-80/mo**

> Domain cost can be neglected, it's just 1$ for the first year.

---

## Conversion rate senarios

| Conversion Rate | Paid Users |
| --------------- | ---------- |
| 2%              | 20         |
| 3%              | 30         |
| 4%              | 40         |
| 5%              | 50         |
| 6%              | 60         |
| 7%              | 70         |

## Revenue Projections (Based on 70% Starter, 20% Pro, 10% Team split)

| Conv.             | Starter (70%)         | Pro (20%)            | Team (10%)          | Revenue | Token Cost | Token-Free Revenue |
| ----------------- | --------------------- | -------------------- | ------------------- | ------- | ---------- | ------------------ |
| **2%** (20 users) | 14 x \$2.70 = \$37.8  | 4 x \$4.40 = \$17.6  | 2 x \$8.50 = \$17.0 | \$72.4  | \$6.00     | **\$66.40**        |
| **3%** (30 users) | 21 x \$2.70 = \$56.7  | 6 x \$4.40 = \$26.4  | 3 x \$8.50 = \$25.5 | \$108.6 | \$9.00     | **\$99.60**        |
| **4%** (40 users) | 28 x \$2.70 = \$75.6  | 8 x \$4.40 = \$35.2  | 4 x \$8.50 = \$34.0 | \$144.8 | \$12.00    | **\$132.80**       |
| **5%** (50 users) | 35 x \$2.70 = \$94.5  | 10 x \$4.40 = \$44.0 | 5 x \$8.50 = \$42.5 | \$181.0 | \$15.00    | **\$166.00**       |
| **6%** (60 users) | 42 x \$2.70 = \$113.4 | 12 x \$4.40 = \$52.8 | 6 x \$8.50 = \$51.0 | \$217.2 | \$18.00    | **\$199.20**       |
| **7%** (70 users) | 49 x \$2.70 = \$132.3 | 14 x \$4.40 = \$61.6 | 7 x \$8.50 = \$59.5 | \$253.4 | \$21.00    | **\$232.40**       |

## Net Profit (After Infra Costs)

| Conversion | Revenue | Min Infra (\$35) | Max Infra (\$80) | Net Profit Range      |
| ---------- | ------- | ---------------- | ---------------- | --------------------- |
| 2%         | \$66.4  | \$31.4           | -\$13.6          | **-\$13.6 – \$31.4**  |
| 3%         | \$99.6  | \$64.6           | \$19.6           | **\$19.6 – \$64.6**   |
| 4%         | \$132.8 | \$97.8           | \$52.8           | **\$52.8 – \$97.8**   |
| 5%         | \$166   | \$131            | \$86             | **\$86 – \$131**      |
| 6%         | \$199.2 | \$164.8          | \$119.8          | **\$119.8 – \$164.8** |
| 7%         | \$232.4 | \$197.4          | \$152.4          | **\$152.4 – \$197.4** |
