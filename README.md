# AWS-EC2-Pricing-Evolution
Analyzing AWS EC2 pricing models and their evolution with real-world workloads

## Table of Contents
1. [Objectives](#objectives)
2. [Overview](#overview)
3. [Trade-offs / Key Learnings](#trade-offs--key-learnings)
4. [Scenario / Example](#scenario--example)
5. [Screenshots](#screenshots)
6. [Conclusion](#conclusion)


⸻

Introduction

AWS EC2 offers multiple pricing models: On-Demand, Reserved Instances (RI), Savings Plans, and Spot Instances.
Many beginners focus only on “cheapest option” without understanding commitment, reliability, and risk.
This project explores how pricing choices evolve with real-world workload requirements.

⸻

Objective
	
	•	Understand the true cost and flexibility of different EC2 pricing models.
	
	•	Highlight common misconceptions (e.g., Spot Instances are unreliable, RIs are always cheapest).
	
	•	Create a clear decision framework for selecting EC2 pricing options.

⸻

Background
	
	1.	On-Demand – No commitment, pay per hour, flexible but more expensive.
	
	2.	Reserved Instances (RI) – Commit to 1-3 years, lower cost, less flexible.
	
	3.	Savings Plans – Flexible commitment, discounts based on usage, can change instance types.
	
	4.	Spot Instances – Cheapest option, can be interrupted, suitable for background jobs.
