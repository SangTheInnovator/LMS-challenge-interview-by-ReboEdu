# LMS-challenge-interview-by-ReboEdu
You are a fullstack developer and you have an idea about creating a Learning Management Platform for your school. This will help your school manage students, schedules, courses, and edit course content better and more efficiently. We have a challenge for you to build your own product and ship it to your school as an MVP product.

Divide your product system architect to two part:

### Backend-site
We should to deploy the Moodle LMS on the server and return the API for external use. You can check more informations how to deploy it and generate the tokens for the API. Link document [https://docs.moodle.org/501/en/Main_page]

### Frontend-site
Create the frontend can get the API from moodleLMS and have features: courses list, courses detail, students informations, schedule, and courses editing. Also we need have the sign in and sign out to see the course: Please remember have roles for accounts - students and teachers. And we should have the basically routing pages like this:
1. Home  [https://elearning.3rdwavemedia.com/moodle/lumo/moodle-5/6/my/]
2. Courses [https://elearning.3rdwavemedia.com/moodle/lumo/moodle-5/1/local/staticpage/view.php?page=catalog-1] -> Course detail [https://elearning.3rdwavemedia.com/moodle/lumo/moodle-5/6/local/staticpage/view.php?page=course-2] -> Course editing page (this is only use for role teachers) -> it will route to the moodle LMS and can edit the course.


[![https://rebo.edu.vn/icons/logoREBOdark.svg](Image URL)]
