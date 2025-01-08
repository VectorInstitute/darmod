---
layout: page
title: Program Team
description: A listing of all the program staff members.
---

# Program Team

## Program Leads

Questions about the program format, arranging accommodations, extensions, comments about the program, and all other matters.

{% assign program_leads = site.staffers | where: 'role', 'Program Lead' %}
{% for staffer in program_leads %}
{{ staffer }}
{% endfor %}

## Instructors

Questions about Tuesdays' content or general questions about applying AI in industry.

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

## Technical Advisors

Questions about Wednesdays' content, assignments or company use cases.

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

# Communicating With Your Program Team

During the program, the program team will interact with you on various matters using the following methods of communication:

- Announcements: The program leads will use Announcements on the program home page to provide you with reminders and regular updates
- Email: If you have a conflict that prevents you from completing the program requirements, or have a question concerning a personal matter, you can send the program team a private message by email to [darmod@vectorinstitute.ai](mailto:darmod@vectorinstitute.ai)
- Slack: Your program team will also engage with you on Slack for questions and clarification about content. Please feel free to interact with your peers there. You may also ask questions for faster responses and for the benefit of the rest of the cohort. 
