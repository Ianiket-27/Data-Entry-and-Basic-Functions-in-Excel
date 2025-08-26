# 📊 Data Entry and Basic Functions in Excel (Student Marks Example)

Managing student marks in Excel is simple yet powerful when combined with built-in functions. Here’s a quick guide:

# 🔹 Step 1: Create Column Headers

In Row 1, enter the following headers:

S.No. → Serial number of the student

Name → Student’s name

Tel, Hin, Eng, Mat, Sci, Soc → Marks in Telugu, Hindi, English, Maths, Science, and Social

# 🔹 Step 2: Enter Student Data

From Row 2 onwards, enter each student’s details.

One row = one student

Columns C → H contain marks

# 🔹 Step 3: Add Computed Columns (Optional but Useful)

Add extra headers:

Total → Sum of all subject marks

Average → Average of marks

(e.g., I1: Total, J1: Average)

# 🔹 Step 4: Apply Excel Functions

✅ Total Marks (per student):
=SUM(C2:H2)

✅ Average Marks (per student):
=AVERAGE(C2:H2)

✅ Total Marks (per subject):
For Telugu (C2:C6):
=SUM(C2:C6)

✅ Average Marks (per subject):
=AVERAGE(C2:C6)

✅ Minimum Marks (per subject):
=MIN(C2:C6)

✅ Maximum Marks (per subject):
=MAX(C2:C6)

# 🔹 Step 5: Use AutoFill

After writing a formula once, drag the fill handle (bottom-right corner of the cell) to copy formulas across rows/columns.

# 🔹 Step 6: Format for Clarity (Optional)

Bold headers

Apply cell borders

Use number formatting for marks

Add Conditional Formatting to highlight highest/lowest scores
