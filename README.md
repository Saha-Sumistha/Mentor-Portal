# Problem Statement : Mentor Portal 
## A Portal specifically designed for mentoring students within IIT Madras BS Degree.
-------------------------------------------------------------------------------------
Students of the IITM Online BSc degree program are diverse, in terms of age, background and
experience. Due to the online nature of the program, there aren’t many opportunities to meet
and learn from seniors compared to traditional college experiences, where a lot of learning and
mentoring happens through interactions with seniors and alumni.
Your goal is to create an online student mentoring platform for the IITM BSc degree program
students. The platform should allow users to enroll as mentors. A mentor can be anyone
currently in the program (the system should admit alumni as well in the near future!) who would
like to provide mentorship to students. The platform should also allow other students to join, and
provide provisions for users to search and connect with mentors (through chat, audio/video call
etc.) based on their preference and expertise.
## Project Structure
 - Backend
    - env
    - APIs
        -User_APIs.py
    - instance
        - store.sqlite3
    - app.py
    - models.py
 - Frontend
## Users
* **Primary User** : Students of IITM BSc degree program as they will be directly benefited from
this.
* **Secondary User** : Alumni , Mentors , Instructors & professors of the Degree Program since
they will not be directly affected but will use this for helping others.
* **Tertiary User** : IITM Administration because they will not use the software although they will
be affected by the software usage.
We are considering specific roles as Users.
## Requirements 
*  Register and sign-in method for various roles like student, mentor,alumni,faculty etc.
* User dashboard for the feeds from other users.
* An advanced search Option to find any user / post with custom filters.
* User Profile
* Create / Edit / Delete/ tagging Posts
* Directly connect with mentors / Alumni.
* A feature to make groups.
* Super Admin controls.
* Calendar for every user to know about their availability.
* A Chat board to communicate with other users by multiple means such as audio,
video and text.
## User stories for the requirements:
* **Feature : Register and sign-in**
>  As a user of this software application,
>>  I want to register and sign-in options to access the application
>>>    So that it is only restricted to IITM administration.
* **Feature : Dashboard**
> As a student,
>> I want a dashboard
>>> So that I can see the feeds from my followed or suggested mentors and alumni,
over a landing page working as HomeDashboard.
* **Feature : Advanced search option**
> As a user,
>> I want a search bar over a specific discover page to help find me any users, and
a filter button
>>> So that when I click over it, it shows me a number of options, like to select from
any particular course, or like whether they are available to mentor.
* **Feature : User Profile**
> As a user,
>> I want a profile page to display my current details and an option to edit or
delete my account
>>> So that I can easily manage things without much effort.
* **Feature : Connecting with mentors**
> As a Student
>> I want an option to follow or directly connect to my preferred mentor or alumni
>>> So that I can get the feeds regularly from them.
* **Feature : Making groups**
> As a mentor or an alumni
>> I want to have an option to create a specific subject focused group
>>> So that I can answer my mentees common questions easily for that subject.
* **Feature : Super Admin controls**
> As an instructor, faculty or member of the POD team of IITMBsc
>> I want super admin access
>>> So that I can control the overall application if needed.
* **Feature : Calendar**
> As a user
>> I want to have calendar
>>> So that I can track my daily routine.
* **Feature : A Chat board**
>As a user,
>> I want a chatboard
>>> So that I can communicate with other users, when I open that board there
should be options at the top of the chat box for audio & video call, also a three
dot menu to change custom settings within that chat.
* **Feature : Creating Posts**
> As a user,
>> I want option to create,edit or delete my posts
>>> So that the information can be broadcasted to my followers or mentees. Also I
want a feature to set the priority & type of post like it may be an alert or
announcement post
