# DEVTrails-KLU4-2026
Guidewire DEVTrails 2026 – “WeatherShield” for Zomato Delivery Partners
Team Name: Klu4
Persona: AI-Powered Insurance for Gig Workers

Phase 1 Submission: March 20, 2026

1. Problem Statement & Persona Scenario
Delivery partners working with Zomato are assigned to specific zones and typically earn ₹900–₹1,200 per day.
However, during adverse weather conditions such as rain or floods, certain zones experience a complete drop in orders. As a result:
•	30–50 partners in an affected zone may receive zero orders
•	This leads to a 25–30% loss in weekly income
Real-World Scenario
•	Rain occurs in one zone (e.g., Kukatpally)
•	~30 delivery partners are impacted
•	Other zones (Banjara Hills, HiTech City, etc.) function normally

2. Self-Sustaining Risk Pool Model
WeatherShield introduces a community-driven micro-insurance pool designed to remain sustainable under typical weather disruptions.
Pool Mechanics
•	Total daily orders across Hyderabad: ~40,000
•	Weather Protection Fee: ₹0.5 per order
→ ₹20,000 daily inflow into the pool
Additional inflows:
•	Rain surge fees (platform contribution)
•	Weekly partner premiums
•	Dynamic price balancing
Outcome
•	Under partial-zone disruptions, the pool remains financially stable
•	Enables near zero-loss compensation for affected workers

3. Weekly Premium Model (Dynamic & Fair)
•	Premium is collected weekly (aligned with payout cycle)
•	Base premium: 9% of weekly earnings
o	Example: ₹10,000 earnings → ₹900 premium
AI-Based Adjustment
•	Premium dynamically varies between 8%–10%
•	Based on:
o	Zone risk level
o	Historical weather patterns
o	Claim frequency
 Ensures fair contribution without overcharging low-risk users

4. Automatic Weather Detection & Transparent Payout System
Detection Mechanism
•	Weather monitored every 30 minutes using OpenWeather API
•	Mapped to delivery zones
Income Loss Calculation
•	Uses personalized hourly earnings
•	Based on last 7 days’ average
Example:
•	Average earning: ₹100/hour
•	Rain disruption: 5 hours
→ Payout = ₹500 (credited instantly)
Transparency Features (App UI)
•	“Rain detected in your zone at 2:30 PM”
•	Lost hours: 5
•	Hourly rate: ₹100
•	Final payout: ₹500
 System ensures accurate compensation for actual income loss only

5. Dual Dashboard System
A. Worker Dashboard
•	Weekly savings summary (e.g., “You saved ₹1,850”)
•	Premium deducted
•	Protected earnings
•	Risk meter
•	Rain event breakdown

B. Admin Dashboard
•	Predicts next-day payout liability (using forecasts)
•	Real-time pool balance tracking
•	Zone-wise claim analysis
•	Fraud detection heatmap
•	Partner performance insights

6. Adversarial Defense & Anti-Fraud Strategy
Problem
Fake GPS manipulation and coordinated fraud can drain the insurance pool.
Solution: Multi-Layer Fraud Detection
1.	Cross-verification:
o	GPS location
o	Accelerometer data
o	Platform timestamps
o	Weather API data
2.	Movement Pattern Analysis:
o	Detects unrealistic jumps or static spoofing behavior
3.	Fraud Ring Detection:
o	Flags clusters (5+ suspicious claims in same zone)
4.	Claim Scoring System:
o	Score range: 0–100
o	Genuine users: 90+
o	Suspicious users: <70
5.	Smart Approval:
o	Verified rain events → auto-approve genuine claims

7. AI/ML Integration Strategy
AI is integrated in three key components:
1. Dynamic Premium Prediction
•	Adjusts premium (8–10%) based on:
o	Risk level
o	Zone history
o	Weather trends
2. Income Loss Estimation
•	Personalized hourly rate prediction
•	Based on historical earning patterns
3. Fraud Detection Model
•	Detects anomalies in:
o	Movement patterns
o	Claim behavior
o	GPS inconsistencies
Tools Used (Phase 1):
•	Scikit-learn (mock implementation)
Phase 2 Plan:
•	Classification models for fraud detection
•	Regression models for payout prediction
•	Risk clustering for zone categorization

. Technology Stack
•	Frontend: React Native (Mobile Application)
•	Backend: Node.js + Firebase
•	APIs: OpenWeather API
•	ML Tools: Scikit-learn (Phase 1 simulation)

8. Phase 1 Prototype Scope
•	User onboarding flow
•	Weekly premium calculator
•	Worker dashboard (mock rain detection + payout simulation)
•	Admin dashboard (basic predictions)
•	Fraud detection concept visualization
Platform: Mobile Application

9. Key Innovations & Differentiators
•	Personalized dynamic hourly earning model
•	Fully transparent payout calculations
•	Self-sustaining community insurance pool
•	Real-time weather-based automation
•	Movement-based fraud detection system

10. Future Enhancements (Phase 2)
•	Real-time ML model deployment
•	Extreme weather scenario handling (multi-zone floods)
•	Integration with platforms like Zomato
•	Advanced simulation for pool sustainability
•	Expansion to other gig platforms (Swiggy, Uber Eats, etc.)

 Final Summary
WeatherShield is an AI-driven micro-insurance solution designed to protect gig workers from income loss caused by weather disruptions. By combining:
•	Dynamic pricing
•	Real-time weather tracking
•	Personalized income models
•	Fraud-resistant systems
it creates a fair, transparent, and scalable financial safety net for delivery partners.

**GitHub Repo:** https://github.com/renuneeraja/DEVTrails-KLU4-2026

