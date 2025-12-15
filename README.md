# students-mental-health-analysis-sql
Explored mental health survey data from a Japanese international university using SQL to examine how length of stay affects depression, social connectedness, and acculturative stress among international students. The analysis highlights patterns in mental health indicators using grouped averages and counts.

# Students Mental Health Analysis (SQL)

This project analyzes mental health survey data from a Japanese international university.
The goal is to explore how the length of stay in a foreign country affects the mental health
of international students.

The analysis focuses on depression, social connectedness, and acculturative stress.

## Research Context
The dataset is based on a 2018 survey of university students and reflects findings from
a published academic study indicating that international students may be at higher risk
of mental health difficulties.

## Dataset
- Table name: `students`
- Source: DataCamp (educational dataset)
- Database: PostgreSQL

### Key Columns Used
- `inter_dom`: International or domestic student
- `stay`: Length of stay (years)
- `todep`: Depression score (PHQ-9)
- `tosc`: Social connectedness score (SCS)
- `toas`: Acculturative stress score (ASISS)

## Analysis Performed
- Filtered international students only
- Grouped students by length of stay
- Calculated:
  - Number of students per stay duration
  - Average depression score
  - Average social connectedness score
  - Average acculturative stress score

## SQL Skills Demonstrated
- Data filtering with `WHERE`
- Aggregation using `COUNT` and `AVG`
- Grouping with `GROUP BY`
- Result ordering
- Data summarization for analysis

## Platform
This project was completed on DataCamp using a read-only PostgreSQL environment.

## Key Insights
- Mental health indicators vary with length of stay
- Social connectedness generally improves with time
- Acculturative stress tends to decrease for long-term students
