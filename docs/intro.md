---
sidebar_position: 1
---

# Outline
An application that creates a 4-year plan for students and is well adapted based on the courses that are taken each quarter.

Santa Monica College and Miracosta College both use MyEdPlan which is a service that is essentially the same but is older tech. Based on the courses in the student’s curriculum , a planner is created, and even shows the status of their degree. You could watch the video here: https://www.miracosta.edu/student-services/counseling/myedplan.html

## Audience
Students are the main audience of the application, but it is to be assumed that it’s moderated by UCSC faculty

## Courses Data
There will be a web scraper that will scrape for the courses and time. An alternative is to ask David Lee for the script of how the courses are taken.

What are the requirements to make a 4-year plan for a student?
- Year of first enrollment
- Major
- Minor (Perhaps a feature to show overlapping classes for more optimized planning?)
- If it’s a transfer, then upper-division courses are shown for a 2-year planning period
  - This could be very popular for STARS


## Tech Stack (Monolithic):

### Front-end:
- React
- Material UI
- Tailwind CSS

### Backend:
- AWS Authentication
- AWS DynamoDB

## Design
Figma: https://www.figma.com/design/jcEtqjO168dIGZgMZbDODH/Project-Notes?node-id=0-1&t=cuqWA0Vii5V6JC56-1

We could have themes to give off a “planner” look to the user, similar to an actual planner:
https://www.papier.com/us/stationery/academic-year-planners/
