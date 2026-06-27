# Hypothesis Test Notes

## Business Question

Should the new onboarding and activation campaign be launched to all users?

The objective is to determine whether the Treatment onboarding experience improves user conversion compared to the existing Control onboarding experience.

---

## Primary Metric Selected

### Paid Conversion Rate

Paid Conversion Rate is selected as the primary metric because it directly measures the percentage of users who become paying subscribers after onboarding.

Formula:

Paid Conversion Rate = Number of Paid Users / Total Users

This metric is closely linked to business growth, subscription revenue, and customer acquisition success.

---

## Null Hypothesis (H0)

There is no statistically significant difference in Paid Conversion Rate between the Control and Treatment groups.

H0:

Treatment Conversion Rate ≤ Control Conversion Rate

---

## Alternate Hypothesis (H1)

The Treatment group has a higher Paid Conversion Rate than the Control group.

H1:

Treatment Conversion Rate > Control Conversion Rate

---

## Test Type

One-Tailed Two-Proportion Z-Test

Reason:

- The metric being tested is a conversion rate (proportion).
- We are comparing two independent groups.
- The business objective is specifically to determine whether the Treatment performs better than the Control.
- We are interested only in improvement, not any difference.

---

## Significance Level

Alpha (α) = 0.05

Confidence Level = 95%

Decision Rule:

- If p-value < 0.05 → Reject H0
- If p-value ≥ 0.05 → Fail to Reject H0

---

## Experiment Data

### Control Group

- Total Users = 693
- Paid Conversion Rate = 3.17%

### Treatment Group

- Total Users = 715
- Paid Conversion Rate = 6.99%

---

## Statistical Test Results

- Z-Score = 3.25
- P-Value = 0.00115

---

## Decision

P-Value (0.00115) is less than Alpha (0.05).

Therefore:

Reject the Null Hypothesis (H0)

---

## Interpretation Logic

If the Treatment group's conversion rate is significantly higher than the Control group's conversion rate and the p-value is below the significance threshold, we conclude that the improvement is unlikely to be caused by random chance.

If the p-value had been greater than 0.05, we would not have enough evidence to conclude that the Treatment improves conversion.

---

## Business Interpretation

The Treatment onboarding experience produced a statistically significant increase in Paid Conversion Rate compared to the Control experience.

The Treatment group achieved:

- Higher conversion rate
- Higher engagement score
- Faster conversion time
- Slightly higher revenue per user

The evidence suggests that the new onboarding campaign successfully improves user activation and conversion.

---

## Conclusion

The experiment provides strong statistical evidence that the Treatment onboarding experience outperforms the existing onboarding process.

Based on the results, the Treatment experience is recommended for rollout to all users.