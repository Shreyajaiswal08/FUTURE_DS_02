📣 FUTURE_DS_02 — Social Media Campaign Performance Tracker

Internship:Future Interns — Data Science & Analytics  
Task 2: Analyze social media campaign data to measure ad performance, ROI, and engagement using Power BI.

 🎯 Objective
To build an interactive **Power BI dashboard** that evaluates digital campaign effectiveness by tracking:
- 💰 ROI
- 📊 Click-through Rate (CTR%)
- 👥 Conversions & Approved Conversions
- 🎯 Audience insights (Gender & Age)

 ⚙️ Steps Performed
1. Data Cleaning & Preprocessing
   - Handled missing or invalid values in Gender,Age, and ROI columns  
   - Converted Start Date and End Date to proper date formats  
   - Ensured numeric fields (Clicks, Conversions, Spend) were correctly typed  

2. Data Modeling & DAX Measures
   - Total Impressions = SUM(Impressions)
   - Total Clicks = SUM(Clicks)
   - CTR (%) = DIVIDE([Total Clicks],[Total Impressions])*100
   - ROI = SUM(ROI)
   - Total Approved Conversions = SUM(Approved Conversions)

3. Dashboard Design
   - KPI Cards for total metrics (Impressions, Clicks, Conversions, ROI)
   - Slicers: Gender, Age, Reporting Start
   - Column Chart: Clicks & ROI by Year
   - Line Chart: CTR% by Year
     - Table Summary: Yearly totals for all key metrics
   
 🧠 Key Insights
- The campaign achieved 4K ROI with 585 approved conversions.
- The overall CTR was 0.01%, indicating limited ad engagement.    
- Performance is consistent across age and gender — opportunity to segment audiences further.  

🧩 Tools & Tech Used
- Microsoft Power BI  
- DAX(Data Analysis Expressions)  
- Excel(Campaign Data Source)  

