# DecodeLabs-Project1-EDA-Feature-Engineering
Advanced Exploratory Data Analysis (EDA) and Feature Engineering pipeline built in Python during my DecodeLabs Data Science Internship.
## Project Overview
An end-to-end Exploratory Data Analysis (EDA) and Feature Engineering pipeline built in Python on a 1,200-row e-commerce transaction dataset.

## Key Techniques
- **Missing Data Imputation:** Resolved missing values in `CouponCode` (`NO_COUPON`) using domain-specific categorical logic.
- **Outlier Capping (Winsorization):** Detected extreme values in `UnitPrice` and `TotalPrice` via the Interquartile Range (IQR) method and capped them using `np.clip`.
- **Categorical Encoding:** Applied One-Hot Encoding (`pd.get_dummies`) to transform `PaymentMethod` and `OrderStatus` into binary numerical features.
- **Feature Engineering:** Engineered three predictive features (`Average_Item_Price`, `Cart_Value_Per_Item`, and `TotalPrice_Log`).
- **Multicollinearity Check & Export:** Verified feature correlations and exported the clean dataset (`cleaned_dataset_project1.csv`).
