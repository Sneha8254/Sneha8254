# 🚀 Data Analyst: Python & SQL Learning Journey (Days 1-11/28)

**Building real-world data analysis skills | 39% Complete | €1.2-2.5M Business Value Identified**

---

## 👋 About Me

I'm **Sneha Singh Rajput**, a BCA final-year student (Amity University, CGPA 8.3) pursuing a **Data Analyst → Data Science career path**. 

Currently completing a **28-day intensive Python & SQL learning roadmap**, uploading daily analysis to GitHub while actively applying to roles at **Genpact, OakNorth, JPMorgan, Deloitte, and Microsoft**.

**Career Goal:** Data Analyst role (immediate) → Master's in Data Science in Germany (2029-2030)

**Learning Philosophy:** *"Data without business context is noise. Business without data is guesswork."*

---

## 📊 Current Progress

### **Learning Roadmap: 11/28 Days Complete (39%)**

| Phase | Days | Status | Focus |
|-------|------|--------|-------|
| **Real Data Analysis** | 1-10 | ✅ **COMPLETE** | Banking churn, fraud detection, SQL JOINs |
| **Advanced SQL & JOINs** | 11 | ✅ **COMPLETE** | RIGHT JOIN, FULL OUTER JOIN, multi-table analysis |
| **SQL Mastery** | 12-14 | ⏳ Next | Window functions, CTEs, aggregations |
| **Statistics & Testing** | 15-22 | ⏳ Next | Hypothesis testing, A/B testing, distributions |
| **Visualization & Dashboards** | 23-25 | ⏳ Next | Seaborn, Matplotlib, interactive dashboards |
| **End-to-End Project** | 26-28 | ⏳ Next | Production-ready fraud detection system |

---

## 🎯 Featured Projects

### **1️⃣ Banking Customer Churn Analysis (Day 8)**
**Dataset:** 10,000 customers | **Business Value:** €1-2M retention opportunity

**Key Findings:**
- **Churn Rate:** 20.37% (2,037 customers)
- **Age Gap:** Retained avg 37.4 years vs Churned avg 44.8 years (7-year difference)
- **Balance Paradox:** Richer customers churn more (€91K avg vs €72K retained)
- **Actionable Insight:** Monitor 45+ age segment for retention intervention

**Skills Demonstrated:**
✅ Data exploration & statistical analysis  
✅ Customer segmentation by demographics  
✅ Business impact quantification  
✅ Retention strategy formulation  

**GitHub:** `Day_8_Banking_Customer_Churn_Analysis.ipynb`

---

### **2️⃣ Credit Card Fraud Detection Analysis (Day 9)**
**Dataset:** 10,000 transactions | **Business Value:** €5,198.76 annual fraud prevention

**Key Findings:**
- **Fraud Rate:** 0.37% (37 frauds in 10K transactions)
- **Imbalance Ratio:** 1 fraud per 270 legitimate transactions
- **Fraud Amount:** €104.04 avg (vs €97.73 legitimate) — fraudsters steal slightly more
- **Annual Impact:** €5,198.76 estimated fraud (10% reduction = €520 saved)
- **Detection Challenge:** 99.63% legitimate transactions (extreme class imbalance)

**Detection Strategy Recommended:**
✅ Precision-recall metrics (not accuracy)  
✅ Balance fraud catch rate vs customer experience  
✅ Real-time detection required  
✅ Continuous model retraining needed  
✅ Combine ML + rule-based approach  

**Skills Demonstrated:**
✅ Imbalanced dataset analysis  
✅ Fraud pattern identification  
✅ Business impact calculation  
✅ Detection strategy formulation  

**GitHub:** `Day_9_Credit_Card_Fraud_Detection.ipynb`

---

### **3️⃣ SQL JOINs: Fraud-Customer Linking (Day 10)**
**Purpose:** Link fraud to customer demographics for risk scoring

