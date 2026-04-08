# Student-Performance-Exploratory-Sql-Excel-Dashboard



![Student Analysis Dashboard](./Student_Analysis_Dashboard.png)

---

## 📘 Project Overview

As humans, we have different belief and assumptions. However, What if everything we assume about student performance is wrong?

Educational institutions often struggle to bridge the gap between student attendance and academic outcomes. Most people tend to believe that **English is easier to ace** than Mathematics due to it many complex calculations and formulas. We often assume **older students (Grade 12) are more disciplined and academically smart** with school works and attendance but we rarely question if **extracurricular activities help or hurt** academic outcomes.

This **Student Performance Exploratory Project** provides a comprehensive SQL-driven analytics of academic performance, attendance patterns, and extracurricular participation at Tofunmi Senku Academy.  By leveraging SQL for complex data extraction and visualization tools for insight discovery, this project demonstrates advanced SQL capabilities from basic aggregations to complex subqueries to uncover actionable insights for school administrators, teachers, and policymakers.

Using a database of **250 students** across Grades 9–12,This SQL project tested assumptions and the outcoming were overwhelming. I analyzed **academic scores, attendance patterns, and extracurricular participation** to uncover what really drives student success. The findings challenge common beliefs and provide actionable recommendations for school administrators.


---

## 🎯 Objectives

- **Contest Established Beliefs:** Evaluate if common beliefs about student performance hold up against data
- **Identify At-Risk Groups:** Carefully select grade levels and study groups with attendance challange and provide timely assistance.
- **Acknowledging Excellence:** Recognize top performing students across all subjects and make them placeable for scholarships and awards
- **Backup Tactics:** Establish data-backed advice for attendance improvement, intervention and awards.
- **Extracurricular Influence:** Understand and explain how activities like Sports and Music can influence academic outcomes.


---

## 🗄️ Database Schema

The analysis is built on a relational database with four tables:

| Table | Description |
|-------|-------------|
| `students` | Demographic info, (grade level, study group, gender (250 students)) |
| `scores` | Subject specific performance: Math, Science, and English per student |
| `attendance` |Term/Daily attendance percentage per student |
| `extracurricular` | Activity participation (Sports, Music, etc.) |



---

## 🔍 The Surprising Truth: Key Insights

### 1. 📐 Academic Benchmarking  — Math

| Subject | Average Score |
|---------|---------------|
| **Mathematics** | **69.91** |
| Science | 69.83 |
| English | 69.82 |

> Many believes that English is easier to assimilate and less complex than any science related course. Since English involves indepth reading, understanding and also written in language we can understand, people assume its less difficult to fail but.
> **The data says:** Math had the **highest average score** across all students. Although the results are closely in range but there's a noticeable slight difference.

This objects our thought on subject difficulty and raises concern regarding teaching method and student's assimilation. Are our teaching methods in English less effective? Is English more difficult to assimilate? Or are students simply more confident in Math? Either way, this is a conversation starter for the academic board.


---

### 2. 🎓 Grade 12 Has the Lowest Attendance — The Senior Flop

| Grade Level | Average Attendance |
|-------------|--------------------|
| Grade 10 | 79% |
| Grade 11 | 80% |
| Grade 12 | **78%** |
| Grade 9 | 82% |

> **Expectation:** A large audience of people believe that people in higher grade are academically smarter than the lower grade due to exposure and as such, expect more like a higher attendance but this data says otherwise.
> **The data says:** Grade 12 has the **lowest attendance** among non-freshman grades (78%) which is so appealing beacuse the lower grade who are new to the school are showing up more consistently than their senior peers.

**Reasons for Grade 12 Slump?** School project? Work? Job interviews? College applications pulling focus? All of these does'nt give *reasons*— but assumptions which raises critical question for school leadership: *What's happening to our seniors?*.

**Reasons for Grade 9 attendance incease:**
-Stronger homeroom mentorship
- Parents more involved with younger students
- Less absenteeism due to part-time jobs or external commitments
----

## 3. Applaudable Impact:
Although the higher grade (grade 12) has the least number of attendance, its average score is commendable as it possesss the highest average score with grade 9 being the least.

 **Reasons?** The higher grade might be bsy with school project, work or seminar workshop that makes them rarely available while the lower grade (Grade 9) might still be settling in, not famiiar with the school academeic syllabus, adjusting to the new environment and teaching method, stress, leading to slump in their average score.

This is the most surprising finding. The youngest students — new to the school, still adjusting — are showing up more consistently than their older peers. **Why?** Possible explanations:
- Stronger homeroom mentorship
- Parents more involved with younger students
- Less absenteeism due to part-time jobs or external commitments

**Recommendation:** Interview Grade 9 students and teachers to extract best practices that can be applied to Grade 12.

---

## 4. The "Extracurricular Stability" (Radar Chart)
The Attendance % by Extracurricular radar chart is very telling:

The shape is nearly a perfect diamond, meaning attendance is consistent across Art, Music, and Sports.

Observation: Students involved in "None" (no activities) don't seem to have significantly lower attendance than those in Sports.

The Problem: Usually, you'd expect "Sports" students to have higher attendance due to eligibility requirements.

The fix:

The Fix: Highlight that Extracurricular involvement at Tofunmi Senku Academy is a lifestyle not a mere requirement, as it maintains a high baseline across the board
----

## 5. Gender Neutrality
The Avg. Attendance by Gender pie chart is a perfect 50/50 split.

The Scores by Gender bar chart shows that Females slightly outperform Males in English (the gray bar), while Males are slightly higher in Math. 

Observation: The school has achieved excellent grade parity in terms of population and general attendance.

---
## 6.Attendance Baseline:
The school-wide attendance average sits at 80.16%, providing a stable foundation for academic delivery.


### 🛠 Technical Stack
**Database**: MySQL

**Language**: SQL (Multi-level Joins, CTEs, Subqueries, Aggregate Functions across four disparate tables to find the intersection of sport participation and attendance)

**Visualization**: Excel (Dashboarding)

**Concepts Used**:  Data Aggregation: Leveraging ORDER BY, LIMIT, GROUP BY, AVG, SUM, COUNT to automate scholarship and remedial lists.

**Connecting students**: scores, attendance, and extracurricular tables.

**Advanced Filtering**: Correlated Subqueries for identifying and comparing students scoring above dynamic school-wide average and HAVING clauses for conditional logic.



### 💡 Recommendations
Based on the data analysis:

Attendance Bonus: Students in "Group C" show higher attendance; the school should examine their method of  study and introduce them in "Group A". Also, since students with >90% attendance controls the high-score category, introduce a system that rewards individuals with perfect attendance.

Math Support and Grade 12 aid : From the data, it's evident that Grade 12 students are lagging in the school's average attendance thus, solutions should be provided for those showing a decline in Math scores like targeted weekend workshops, extra lessons or a dedicated counselor.

Balanced Lifestyle: The data suggests a relationship between sports participation and consistent attendance; increasing financial assistance for the gymnastic department may improve overall school presence.

