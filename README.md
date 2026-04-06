# Student-Performance-Exploratory-Sql-Excel-Dashboard
It explains a school academic record and decline and the proficiency in use of tools like SQL and Excel



## **SQL Data Analysis Project by Uchechi Esther Nwaoha**

![Student Analysis Dashboard](./Student_Analysis_Dashboard.png)

---

## 📘 Project Overview

As humans, we have different belief and assumptions. However, What if everything we assume about student performance is wrong?

Most people tend to believe that **English is easier to ace** than Mathematics due to it many complex calculations and formulas. We assume **older students (Grade 12) are more disciplined and academically smart** with school works and attendance but we rarely question if **extracurricular activities help or hurt** academic outcomes.

This **Student Performance Exploratory Project** is a comprehensive SQL-driven analytics of academic performance, attendance patterns, and extracurricular participation. This project demonstrates advanced SQL capabilities from basic aggregations to complex subqueries to uncover actionable insights for school administrators, teachers, and policymakers.

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
| `students` | Demographics, grade level, study group, gender (250 students) |
| `scores` | Subject scores: Math, Science, and English per student |
| `attendance` | Daily attendance percentage per student |
| `extracurricular` | Activity participation (Sports, Music, etc.) |

---

## 🔍 The Surprising Truth: Key Insights

### 1. 📐 Math Leads the Pack — Yes, Math

| Subject | Average Score |
|---------|---------------|
| **Mathematics** | **69.91** |
| Science | 69.83 |
| English | 69.82 |

> **Many believes that:** English is easier to assimilate and score high in.
> **The data says:** Math had the **highest average score** across all students.

This objects our thought on subject difficulty. Are our teaching methods in English less effective? Is English more difficult to assimilate? Or are students simply more confident in Math? Either way, this is a conversation starter for the academic board.

---

### 2. 🎓 Grade 12 Has the Lowest Attendance — The Senior Slump

| Grade Level | Average Attendance |
|-------------|--------------------|
| Grade 10 | 81% |
| Grade 11 | 80% |
| Grade 12 | **78%** |
| Grade 9 | 70% |

> **What you'd expect:** Grade 12 students, being oldest and most mature, would have the best attendance.
> **The data says:** Grade 12 has the **lowest attendance** among non-freshman grades (79%).

**Why?** Senioritis? Job interviews? College applications pulling focus? The data doesn't answer *why* — but it raises a critical question for school leadership: *What's happening to our seniors?*

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

This doesn't mean Sports *causes* better attendance — but it's a strong correlation worth investigating. Do Sports students have better discipline? Does Music rehearsal scheduling conflict with morning classes?

---

