# Phone Restriction Impact Study — Behavioral Analysis in a Controlled Learning Environment

## Overview

This project investigates the impact of phone access on student performance, focus, and sleep within a structured academic environment.

The study simulates conditions similar to a disciplined learning setting, where phone usage is restricted, and evaluates how reduced digital distractions influence academic outcomes.

---

## Research Question

Does restricting phone access improve student performance and focus?

---

## Hypothesis

Students without access to phones will:

* demonstrate higher levels of focus
* achieve better academic results
* experience changes in sleep patterns

---

## Data

A dataset was constructed to compare two groups:

* `phone_access = 0`: students without phone access
* `phone_access = 1`: students with phone access

Features included:

* `study_hours`: time spent studying
* `sleep_hours`: duration of sleep
* `focus_level`: self-reported concentration level
* `exam_score`: academic performance

---

## Methodology

### Experimental Design

The dataset represents a simplified comparison between two groups under different conditions:

* controlled environment (no phone access)
* unrestricted environment (phone access allowed)

---

### Visualization

Box plots were used to compare distributions between groups:

1. Phone Access vs Exam Score
2. Phone Access vs Focus Level
3. Phone Access vs Sleep Hours

This approach highlights differences in central tendency and variability.

---

## Results

### Academic Performance

Students without phone access achieved significantly higher exam scores:

* stronger consistency
* higher median performance

---

### Focus Level

A clear increase in focus levels is observed in the no-phone group:

* fewer distractions
* improved concentration during study time

---

### Sleep Patterns

Students with phone access tend to sleep more, but:

* increased sleep does not translate into better performance
* quality of focus appears more important than quantity of rest

---

## Key Insights

* Reduced phone usage is strongly associated with improved academic outcomes
* Focus plays a critical mediating role between environment and performance
* Digital distractions can negatively impact learning efficiency

---

## Limitations

* Small sample size
* Synthetic dataset (not collected from real participants)
* Focus level is subjective
* No statistical significance testing applied

---

## Future Work

* Collect real-world data from students
* Conduct A/B testing in actual classrooms
* Apply statistical tests (t-test, p-value analysis)
* Build predictive models for performance
* Analyze long-term behavioral effects

---

## Tech Stack

* Python
* Pandas
* Plotly

---

## Repository Structure

```id="p1h2o3"
phone-restriction-impact-study/
│
├── notebook.ipynb
├── README.md
```

---

## Conclusion

The findings suggest that restricting phone access can significantly improve student focus and academic performance. While increased sleep is observed among students with phone access, it does not compensate for the negative effects of distraction.

This study highlights the importance of controlled learning environments in maximizing educational outcomes.

---

## Author

Independent research project exploring behavioral factors affecting student performance.
