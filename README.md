# 🚗 Customer Coupon Acceptance Analysis

This project explores the factors that influence whether drivers accept digital coupons while on the road. The goal was to uncover meaningful patterns that explain why some drivers choose to use these coupons—and why others don’t.

---

## 📚 Background

This data is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechanical Turk, where participants were asked if they would accept a coupon (for restaurants, bars, coffee houses, etc.) sent to their phone during a driving scenario. Acceptance was defined as using the coupon either immediately or before it expired.

---

## ✅ Overall Acceptance Trends

Roughly **57%** of coupons in the dataset were accepted. While a majority said yes, a large portion of offers were still declined—suggesting that coupon acceptance depends on more than just availability.

---

## 🔍 Key Findings: What Sets Acceptors Apart?

We looked at how different features (like passenger type, time of day, income, and personal habits) influenced whether a coupon was accepted.

### 🍸 Bar Coupons

- **Frequent Bar-Goers Are More Receptive:** Drivers who go to bars more than 3 times a month were far more likely to accept a bar coupon.
- **Age Plays a Role (Especially with Habits):** Those over 25 who also visit bars regularly were more likely to say yes.
- **Passenger Type & Occupation Matter:** Drivers traveling with adults (not kids) and those in certain job sectors were more likely to accept bar coupons.
- **Best Predictors Are Combinations:** The highest acceptance rates came from drivers who were over 25, frequently visited bars, had no kids in the car, ate at inexpensive restaurants, and belonged to specific income brackets.

### ☕ Coffee House Coupons

- **Company Influences Decisions:** Drivers with friends or partners in the car were more likely to accept a coffee coupon than those driving alone or with kids.
- **Timing Is Key:** Acceptance peaked at 10 AM and 2 PM—common coffee break hours.
- **Regular Visitors Say Yes More Often:** People who already go to coffee shops frequently were more likely to use the coupons.
- **Combined Factors Matter:** The highest acceptance was among drivers with companions, a regular coffee habit, and driving during peak coffee times.

---

## 🧠 Conclusion

Drivers don’t accept coupons randomly. Their decision is shaped by habits, timing, and social context. For bar coupons, those with a “bar-going” lifestyle (e.g., over 25, adult passengers, social occupations) are more responsive. For coffee house coupons, having company and receiving the offer at a typical coffee time makes a noticeable difference.

**In short: coupons work best when they align with what people are already likely to do.** Targeting offers based on these patterns can significantly improve engagement and usage.

---