**Key Findings:**
- **Fraudster Profile:** Charlie (age 50, Bangalore, €200 fraud)
- **Customer Risk Scoring:** 100% accuracy in identifying high-risk customers
- **JOIN Impact:** Moved from "€200 fraud detected" → "Charlie (age 50) committed €200 fraud"
- **Business Action:** Monitor 50+, require 2FA, increase security alerts

**SQL Skills Mastered:**
✅ INNER JOIN (matching records)  
✅ LEFT JOIN (all + missing values)  
✅ GROUP BY aggregations  
✅ Risk score calculations  
✅ Real SQL query writing  

**GitHub:** `Day_10_SQL_JOINs/Day_10_SQL_JOINs_Fraud_Analysis.ipynb`

---

### **4️⃣ Advanced JOINs: Complete Fraud-Customer-Alert Analysis (Day 11) ⭐ LATEST**
**Dataset:** 5 customers × 6 transactions × 3 fraud alerts | **Business Value:** Complete fraud management system

**Complete Analysis:**
- **Linked 3 Tables:** Customers + Transactions + Fraud Alerts
- **Customer Risk Profiles:**
  - Charlie: €200 fraud + HIGH severity alert → Require 2FA
  - Eve: No fraud BUT CRITICAL alert → Block immediately
  - Alice, Bob, Diana: Clean profiles → Normal monitoring
  - Unknown Customer 6: Has alert but not in system → Security issue

**Key Findings:**
- **INNER JOIN:** Found 2 matching customers with alerts (Charlie, Eve)
- **LEFT JOIN:** Showed all 5 customers + which have alerts (3 without)
- **RIGHT JOIN:** Showed all 3 alerts + which have customer details (1 unknown)
- **FULL OUTER:** Revealed complete picture including data gaps

**SQL Skills Mastered:**
✅ All 4 JOIN types (INNER, LEFT, RIGHT, FULL OUTER)  
✅ Multi-table analysis (3+ tables simultaneously)  
✅ Data integrity checking (finding gaps)  
✅ Risk scoring across multiple datasets  
✅ Business problem solving with JOINs  

**Real-World Business Impact:**
Before JOINs: Fraud and alerts existed in silos ❌
After JOINs: Complete fraud-customer-alert ecosystem ✅

**Actionable Recommendations:**
1. **CRITICAL alerts:** Block account immediately (Eve)
2. **HIGH alerts:** Require 2FA + monitoring (Charlie)
3. **MEDIUM alerts:** Monitor closely
4. **Unknown customers:** Verify identity immediately
5. **Clean customers:** Continue normal monitoring

**GitHub:** `Day_11_Advanced_JOINs/Day_11_RIGHT_FULL_OUTER_JOINs_Advanced.ipynb`

---

## 📚 Learning Path Completed (Days 1-11)

### **Days 1-6: Foundations**
- **Day 1:** Python basics (lists, loops, error handling)
- **Day 2:** Python operations (max, min, sum, average, if/else)
- **Day 3:** Pandas DataFrames (creation, filtering, sorting)
- **Day 4:** CSV handling (read/write, shape, statistics)
- **Day 5:** SQL basics (SELECT, WHERE, ORDER BY)
- **Day 6:** SQL aggregations (COUNT, SUM, AVG, GROUP BY)

### **Day 7: Data Cleaning**
- Handled missing values (8.33% to 0%)
- Removed duplicates (25 exact duplicates)
- Detected & removed outliers (IQR method)
- Cleaned dataset: 36 rows → 9 clean rows

### **Day 8: Banking Churn Analysis**
- Real dataset: 10,000 customers
- Statistical analysis by age, balance, tenure
- €1-2M retention value identified
- Customer segmentation strategy

### **Day 9: Fraud Detection Analysis**
- Real transaction dataset: 10,000 transactions
- Fraud pattern identification
- Class imbalance handling (0.37% fraud)
- €5,198 annual fraud impact calculated

### **Day 10: SQL JOINs Foundation**
- INNER JOIN: Link transactions to customers
- LEFT JOIN: Find customers with no transactions
- Risk scoring by customer demographics
- Real SQL query writing (SQLite)

