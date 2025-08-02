**Student Enrollment System (MS Access Application)**
A user-friendly Student Enrollment System built using Microsoft Access (.accdb) and VBA. It allows registering students, managing course enrollments, applying validations, and generating reports.

📌 **Features**
Student Registration Form
Includes fields: Full Name, Gender, DOB, Phone Number, Email, Course ID, Enrollment Date

➤ **Validations:**
Gender: Dropdown (Male, Female, Other)
DOB: Must be ≥ 01-01-1900 and student must be at least 18 years old
Phone Number: Must be 10 digits
Email: Must follow format like abc@xyz.com
CourseID: Selected from courses table
Enrollment Date: Defaults to today
VBA popup: "Welcome to the Student Enrollment Form"

**Courses Table**
Fields: CourseID (AutoNumber), CourseName (Short Text)
Linked to Students table (One-to-Many via CourseID)

**Queries**
qry_StudentsByCourse: Shows students enrolled in each course
qry_StudentsByGenderAndCourse: Filters by gender and course
qry_StudentCountPerCourse: Displays number of students per course

**Report**
rpt_StudentEnrollmentSummary: Displays grouped student records by CourseID

🛠 **Technologies Used**
Microsoft Access (.accdb)
VBA (Visual Basic for Applications)
SQL (for queries)

**Contact**
For suggestions or feedback, connect via https://www.linkedin.com/in/sai-madhavi-latha-maddali/
