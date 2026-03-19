# Guidewire_codex
SmartShield is an AI-powered parametric insurance platform that protects gig delivery workers from income loss due to weather, pollution, and disruptions with automated payouts and fraud-resistant design.




SmartShield – AI Parametric Insurance for Gig   Delivery Workers
________________________________________

Problem Statement
Gig delivery workers play a crucial role in India's growing digital economy. Platforms such as Zomato, Swiggy, Amazon, Flipkart, and Zepto depend heavily on delivery partners to complete orders and maintain service efficiency. However, these workers face frequent income disruptions due to external factors beyond their control.Environmental conditions such as heavy rainfall, floods, extreme heat, and severe pollution can prevent delivery partners from working for several hours or even entire days. In addition, social disruptions such as curfews, strikes, or unexpected zone closures may block access to delivery locations. These situations significantly reduce the number of deliveries completed and lead to direct income loss for workers.Currently, gig workers do not have a financial protection system specifically designed to cover income loss caused by such disruptions. As a result, many workers experience unstable earnings and financial uncertainty.The goal of this project is to design an AI-powered parametric insurance platform that protects gig delivery workers against income loss caused by external disruptions. The system automatically detects disruption events and provides compensation without requiring manual claim submissions.
Target Persona
The primary target users of this platform are food delivery partners working for platforms such as Swiggy and Zomato.
Typical profile of a delivery partner:
➢	Works 8–10 hours per day

➢	Completes approximately 18–25 deliveries per day

➢	Average weekly earnings range between ₹3000 and ₹4000

➢	Operates within specific delivery zones in urban areas

Challenges faced by delivery partners include:
➢	Heavy rain reducing delivery orders

➢	Flooded roads making travel difficult

➢	Extreme heat affecting working hours

➢	Severe pollution affecting outdoor work

➢	Government restrictions or curfews blocking deliveries

These disruptions directly impact the worker’s ability to earn income.
 Persona Scenario
Consider the example of Rahul, a Swiggy delivery partner working in Chennai. On a normal working day, Rahul completes around 20 deliveries and earns approximately ₹600.During a heavy rainfall event, many roads become flooded and restaurants temporarily pause delivery services. As a result, Rahul is unable to complete deliveries for several hours. By the end of the day, he earns only ₹200 instead of his usual ₹600, resulting in a loss of ₹400.With the SmartShield platform, the system detects the heavy rainfall condition using weather APIs. Since the rainfall exceeds the predefined threshold, the system automatically triggers a compensation payout to Rahul to partially cover his lost earnings.This ensures that gig workers maintain financial stability even during unexpected disruptions.
Proposed Solution
SmartShield is an AI-enabled parametric insurance platform designed to protect gig workers from income loss caused by external disruptions.The platform continuously monitors environmental and social disruption data through external APIs. When predefined disruption conditions are detected, the system automatically identifies workers operating in the affected area and triggers compensation payments.

Key characteristics of the platform include:
➢	Weekly insurance pricing aligned with gig worker earnings

➢	Automatic disruption detection

➢	Zero-touch claim processing

➢	Instant compensation payouts

➢	AI-based risk assessment and fraud detection
By automating the entire claim process, the platform eliminates the need for manual claim submissions and ensures faster payouts for affected workers.

System Workflow
The system operates through the following steps:
1.	A delivery worker registers on the SmartShield platform using basic information such as name, delivery platform, and working location.

2.	The system collects the worker’s delivery zone and estimates their average weekly earnings.

3.	AI models analyze historical environmental and disruption data for the worker’s location.

4.	Based on the risk level of the delivery zone, the system calculates an appropriate weekly insurance premium.

5.	The platform continuously monitors real-time data from weather, pollution, and government alert APIs.

6.	When a disruption event meets predefined trigger conditions, the system automatically identifies affected workers.

7.	A claim is generated automatically without requiring manual submission.

8.	The system processes compensation payments through a payment gateway.

This workflow ensures a seamless and automated insurance experience for gig workers.

Simple Workflow Diagram:

Worker Registers
       ↓
System Calculates Risk Score
       ↓
Weekly Premium Assigned
       ↓
System Monitors Weather / Pollution
       ↓
Disruption Trigger Detected
       ↓
Automatic Claim Generated
       ↓
Compensation Paid to Worker



Parametric Triggers
Parametric triggers are objective conditions that automatically activate compensation payouts.
The following disruption events are monitored by the system:
Event	Trigger Condition	Impact
Heavy Rain	Rainfall greater than 50 mm	Delivery operations halted
Extreme Heat	Temperature greater than 42°C	Unsafe working conditions
Severe Pollution	Air Quality Index (AQI) above 350	Reduced outdoor activity
Flood Alert	Government flood warning issued	Roads inaccessible
These predefined triggers allow the system to process claims automatically without requiring verification or manual approval.
Weekly Premium Model
Gig workers typically receive payments on a weekly basis. Therefore, SmartShield uses a weekly insurance premium model that aligns with their earning cycle.
The weekly premium is determined based on the risk level of the worker’s delivery zone. AI models analyze historical disruption data to estimate the probability of income loss events.
Pricing model:
Risk Level	Weekly Premium
Low Risk Zone	₹15
Medium Risk Zone	₹25
High Risk Zone	₹40
Workers operating in areas with higher disruption probability pay slightly higher premiums, while workers in safer zones benefit from lower premiums.
This dynamic pricing model ensures fair and affordable coverage for gig workers.