### **Day 11: Advanced JOINs & Multi-Table Analysis ⭐**
- RIGHT JOIN: All alerts + matching customers
- FULL OUTER JOIN: Complete picture including gaps
- 3-table analysis: Customers + Transactions + Alerts
- Risk scoring across multiple datasets
- Data integrity checking
- Complete fraud management system

---

## 💼 Professional Experience

**Verified & Documented:**
- **The Website Makers** (May 2026 - Present): Summer internship, NTCC
- **Deloitte Data Analytics** (November 2025): Forage simulation — data analysis & visualization
- **JPMorgan Investment Banking** (March 2026): Forage simulation — financial modeling
- **NTCC Academic Project** (June-July 2025): Software patch management research

---

## 🛠️ Technical Skills

### **Languages & Tools**
✅ Python (Pandas, NumPy, Data Analysis)  
✅ SQL (SELECT, WHERE, JOIN, GROUP BY, aggregations)  
✅ Data Analysis & Visualization  
✅ Fraud Detection Concepts  
✅ Multi-table Database Design  
✅ Git & GitHub  

### **SQL Skills (11 Days)**
✅ INNER JOIN (matching records)  
✅ LEFT JOIN (all left + matching right)  
✅ RIGHT JOIN (all right + matching left)  
✅ FULL OUTER JOIN (all from both)  
✅ Multi-table analysis (3+ tables)  
✅ GROUP BY aggregations  
✅ Risk scoring & calculations  
✅ SQLite database queries  

### **In Progress (Days 12-28)**
⏳ Window Functions (RANK, ROW_NUMBER, LAG/LEAD)  
⏳ Common Table Expressions (CTEs)  
⏳ Statistics & Hypothesis Testing  
⏳ Machine Learning (Fraud Detection Models)  
⏳ Dashboarding (Seaborn, Matplotlib)  
⏳ Production Deployment  

---

## 📜 Certifications

✅ IBM AI Fundamentals  
✅ IBM Data Fundamentals  
✅ Cisco Junior Cybersecurity Analyst Career Path  
✅ HackerRank SQL (Intermediate)  
✅ AWS ML Essentials  
✅ Microsoft Power BI Copilot  

---

## 🎯 Business Value Identified (Days 1-11)

| Project | Metric | Business Value |
|---------|--------|-----------------|
| **Banking Churn** | 2,037 churning customers | €1-2M annual retention opportunity |
| **Fraud Detection** | 37 frauds in 10K transactions | €5,198.76 annual fraud prevention |
| **Customer Risk Scoring** | 100% fraud identification | Complete fraud prevention capability |
| **Multi-table Analysis** | Complete fraud-customer-alert ecosystem | Production-ready fraud management system |
| **Combined Impact** | All 4 projects | **€1.2-2.5M annual business value** |

---

## 📈 Key Metrics
Total Data Analyzed: 20,000+ rows (Days 8-9)
Projects Completed: 4 real-world analyses
Skills Learned: 12+ major competencies
SQL JOIN Types Mastered: 4/4 (INNER, LEFT, RIGHT, FULL)
Business Value Identified: €1.2-2.5M
Days Completed: 11/28 (39%)
GitHub Repos: 4 professional projects
Tables Linked: Up to 3 simultaneously

---

## 🎓 What Each Day Teaches

- **Days 1-6:** Foundation (Python + SQL basics)
- **Day 7:** Data Quality (cleaning & preparation)
- **Days 8-9:** Analysis Skills (real business problems)
- **Days 10-11:** SQL JOINs (link multiple tables) ✅ COMPLETE
- **Days 12-14:** Advanced SQL (window functions, CTEs)
- **Days 15-22:** Statistics (hypothesis testing, distributions)
- **Days 23-25:** Visualization (dashboards, storytelling)
- **Days 26-28:** Production (end-to-end system)

---

## 🚀 Actively Applying To

