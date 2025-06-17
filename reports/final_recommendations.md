# Final Recommendations to AlphaCare Insurance Solutions (ACIS)

##  1. Customer Segmentation for Premium Optimization

**Insight:** Customers with similar vehicle profiles and demographics exhibit consistent claim behaviors.

**Recommendation:**

* Use ML-based clustering to segment customers using features like:

  * `VehicleType`, `RegistrationYear`, `Province`
  * `CapitalOutstanding`, `NewVehicle`, `Converted`
* Apply tiered pricing strategies per segment to minimize over/underpricing.

---

##  2. Vehicle Profile Risk Targeting

**Insight:** Vehicles with high `CubicCapacity`, older `RegistrationYear`, and lacking `AlarmImmobiliser` devices have higher `TotalClaims`.

**Recommendation:**

* Apply higher premium loadings for these profiles.
* Consider mandatory installation of anti-theft devices to lower risk.

---

##  3. Demographic-Based Risk Stratification

**Insight:** Provinces, `MainCrestaZone`, and demographic features like `MaritalStatus` and `LegalType` show varying risk levels.

**Recommendation:**

* Include demographic data in premium calculation.
* Provide discounts or loyalty incentives in low-risk regions.

---

## 4. Target Claim Reduction with Smart Policies

**Insight:** `TrackingDevice` and `AlarmImmobiliser` presence is associated with lower claim amounts.

**Recommendation:**

* Provide premium discounts to customers using these devices.
* Educate customers on safe driving and claim-saving behaviors.

---

##  5. Real-Time Predictive Pricing

**Insight:** Random Forest models delivered the most accurate predictions for `TotalPremium` and `TotalClaims`.

**Recommendation:**

* Integrate this model into the live quote system.
* Use predictions to enhance internal risk assessments.

---

##  6. Policy Design for Low-Claim Segments

**Insight:** Some customer clusters generate high premiums but minimal or zero claims.

**Recommendation:**

* Introduce no-claim bonuses or cashback rewards.
* Design policies promoting retention of low-risk customers.

---

## 7. Operational Integration

**Recommendation:**

* Leverage Git + DVC for versioning data and models.
* Ensure automated pipelines for training and deploying models.


---

**Prepared by:** Abel Adamu Shumet
**Project:** B5W3: Insurance Risk Analytics Challenge
**Date:** 17 June 2025
