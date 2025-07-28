## Small program to parse class schedules and generate a formatted Word doc

---

# Usage:
'''bash
python class_schedule_constructor.py input_filename.txt

input_filename.txt: A text file containing one Python dictionary per line with keys like:

- "Course", "Day", "Time", "Room", "Professor", "Type of Activity"

---

# Output:
Creates a nicely formatted Word doc called Schedule.docx

# Requirements:
'''bash
  - pip install python-docx