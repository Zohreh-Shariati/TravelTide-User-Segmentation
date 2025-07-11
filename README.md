# Travel Tide – User Segmentation Analysis

## 1. Project Overview

This project focuses on **user segmentation for Travel Tide**, a company that offers a platform for booking flights and hotels. The objective is to analyze user activity and engagement in order to design a segmentation model that enables the company to target users with relevant perks or offers.

The project involved preprocessing and analyzing behavioral and transactional data from several sources, concentrating only on **active users from the last 6 months**. The final dataset includes thousands of session-level records, which were aggregated into **user-level metrics** to support segmentation efforts.

---

## 2. Data Sources

The analysis utilized the following four tables:

- **` sessions`** – Logs of user activity and behavior in the Travel Tide app
- **`users`** – Demographic details and basic user profile data
- **`flights`** – Booking data for flights
- **`hotels`** – Booking data for hotels

These datasets were merged and cleaned to build a comprehensive picture of each user’s engagement and transactional behavior.

---

## 3. Methodology

### Data Filtering
- Focused only on **active users** who engaged with the app in the past 6 months to ensure relevance.
- Removed incomplete, duplicate, or irrelevant records.

### Data Aggregation
- Transformed session-level records into **user-level metrics**.
- Created metrics such as:
  - Total number of sessions
  - Flight and hotel bookings per user
  - Average session duration
  - Frequency of engagement


### Metric Weighting
- Developed a **scoring system** to associate users with perks.
- Weights were manually assigned to behavioral features due to lack of ground-truth labels.

---

## 4. Tools Used

- **Python** – Core programming for data processing and analysis
- **PostgreSQL** – Data extraction and transformation
- **Pandas** – Data manipulation and aggregation
- **Matplotlib / Seaborn** – Data visualization and insights

---

## 5. Key Findings

-  **Segmentation Achieved**: Successfully segmented users based on engagement and booking behavior.
-  **Business Implication**: Travel Tide can tailor perks and communication strategies to each user group, potentially increasing retention and conversion.

---

## 6. Recommendations

1. **Implement A/B Testing**  
   Validate the weighted scoring and perks distribution using controlled experiments to measure impact on user engagement and retention.

3. **Automate Segmentation**  
   Deploy the segmentation logic into a live system for real-time user classification and dynamic perk distribution.

4. **Targeted Marketing Strategies**  
 Develop campaigns that appeal to all genders and age groups to expand reach and build a more diverse customer base.

---
