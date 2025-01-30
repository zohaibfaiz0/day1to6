# Marketplace Deployment - Day 6

## Project Overview
This repository contains all the necessary files and documentation for the deployment and staging environment setup of the marketplace project.
It follows a structured approach, covering environment configuration, deployment, and testing.

## Guide
- Create an account 
- Login using email and password
- Add products to cart
- Go to cart page
- Go to checkout page
- Enter your information
- Select how to pay [card/cash on delivery] [card doesn’t work, select Cash on Delivery]
- Place order

## Staging Environment
- **Live Staging URL:** [https://testing-finallll.vercel.app]
- **Github URL:** [https://github.com/zohaibfaiz0/testing]
- **Hosting Platform:** Vercel 

## Repository Structure
```
├── documents/
│   ├── Day_1
│   ├── Day_2
│   ├── Day_3
│   ├── Day_4
│   ├── Day_5
│   
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── context/
│   ├── sanity/
│
├── public/
│   ├── assets/
│
├── test-reports/
│   ├── test_cases.csv
│   ├── performance_report_lighthouse.pdf
│
├── .env.example
├── package.json
├── next.config.js 
├── README.md
```

## Deployment Steps
### 1. Hosting Platform Setup
- Connected GitHub repository to **[Vercel]**
- Configured build and deployment settings
- Added environment variables securely

### 2. Environment Variables
- Configure environment variables by creating a `.env` file and filling in the required values.

### 3. Deployment Process
- Deployed the project to Vercel
- Ensured a successful build and basic functionality validation

### 4. Staging Environment Testing
#### ✅ Functional Testing:
- Verified product listing, search, cart operations
- API interactions validated 

#### ✅ Performance Testing:
- Used Lighthouse for speed and responsiveness analysis
- Performance report saved in `PerformanceReport.pdf`

#### ✅ Security Testing:
- Input validation checks to prevent SQL injection
- HTTPS enforced and sensitive data secured

## Test Case Report
All test cases are documented in TestCase.pdf, including:
- **Test Case ID**
- **Description**
- **Expected vs. Actual Results**
- **Status** (Passed/Failed)

## Key Takeaways
- Successfully deployed a working staging environment.
- Identified and documented issues for future improvements.
- Learned best practices for managing deployment pipelines and staging environments.

## Changes Made
- Removed product details and order confirmation pages due to deployment issues.

### 🚀 Project Ready for Review!