AI / ML Integration
AI models analyze historical environmental and disruption data to estimate the risk level of different delivery zones.
Input data includes:
➢	Historical weather conditions

➢	Pollution levels

➢	Flood-prone areas

➢	Frequency of disruption events

Machine learning models such as Random Forest or Gradient Boosting can be used to generate a risk score for each delivery zone, which helps determine premium pricing.
Fraud Detection
The platform also incorporates AI-based fraud detection mechanisms to prevent misuse of the insurance system.
Fraud detection techniques include:
➢	GPS-based location validation

➢	Detection of duplicate claims

➢	Behavioral anomaly detection

➢	Verification of worker activity during disruption events

Anomaly detection models such as Isolation Forest can be used to identify suspicious claims and flag them for review.


System Architecture
The SmartShield platform consists of several interconnected components.
The Worker Application allows delivery partners to register, view coverage details, and track compensation payments.The Backend Server handles user management, policy creation, disruption monitoring, and claim processing.The AI Risk Prediction Engine analyzes environmental data to determine risk levels and calculate premium pricing.The Disruption Monitoring System continuously collects real-time data from weather APIs, pollution monitoring services, and government alert systems.The Claim Processing Engine automatically generates claims when parametric triggers are activated.Finally, the Payment Gateway processes compensation payouts and transfers funds to the worker’s account.

 

Technology Stack
Frontend : React.js or Next.js
Backend : Python (FastAPI or Flask)
Database : PostgreSQL
Machine Learning : Scikit-learn
External APIs : OpenWeather API
 		  AQI Monitoring API
Payment Integration : Razorpay Sandbox or UPI Simulation
Deployment :  Docker / Cloud Hosting
Key Features
➢	AI-powered risk assessment
➢	Dynamic weekly premium calculation
➢	Automated disruption detection
➢	Zero-touch claim processing
➢	Fraud detection system
➢	Worker dashboard showing earnings protection
➢	Admin dashboard for risk monitoring and analytics

Analytics Dashboard
Worker Dashboard : The worker dashboard provides:
➢	Active insurance coverage status

➢	Weekly premium details

➢	Claim history

➢	Compensation received

➢	Risk alerts for upcoming disruptions
Admin Dashboard : The admin dashboard provides:
➢	Total registered workers

➢	Active policies

➢	Number of claims processed

➢	Risk analysis of delivery zones

➢	Fraud detection alerts

Development Plan
Week 1
Research gig worker challenges and finalize system architecture.
Week 2
Develop initial prototype including worker registration, disruption monitoring, and premium calculation modules.
Future phases will expand the system to include automated claims, payment integration, and advanced fraud detection features.

Impact
The SmartShield platform provides a financial safety net for gig workers who depend on daily earnings. By protecting workers against income loss caused by external disruptions, the platform improves financial stability and reduces uncertainty for delivery partners.Automating claims and payouts also simplifies the insurance process, making it faster, transparent, and accessible for gig workers.This solution demonstrates how AI-powered parametric insurance can be used to support the growing gig economy and ensure economic resilience for delivery workers.

Development Plan
The development of SmartShield will follow a phased approach.
Phase 1 – Ideation and Design
●	Identify target delivery persona.

●	Design system architecture and workflow.

●	Define parametric triggers and weekly premium models.

Phase 2 – Core System Development
●	Implement worker registration and onboarding.

●	Develop a dynamic premium calculation module.

●	Integrate external APIs such as weather and AQI data.

●	Implement automated claim triggering.

Phase 3 – Advanced Features
●	Implement fraud detection using anomaly detection models.

●	Integrate payment gateway for instant payouts.

●	Build analytics dashboards for workers and administrators.
Future Enhancements
In future versions, the platform can include:
●	Hyper-local risk prediction using advanced machine learning models.

●	Integration with delivery platform APIs for real-time activity validation.

●	Personalized insurance plans based on worker behavior and working hours.

●	Expansion to other gig sectors such as ride-hailing and logistics delivery.
Conclusion
SmartShield provides an innovative solution to protect gig workers from income loss caused by uncontrollable disruptions. By combining AI-based risk prediction, parametric triggers, and automated payouts, the platform ensures fast and transparent compensation for delivery workers. This approach strengthens financial stability in the gig economy and demonstrates how technology can improve micro-insurance systems for millions of workers.

									PRESENTED BY,
									Team: codeX
