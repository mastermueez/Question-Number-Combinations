# Question Number Combinations
The notebook, **Question Assignment.ipnyb**, has been created to assign question numbers to students from a given number of questions. For instance, there could be 10 questions in total and 5 of those need to be assigned to each student. For this case, the concept of combinations has been used to generate a list of all possible combination of question numbers. Then, the lists are evenly assigned to each student. This is done by first reading a CSV file, containing IDs and names. Afterwards another CSV file is generated with a new column, containing the assigned question numbers.

## User Specific Vairables
The following variables need to be adjusted accordingly:
* **file_name**: the name of the original file
* **remove_cols**: columns that need to be dropped, leave list empty if not required
* **questions_count_total**: total number of questions to choose from
* **questions_count**: number to questions students will be assigned