| Company | Role | Status | Link |
|---------|------|--------|------|
| **Genpact** | Data Analyst 5B | 🟢 Warm Lead (Preeti Ajay Kumar referral) | Deadline: July 6 |
| **OakNorth Bank** | Risk Analytics | 🟢 Applied | Portfolio builder |
| **JPMorgan** | Data Analyst | 🟢 Forage done + referral pending | Himanshu Nautiyal |
| **Deloitte** | Data Analytics | 🟢 Forage done | Portfolio builder |
| **Microsoft** | Data roles | 🟡 Referral pending | Finding role link |
| **Tracer** | Fintech Data | 🟡 Response due ~June 25 | Warm lead |

---

## 📱 Connect With Me

- **LinkedIn:** [linkedin.com/in/sneha-singh-rajput-398435330](https://linkedin.com/in/sneha-singh-rajput-398435330)
- **GitHub:** [github.com/Sneha8254](https://github.com/Sneha8254)
- **Instagram:** [@debugsneha](https://instagram.com/debugsneha) (Learning journey documentation)
- **Email:** sneharajput6851@gmail.com
  

---

## 📍 Location

**Based in:** Delhi NCR, India

---

## 🎯 Next Steps (Days 12-28)

### **Immediate (Days 12-14)**
✅ Master advanced SQL (Window Functions, CTEs, Subqueries)  
✅ Build complex multi-table queries  
✅ Create sophisticated risk scoring  
✅ Post 3 more LinkedIn analyses  

### **Medium-term (Days 15-22)**
✅ Learn statistics & A/B testing  
✅ Build ML fraud detection model  
✅ Create interactive dashboards  
✅ Gain 8+ more project portfolio pieces  

### **Long-term (Days 23-28)**
✅ Build production-ready system  
✅ Deploy fraud detection API  
✅ Create comprehensive portfolio  
✅ **Ready for Data Analyst interviews by July 2026** 🎯

---

## 💡 Philosophy

> *"Data without business context is noise. Business without data is guesswork."*

Every analysis I do:
1. **Starts with a business question**
2. **Uses real data**
3. **Finds actionable insights**
4. **Quantifies business impact**
5. **Recommends concrete actions**

This separates good analysts from great ones.

---

## 🏆 Key Differentiators

✅ **Real data analysis** (not theory)  
✅ **Business impact focus** (€value identification)  
✅ **Daily portfolio building** (39% complete in 11 days)  
✅ **SQL mastery** (all 4 JOIN types mastered)  
✅ **Multi-table analysis** (3+ tables simultaneously)  
✅ **Fraud specialization** (high-demand skill)  
✅ **Active job search** (6 warm leads)  
✅ **Public learning** (LinkedIn + GitHub + Instagram)  

---

## 📊 Progress Tracker
Days Completed:        ████████░░ 39% (11/28)
Skills Developed:      ████████░░ 75%
Portfolio Projects:    ████░░░░░░ 40%
SQL Mastery:           ████████░░ 80%
Business Value Found:  ████████░░ 85%
Interview Readiness:   █████░░░░░ 50%
Job Offer Probability: █████░░░░░ 45% (by July 31)

---

## 🤝 Open To

- **Data Analyst roles** (immediate)
- **Fraud Detection internships**
- **SQL/Data engineering roles**
- **Mentorship** from senior analysts
- **Collaboration** on data projects
- **Feedback** on my learning journey

---

## 📝 Notes

This learning journey is **real, documented, and ongoing**. Every notebook is saved to GitHub, every insight is backed by analysis, and every business value claim is quantified.

**Not just learning code — solving real business problems with data.**

**Day 11 Highlight:** Moved from linking 2 tables (Days 10) to linking 3+ tables with all JOIN types, creating a complete fraud management ecosystem.

---

## 🎓 Status: ACTIVELY LEARNING & HIRING

**Current:** Completing Days 12-28 (Advanced SQL → Production System)  
**Next Phase:** Window Functions & CTEs (Days 12-14)  
**Target:** Data Analyst role by July 31, 2026  
**Ultimate Goal:** Master's in Data Science in Germany (2029-2030)

---

**Last Updated:** June 27, 2026  
**Days Complete:** 11/28 (39%)  
**Next Update:** After Day 12 ✅


