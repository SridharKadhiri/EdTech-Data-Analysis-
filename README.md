# EdTech Data Analysis

## Overview

As a Data Analyst in an EdTech company, tasked with accelerating user growth through a detailed analysis of customer acquisition. The insights gained from this analysis will inform the design of a more effective marketing strategy for the company.

## Expected Outcome

1. **Metrics Identification and Analysis Questions**
   - Frame insightful questions and identify relevant metrics.
   - Assist the business team in understanding the lead's journey and stages for potential improvement.
   - Provide insights for business heads to assess team performance.
   - Help managers identify target areas for improvement.

2. **Handling Outliers**
   - Identify and make a note of any outliers in the dataset.
   - Exclude outliers from the analysis.

3. **Dashboard Creation**
   - Build a visually appealing and informative dashboard.
   - Utilize professional visualizations to support data-backed recommendations.
   - Empower the business team with actionable insights, roadmaps, and strategies.

## Tools Useed

- Preferred Visualization Tool: PowerBI Desktop
- Optional: MS-Excel

## Dataset Overview

### Customer Acquisition Flow (flowchart)

1. **Lead**
2. **Awareness**
3. **Consideration**
4. **Conversion**

### Dataset Components

1. **lead_basic_details**
   - lead_id: unique lead identifier [string]
   - age: age of the lead [int]
   - gender: gender of the lead [string]
   - current_city: city of residence [string]
   - current_education: current education details [string]
   - parent_occupation: parent's occupation [string]
   - lead_gen_source: lead generation source [string]

2. **sales_managers_assigned_leads_details**
   - snr_sm_id: unique senior sales manager identifier [string]
   - jnr_sm_id: unique junior sales manager identifier [string]
   - assigned_date: date leads are assigned to junior sales manager [date]
   - cycle: lead assignment cycle [string]
   - lead_id: unique lead identifier [string]

3. **leads_interaction_details**
   - jnr_sm_id: unique junior sales manager identifier [string]
   - lead_id: unique lead identifier [string]
   - lead_stage: stage of the lead when contacted by junior sales manager [string]
   - call_done_date: date of call made to lead by junior sales manager [date]
   - call_status: status of the call [string] (successful/unsuccessful)
   - call_reason: reason for calling the lead [string]

4. **leads_demo_watched_details**
   - lead_id: unique lead identifier [string]
   - demo_watched_date: date of demo session watched by the lead [date]
   - language: language of the watched demo session [string] (English, Telugu, Hindi)
   - watched_percentage: percentage of session watched by the lead (out of 100) [float]

5. **leads_reasons_for_no_interest**
   - lead_id: unique lead identifier [string]
   - reasons_for_not_interested_in_demo: reason for lack of interest in watching the demo [string]
   - reasons_for_not_interested_in_consideration: reason for not considering the product [string]
   - reasons_for_not_interested_in_conversion: reason for not converting [string]

## Dataset Download

Download the dataset files using the link provided: [Dataset Files](https://drive.google.com/file/d/1FlQrn0Q5D23VMC4mdbsbLmLQphWdgwnd/view?usp=sharing)

## Dashboard Preview
![image](https://github.com/SridharKadhiri/EdTech-Data-Analysis-/assets/90100318/b531e8ec-74d1-46c9-9a90-9e538bdfb2f8)
[Link to the Dashboard](https://www.novypro.com/project/edtech-analysis-dashboard)

# Project Report

## Sales and Conversion Analysis Report

### Executive Summary:

In our recent analysis utilizing the interactive dashboard, key insights related to lead conversion and team performance were identified. The overall conversion rate for successful enrollment is currently at 17.88%, revealing areas for improvement. Notable performers include Junior Managers JNR1016MG and JNR1002MG, with conversion rates of 8 and 7, respectively. While there are successes, further growth opportunities exist, especially for JNR1002MG, who leads in the overall conversion rate among junior managers. Conversely, JNR1011MG displays the lowest conversion rate, suggesting a need for refresher sessions.

### Key Findings:

1. **Overall Conversion Rate:**
   - The analysis indicates a conversion rate of 17.88%, highlighting areas for enhancement in the lead-to-enrollment journey.
   - The conversion funnel visualization in the dashboard provides a detailed breakdown of each stage, offering insights into improvement areas.

2. **Junior Managers Performance:**
   - Junior Managers JNR1016MG and JNR1002MG exhibit remarkable performance with conversion rates of 8 and 7, respectively.
   - JNR1002MG holds the highest conversion rate among junior managers, establishing them as the top performer.

3. **Suggested Refresher Sessions:**
   - JNR1011MG exhibits the lowest conversion rate, indicating a need for intervention.
   - We recommend scheduling refresher sessions for the team under JNR1011MG to address potential challenges and enhance performance.

4. **Addressing Offline Class Preferences:**
   - The primary reason for not enrolling is the preference for offline classes.
   - To mitigate this concern, we recommend incorporating a hybrid learning model, offering a blend of online and offline options.

5. **Senior Manager SNR5.3MG Performance:**
   - Senior Manager SNR5.3MG stands out with a 40% conversion rate, showcasing effective leadership.
   - Analyzing strategies employed by SNR5.3MG can provide valuable insights for other managers to enhance their conversion rates.

6. **Call Count and Conversion Ratio:**
   - Managers with the highest call counts demonstrated the highest conversion ratios.
   - Encouraging all managers to maintain a high call volume could contribute to improved overall conversion rates.

### Conclusion:

The analysis has unveiled strengths and areas for improvement in the lead conversion process. Addressing offline class preferences, providing targeted refresher sessions, and learning from top performers can contribute to a more efficient enrollment process. The dashboard remains a valuable tool for ongoing analysis and strategic decision-making.

### Recommendations:

1. Implement a hybrid learning model to address the preference for offline classes.
2. Schedule refresher sessions for the team under JNR1011MG to enhance their performance.
3. Encourage all managers to maintain a high call volume to improve overall conversion rates.

### Next Steps:

1. Collaborate with the curriculum team to implement a hybrid learning model.
2. Schedule refresher sessions for JNR1011MG and monitor subsequent performance.
3. Organize knowledge-sharing sessions to disseminate effective strategies from high-performing managers.

This report aims to guide the team towards strategic actions and improvements in the enrollment process, ultimately contributing to higher conversion rates and business success.
