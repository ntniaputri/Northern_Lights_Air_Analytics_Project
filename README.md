# ✈️ Northern Lights Air Loyalty Program Analysis ✨

---

## ✨ Project Background ✨

Northern Lights Air (NLA), a fictitious airline headquartered in Canada, operates a customer loyalty program designed to reward and retain frequent flyers. In an effort to increase program participation and strengthen customer engagement, NLA launched a promotional campaign between February and April 2018 aimed at driving new enrollments. This project conducts a comprehensive analysis of NLA's loyalty program to evaluate program performance, customer engagement, and cancellation behaviors.

The dataset includes detailed information on customer enrollments, loyalty tier segmentation, cancellation records, and additional customer characteristics. This analysis aims to extract meaningful insights that can help optimize the loyalty program strategy and maximize customer lifetime value. The following core areas are addressed:

* **Customer Value Segmentation:** 💰 Identification and profiling of different customer segments based on their lifecycle value, providing clarity on which groups contribute most to the business and which require strategic intervention.
* **Loyalty Tier Performance:** ⭐ Evaluation of the behaviors and performance of customers across NLA's loyalty tiers (Aurora, Nova, Star), including metrics such as redemption rate and lifetime value.
* **Promotion Impact:** 🚀 Assessment of the 2018 promotional campaign’s effect on customer retention and cancellation trends, uncovering whether promotional enrollment led to better loyalty outcomes compared to standard sign-ups.

* Data preparation and initial inspection were carried out using Microsoft Excel.
* Interactive dashboards and visual analyses exploring customer value, loyalty tiers, and cancellation behavior are available in Tableau:
    🔗 https://public.tableau.com/views/NorthernLightsAirLoyaltyProgram_17497335940990/LoyaltyProgramHealthCustomerValue?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

## 🔍 Data Structure & Initial Checks 📋

The dataset for this Northern Lights Air (NLA) loyalty program analysis is composed of two relational tables: Customer Flight Activity and Customer Loyalty History. These are connected via a shared key field: Loyalty Number. The Customer Flight Activity table contains 392,936 records, capturing monthly travel behavior such as flight count, distance flown, and points earned or redeemed. The Customer Loyalty History table includes 16,737 records and provides demographic and program-related details for each loyalty member, including enrollment type, salary, CLV, and cancellation information.

![image](https://github.com/user-attachments/assets/a568dbdc-b5f1-4be9-9feb-c182a8b11596)

Preliminary inspection using Excel showed no significant outliers or anomalies in the data. Both tables were clean and ready for transformation and analysis in subsequent stages.

---

## 🌟 Executive Summary 🌟

NLA’s loyalty program reveals distinct member behaviors across tiers. Aurora tier members, who combine high spending with strong reward engagement, generate the highest customer lifetime value (CLV), making them ideal targets for retention and VIP incentives. Star tier members, while the most active in redeeming points, show the lowest CLV, signaling high reward sensitivity but limited revenue, they may respond well to budget-conscious loyalty perks. Nova tier members fall in between, with moderate performance in both spending and redemption.
Most customers fall into Medium and Low CLV bands, highlighting an opportunity for targeted growth. Promotional enrollments slightly reduce cancellations, indicating that early incentives can boost retention. To maximize impact, tier-specific strategies are needed: retain Aurora, uplift Medium/Low, and engage Star with value-driven offers.

---

## 📊 Key Findings 📊

![image](https://github.com/user-attachments/assets/daa6b97a-a01b-4645-b91c-1963424c399c)

### Peak Areas ⬆️
* Aurora tier has the highest CLV: $10,672.69.
* Star tier leads in redemption rate: 1.49%.
* Medium CLV Band holds the largest share of customers: 41.58% (~7,000 customers).
* 2018 Promotion shows a lower cancellation rate: 11.84%, compared to Standard.

### Decline Areas ⬇️
* Star tier shows the lowest CLV: $6,741.76.
* Nova tier has the lowest redemption rate: 1.43%.
* VIP CLV Band has the smallest customer share: 15.81%.
* Standard enrollment has the highest cancellation rate: 12.38%.

### Unique Patterns (Noteworthy Behaviors + Strategic Implications) 💡
* **Star tier:** highest redemption (1.49%) + lowest CLV ($6,741.76), suggesting that lower-value customers are more reward-sensitive and possibly more price-conscious, they engage more with the loyalty program to maximize perceived value.
* **Aurora tier:** high redemption (1.46%) + highest CLV ($10,672.69) — ideal loyalty behavior. This group spends and engages — prime targets for VIP benefits or brand ambassador roles.
* **Medium and Low CLV Bands** form 66.72% of the base (Medium: 41.58%, Low: 25.14%) — a huge pool with upgrade potential. Strategic investment in these segments could improve average CLV if they’re guided into higher tiers via personalized incentives.
* **Promotional enrollment** lowers cancellation by 0.54% (11.84% vs. 12.38%) — while not dramatic, it suggests promotions improve early stickiness. Optimizing these offers and extending similar strategies could further boost retention at scale.

---

## 🎯 Recommendations 🎯

* **Prioritize Aurora Tier:** Retain high-CLV members with VIP perks, upsells, and ambassador roles to maximize long-term value.
* **Re-Engage Star Tier:** Offer budget-friendly, frequent rewards to match their high redemption habits and drive more spending.
* **Activate Nova Tier:** Encourage redemptions and upgrade engagement with targeted offers and simplified reward use.
* **Uplift Medium/Low CLV Segments:** Launch tier-migration incentives and personalized nudges to unlock growth from this large customer base.
* **Optimize Enrollment Strategies:** Expand promotional sign-ups and improve standard onboarding to reduce cancellations and build early loyalty.
