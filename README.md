
# Student Scores: Find the Highest Score

## Description

This Python script identifies the highest score from a list of student test scores. It does this by iterating through each score in the list and comparing it to the current highest score found.

## How It Works

1. A list named `student_scores` contains multiple integer values, each representing a student's score.
2. A variable `highest` is initialized to `0`. This will keep track of the highest score as the loop progresses.
3. The script loops through each score in the `student_scores` list.
4. During each loop iteration, it checks if the current `score` is greater than the current `highest`. If so, it updates `highest`.
5. After the loop completes, the highest score is printed.

## Code

```python
student_scores = [150, 142, 185, 120, 171, 184, 149, 24, 59, 68, 199, 78, 65, 89, 86, 55, 91, 64, 89]

highest = 0
for score in student_scores:
    if score > highest:
       highest = score
print(highest)
