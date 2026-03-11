# Dummy-Product-Funnel
Product funnel and feature analysis using Python

# Product Funnel & Feature Analysis

This project demonstrates a **product funnel and feature usage analysis** for a hypothetical product with 1,000 users. It is built using **Python (pandas, matplotlib)** and can be visualized using **Power BI**.  

## Project Overview
- Analyze user behavior across the product funnel: **Signup → Onboarding → First Purchase → Feature Use**
- Identify **drop-offs** in the funnel and suggest improvements
- Track **top features** used by users and engagement trends

## Dataset
- `dummy_product_data.csv` contains simulated user-event data:
  - `user_id` : Unique user ID
  - `event` : Event type (signup, onboard, purchase, feature_use)
  - `timestamp` : Event timestamp
  - `product` : Feature name (only for `feature_use` events)

## Key Insights
- Total users: 1,000
- Drop-off: 17.4% from signup → onboarding, 40.44% from onboarding → first purchase
- Top 5 features (Notifications, Search, VideoCall, ProfileUpdate, Chat) drive 65% of user engagement
- Python visualizations created to track funnel and feature usage

## How to Run
1. Install Python packages: `pandas`, `matplotlib`  
```bash
pip install pandas matplotlib
