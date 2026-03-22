# Open-University-Student-Success-Analysis
Open University Student Success Analysis
Kanche Susmitha | Data Analyst
Tools: Python · Pandas · NumPy · Matplotlib · Seaborn · SciPy · Tableau

🎯 Business Problem
The Open University needed to move beyond surface-level engagement metrics. Raw click and login data could not explain why students with high activity still withdrew, or why some achieved strong results with minimal effort. The goal was to identify at-risk students early and understand what actually drives academic success.

📐 Metrics Designed
Metric Definition:
Academic Performance (AP): Normalised weighted average of assessment scores
Learning Effort (LE): Normalised total VLE clicks across the module
Academic Success Efficiency (ASE): AP ÷ LE — how effectively effort converts into results

👥 Student Segments Identified
Segment Profile :
Efficient LearnersHigh ASE, low effort
Cognitive Overload Risk: High effort, low efficiency — 50% of students
Disengaged: Low effort, low performance
Struggling Performers: High effort, still low scores

📊 Key Findings

1. Students with low-to-medium clicks showed the highest ASE — quality beats quantity
2. Early engagement alone does not prevent withdrawal — CCC module had 71.9% withdrawal despite high activity
3. Hypothesis testing confirmed ASE differs significantly between successful and at-risk students (t = 54.01, p < 0.001)


📈 Tableau Dashboard
🔗 https://public.tableau.com/app/profile/kanche.susmitha4144/viz/OpenUniversity_17741590894190/OpenUniversityStudentSuccessandEngagementAnalysis

📁 Dataset
Source: OULAD — 7 tables: studentInfo · studentRegistration · courses · assessments · studentAssessment · studentVle · vle
