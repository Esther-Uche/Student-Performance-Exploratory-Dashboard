# Student-Performance-Exploratory-Sql-Excel-Dashboard



## **SQL Data Analysis Project by Uchechi Esther Nwaoha**

![Student Analysis Dashboard](./Student_Analysis_Dashboard.png)

---

## 📘 Project Overview

As humans, we have different belief and assumptions. However, What if everything we assume about student performance is wrong?

Most people tend to believe that **English is easier to ace** than Mathematics due to it many complex calculations and formulas. We often assume **older students (Grade 12) are more disciplined and academically smart** with school works and attendance but we rarely question if **extracurricular activities help or hurt** academic outcomes.

This **Student Performance Exploratory Project** provides a comprehensive SQL-driven analytics of academic performance, attendance patterns, and extracurricular participation at Tofunmi Senku Academy.  By leveraging SQL for complex data extraction and visualization tools for insight discovery, this project demonstrates advanced SQL capabilities from basic aggregations to complex subqueries to uncover actionable insights for school administrators, teachers, and policymakers.

Using a database of **250 students** across Grades 9–12,This SQL project tested assumptions and the outcoming were overwhelming. I analyzed **academic scores, attendance patterns, and extracurricular participation** to uncover what really drives student success. The findings challenge common beliefs and provide actionable recommendations for school administrators.



---

## 🎯 Objectives

- **Contest Established Beliefs:** Evaluate if common beliefs about student performance hold up against data
- **Identify At-Risk Groups:** Carefully select grade levels and study groups with attendance challange and provide timely assistance.
- **Acknowledging Excellence:** Recognize top performing students across all subjects and make them placeable for scholarships and awards
- **Backup Tactics:** Establish data-backed advice for attendance improvement, intervention and awards.
- **Extracurricular Influence:** Understand and explain how activities like Sports and Music can affect academic outcomes.


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

 and isolated top performers for scholarship consideration.

Attendance Correlation: Analyzed how study group discipline and extracurricular involvement (Sports, Art, Music) impact attendance rates.

Gender Performance Gap: Conducted a comparative analysis of scores across genders to ensure equity in academic support.

Targeted Intervention: Isolated "Grade 12" and specific study groups that fell below the school-wide attendance average for administrative review.


---

### 2. 🎓 Grade 12 Has the Lowest Attendance — The Senior Slump

| Grade Level | Average Attendance |
|-------------|--------------------|
| Grade 10 | 81% |
| Grade 11 | 80% |
| Grade 12 | **78%** |
| Grade 9 | 70% |

> **Expectation:** A large audience of people believe that people in higher grade are academically smarter than the lower grade and as such, expect a higher attendance but this data says otherwise.
> **The data says:** Grade 12 has the **lowest attendance** among non-freshman grades (79%).

**Reasons?** School project? Work? Job interviews? College applications pulling focus? All of these does'nt give *reasons* — but assumptions which raises critical question for school leadership: *What's happening to our seniors?*

---

### 3. 🧒 Grade 9 Defies Expectations — Highest Attendance of All

| Grade Level | Average Attendance |
|-------------|--------------------|
| **Grade 9** | **70%** (but wait — read the note below) |

> **Correction from the data:** Grade 9 actually has **higher attendance than all other grades** when examined properly.

This is the most surprising finding. The youngest students — new to the school, still adjusting — are showing up more consistently than their older peers. **Why?** Possible explanations:
- Stronger homeroom mentorship
- Parents more involved with younger students
- Less absenteeism due to part-time jobs or external commitments

**Recommendation:** Interview Grade 9 students and teachers to extract best practices that can be applied to Grade 12.

---

### 4. ⚽ Sports vs. Music: Attendance Gap

| Extracurricular Activity | Average Attendance |
|--------------------------|--------------------|
| **Sports** | **81%** |
| Plot Area | 80% |
| **Music** | **70%** |

> **Insight:** Students in Sports attend 11% more often than students in Music.

This doesn't mean Music limits attendance but it's a strong correlation worth investigating as to why Sports students have better attendance. Is it discipline? Does Music rehearsal scheduling conflict with morning classes? Does Music concert and sessions limit attendance?


### 🛠 Technical Stack
**Database**: MySQL

**Language**: SQL (Joins, CTEs, Subqueries, Aggregate Functions)

**Visualization**: Excel (Dashboarding)

**Concepts Used**:  Data Aggregation: GROUP BY, AVG, SUM, COUNT.

**Connecting students**: scores, attendance, and extracurricular tables.

**Advanced Filtering**: Subqueries for school-wide average comparisons and HAVING clauses for conditional logic.

---

