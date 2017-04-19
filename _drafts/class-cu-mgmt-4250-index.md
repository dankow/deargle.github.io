---
layout: syllabus
#permalink: /class/cu/mgmt4250/
title: MGMT 4250 Sec 001 &ndash; Information Security Management
---

_Fall 2017_ 

<div id='nav-bar'></div>

Instructor
: Dave Eargle ([contact]({% link contact.md %})) 

Class
: Mon/Wed 12:30PM - 1:45PM 
: KOBL 375

Office Hours
: By appointment (Skype or Hangouts preferred)
 



# Course Information


## Course Description

This course is a broad introduction to the managerial issues of information security. Because security is multifaceted, the topics of the class range widely, including technical (e.g., cryptography), managerial (e.g., policy compliance), physical (e.g., door locks), and psychological (e.g., social engineering) issues. A key objective of the class is to develop a security mindset, in which one learns to think like an attacker for ways to exploit a system.


## Learning Outcomes

Develop working knowledge of methods of protecting data
: To gain a working knowledge of modern methods of protecting data: encryption, hashing, confidentiality, authentication, integrity, non-repudiation, certificates, and IP security.

Gain familiarity with attack vectors
: To become familiar with attack vectors that are commonly executed in attempting to access and compromise or steal data

Learn methods of attack prevention and detection
: To learn modern methods of attack prevention and detection: antivirus, firewalls, intrusion detection, and system hardening

Learn methods of threat modeling
: To learn state-of-the-art methods of threat modeling.

Develop a security mindset
: This goal will help you think like a security professional—how to identify threats like an attacker, and how to mitigate those threats.

Appreciate the broad disiciplines required for IS security
: This class will help you appreciate the broad disiciplines required for information security to work. We'll cover subjects as diverse as cryptology, physical security, psychology, and management.


## Materials

* Security Engineering 2e by Ross Anderson (legitimately available online for free)
* Secrets & Lies by Bruce Schneier (selected chapter will be made available)



## Certification Option

As an option, students seeking certification may replace the final exam by passing the Security+ certification or another certification approved by the instructor. You can substitute your score on the certification (plus an adjustment—5% for the Security+) for the final. For example, if you received an 85% on the Security+ exam you would receive a 90% for your final exam score.
 
To receive credit for the certification, a student must show evidence of having taken the certification exam by the last day of class. If a student doesn't show the instructor evidence of passing the certification by this date, then he/she will be required to take the final exam.



## Grading

<div markdown='1' style='width:40%' class='small'>

|                Item                | Points |
|------------------------------------|--------|
| Quizzes  |   70   |
| Labs | 200 |
| Participation | 40 | 
| Course Evaluation | 10 |
| Security Book | 100 |
| Security Films | 30 | 
| Midterm project |  175 |
| Threat assessment project | 175 |
| Final Exam | 200 | 
|=|=|
| **Total** |    **1000** |

| Extra Credit | Value |
|-|-|
| Security Movie for Extra Credit | Replace 1 quiz |
| Security Book for Extra Credit | Replace 1 lab | 
|=|=|

</div>



## Classroom Policies

### Participation Policy

Contribution will account for 5% of your final grade.  Most students will earn 80% of these points.  Students who are exceptional and go above and beyond in enhancing the classroom experience may receive a higher score.

The following list is not comprehensive, but rather an example of items weighted in the contribution category:

* Providing feedback on the class via the course evaluation
* Treating others with respect
* Showing courtesy for presenters (guest speakers, instructor, students)
* Participating in class discussions
* Arriving on time and not leaving early
* Not using technology inappropriately (distracting yourself or others)


### Team work

In this class, you will work in teams. As a result, review a short report on [team effectiveness]({{site.baseurl}}/class/general/team_effectiveness.pdf) and establish a team agreement [(sample agreement)]({{ site.baseurl }}/class/general/sample_team_agreement.docx). Give the instructor a copy of your team agreement by the end of the second week of classes.


### Freeloader policy

It occasionally happens in class and enterprise settings that someone in a group is not prepared to do his/her share. In the case of my classes, I recommend that the team give the freeloader one warning and then fire that person from the team. That person will then do group assignments individually or find another team to join. The team should notify me of the change in team composition immediately. I distribute a [form]({{site.baseurl}}/class/general/Peereval.docx) to assess team participation at the end of the semester. If a major disparity in team contribution is reported, I will adjust team project grades.


### Classroom Procedures

Students are welcome to use laptops in class for note taking and completing class exercises, exclusively.


### Late Work 

All assignments and projects are to be submitted on time or early, so plan accordingly. If you have to miss class please submit your assignment early. On VERY rare occasions, an exception may be granted, allowing the student to submit the work late with a 20% penalty. Under no circumstances will anything be accepted more than a week late.




