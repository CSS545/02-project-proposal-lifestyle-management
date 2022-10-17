[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=8933004&assignment_repo_type=AssignmentRepo)
Hint: [Markup Guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

# Project Name - Lifestyle Management App
**Project Members** - Gagneet Sachdeva, Greeshma Parimi, Purva Patil

**Version** - 1.0

## Summary of Project
Around 70% of adult population rely on digital calendar to manage daily activities, out of which 46.7% rely mostly on mobile calendars. We propose an app which not only alerts users about scheduled work meetings, but also reminds them to take short breaks between long working hours. This will help us improve productivity and maintain healthy lifestyle . This app allow users to add common recurring events like meal hours, exercise hours and other personal activities.

## Project Analysis
### Target Audience
**Age group** - Primary(18-60)

**Occupation** - Students/Working Professionals/Home makers

**Why?** - The people in this age group usually tend to forget many things while working, so these people are our potential customers

**Plan to reach target audience** - Advertisements, collaborating with Professional Ogranizations

### Primary Purpose
To help the adults who find it difficult to manage their daily routine both personally and professionally, and maintain a healthy life by adding their daily schedule to the app while reminding the users to take short breaks.


### Value Proposition
It reminds the users about  their daily personal & professional events with a reminder/alert.

The app will help users to reduce their stress and increase the productivity. 


### Success Criteria
Number of people actively using the app, for eg. people customizing their schedule in the app

Number of downloads from the app store 

Reviews and Ratings of the application


### Competitor Analysis
Google Calendar - It helps to schedule the meetings, events and get the reminders. 

Strengths/Weakness - ‘Google’ brand has a strong user base and so does the calendar, but it doesn’t have a break management feature which would remind users to take breaks in between work hours.

### Monetization Model
Integrating the app with professional organizations to increase the productivity of the employees by scheduling the events of their daily lives on the app.

Ads regarding the type of tasks in the to-do list, which suggests the user of near by options to fulfill the task. Fo eg. User wants to go to a gym, we can recommend the near by options for gym through ads.


### Initial Design
**Scope:**

Users can add their own breaks/the app can set the default breaks

Users can add the repeating events beforehand, may be months before. For eg. gym time, meal timings

Option to allow the users to disable the app/reminders for a day(if they feel like skipping the schedule)

Users can also add personal notes as reminders.

**Limitations:**

If the user choose to use the app without signing in, it won’t be able to restore any of its data from the cloud.


### UI/UX Design
User can either log in through Log-in Page or continue without logging in.

Dashboard which includes options like Breaks, Current day, Events, etc

Screen which enables the users to customize the breaks and add the days/timings.

Screen to show current day’s schedule including the work schedule imported from user’s gmail account, which will also allow users to view the monthly schedule.


### Technical Architecture
Data structures - Arrays for processing user events

Storage - Store the events in the database(SQLite)

Cloud - To store user settings & data for restoration

3rd party services/APIs -  Gmail/Google Calendar


## Challenges and Open Questions
Integration with Google API

Our app is targeting to give an option of using the app without logging-in. Users can create their schedules offline too. 

If the user deletes the app and re-installs, how are we going to restore the user settings.[Proposed Solution: Settings can be saved based on user’s device id which is unique.]

