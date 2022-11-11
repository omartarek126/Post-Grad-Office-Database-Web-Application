
# PostGrad Office Database Web Application

The GUC has a postgrad office responsible for masters and PhD. programs. The postgrad office wants to create a system to keep track of students doing their postgrad studies as well as manage the process of students taking prerequisite courses for the postgrad studies. Students can register for their master or PhD through this system.

### This project consists of 4 main components:
1. Student Component (GUCian or nonGUCian)
2. Supervisor Component
3. Admin Component
4. Examiner Component

Each component has its own webpage with its own unique functionalities. Depending on the email and password entered at the login page, the user is redirected to the appropriate webpage.

### As a Student I can:
- View my profile that contain all my information
- add my telephone number(s)
- List all my theses in the system
- List all my courses and their grades in the system (for nonGUCian students only)
- Add and fill my progress report for my on going thesis
- Add a publication and link it to my on going thesis

### As a Supervisor I can:
- List all my students names and years spent in the thesis
- View all publications of a student
- Add a defense for a thesis and add examiner(s) for the defense
- Evaluate a progress report of a student, and give evaluation value 0 to 3
- Cancel a Thesis if the evaluation of the last progress report is zero

### As an Admin I can:
- List all supervisors in the system
- List all Theses in the system and the count of the on going theses
- Issue a thesis payment
- Issue installments as per the number of installments for a certain payment every six months starting from the entered date
- Update the number of thesis extension by 1

### As an Examiner I can:
- Edit my personal information, my name and field of work
- List all theses titles, supervisors, and students names I attended defenses for
- Add comments for a defense
- Add grade for a defense
- Search for thesis where the title contains the entered keyword

## Technologies Used:
- HTML
- CSS
- C#
- ASP.NET
- SQL