# Assignments


## Labs

Labs are hands-on learning activities that will be begun in class and completed outside of class. Labs are typically due one week after they are introduced in class.

{% assign assignments = site.security_assignments | sort: 'number' %}
{% for assignment in assignments %}

* [{{ assignment.title }}]( {{ assignment.url }} )

{% endfor %}


## Midterm vulnerability assessment project

This is a group project. The midterm will be a vulnerability and penetration assessment report of a server. The report will be written for an upper management audience. Teams of students will be given an IP address of a server to assess for security weaknesses. The midterm report will be due two weeks later.

## Current event threat assessment

This is a group project. Teams will choose a recent security breach incident and report on it as if it just occurred. The report will summarize the incident and give recommendations for how to manage the threat. The report will also include a risk assessment of  other potential threats the chosen organization faces, along with recommendations for mitigating each identified threat. Deliverables include a written report and a presentation.


## Readings Quizzes

Most readings and videos on the schedule have associated quizzes. Quizzes are open book, open Internet and must be completed within 20 minutes.

Quizzes are due before class on the date due.


## Security Book

Read one of the books on the [Security Readings and Films list]({% link security-assignments/security-reading-and-film-list/index.md %}) by the last day of class. To receive credit, submit your report via a quiz. Indicate which book you read, whether you read the whole book, and give your brief reaction to it.


## Security Films

Two films are required viewing for this course: "Zeros Days" and "Citizenfour." You can watch these films with the class on the announced screening days, or on your own. To receive credit, complete one security films report quiz for each film. Simply indicate that you watched the whole film and give your brief reaction to the film.


## Extra Credit

You can **replace your lowest quiz score** by watching a second _security film_ from the [Security Readings and Films list]({% link security-assignments/security-reading-and-film-list/index.md %}) submitting a few sentences about what you thought about it.

Similarly, you can **replace your lowest lab score** by reading a second _security book_ from the [Security Readings and Films list]({% link security-assignments/security-reading-and-film-list/index.md %}) and submitting a few sentences about what you thought about it.


## Team evaluation

[This form](/{{ site.baseurl }}class/general/Peereval.docx) should be submitted **before the final exam.**



# Schedule


<div class='small'>
<table class='table table-condensed table-hover'>
    <thead>
    <tr>
        <th rowspan='2'>Week</th>
        <th rowspan='2'>Class</th>
        <th rowspan='2'>Date</th>
        <th rowspan='2'>Topic</th>
        <th colspan='3' class='text-center'>Activities</th>
    </tr>
    <tr>
        <th class='col-md-4'>Due Before Class</th>
        <th class='col-md-4'>In-Class</th>
        <th class='col-md-4'>Due by 11:59pm</th>
    </tr>
    </thead>
    <tbody>
{% for week in site.data.schedules.security %}

    {% assign weeknum = week[0] %}
    {% assign days = week[1] %}
    {% for day in days %}
     
    {% if forloop.last == true %}
        {% assign custom_css = 'border-bottom' %}
    {% else %}
        {% assign custom_css = '' %}
    {% endif %}
    
    {% if day.custom_css %}
        {% assign custom_css = custom_css | append: ' ' | append: day.custom_css %}
    {% endif %}
    
    {% if custom_css %}
        <tr class="{{ custom_css }}">
    {% else %}
        <tr>
    {% endif %}
     
    {% if forloop.first == true %}
            <td>{{ weeknum }}</td>
    {% else %}
            <td></td> 
    {% endif %}    
    
            <td>{{ day.class_num }}</td>
            <td>{{ day.date | date: "%a, %b %d"}}</td>
            <td>{{ day.title }}</td>
            <td>
                {% if day.due_before %}
                    <ul>
                    {% for due_before in day.due_before %}
                        <li>{{ due_before.name }}</li>
                    {% endfor %}
                    </ul>
                {% endif %}
            </td>
            <td>
                {% if day.assigned_today %}
                    <ul>
                    {% for assignment in day.assigned_today %}
                        <li>{{ assignment.name }}</li>
                    {% endfor %}
                    </ul>
                {% endif %}
            </td>
            <td>
                {% if day.due_tonight %}
                    <ul>
                    {% for due_tonight in day.due_tonight %}
                        <li>{{ due_tonight.name }}</li>
                    {% endfor %}
                    </ul>
                {% endif %}
            </td> 
        </tr>

    {% endfor %}
{% endfor %}
</tbody>
</table>
</div>

<br>
<br>
 
_This syllabus is a fork of one created by [Dr. Anthony Vance](http://anthonyvance.com/). Many thanks to Tony._