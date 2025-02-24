# NYC-complaints
This is the data dashboard challenge for the Winter 2025 BIS 412 Advanced Data Visualization course. The challenge uses data from New York City's 311 complaint data to visualize the temporal and spatial aspects of common issues raised by residents.

# Overview

Challenge created by and made for the BIS 412 Advanced Data Visualization course at the University of Washington Bothell.

    📊 Challenge created by and made for the Winter 2025 BIS 412 Advanced Data Visualization course at the University of Washington Bothell.
    ✍️ Authored by Yared A, Sakaria D, and Mohamed M 
    🔍 Challenge review committee: Yared A., 
    🔍 Committee chair: Yared A.
    🛠️ Edited and supervised by Prof. Caleb Trujillo

# Description

The challenge is to develop an interactive dashboard that analyzes NYC 311 service requests from NYCOpenData. 
This dashboard's objective is to use historical and real-time data visualizations to give relevant insights to various stakeholders. By showing patterns and trends in service requests, decision-makers may improve response processes, allocate resources more efficiently, and identify problem areas. The dashboards aim to present exploratory data analysis or narrative-driven insights through visual media. The tasks to address our challenge have two options:

## Challenge A: Exploratory visualization
Create a platform that gives a broad overview of the data and supports user choice to explore specifics and details.

-    Make an interactive dashboard.
-    Create descriptive and comparison displays that enable users to filter the most common complaints overall by complaint type (using a reactive feature), borough, agency, time of day, day of week, or month  
-    Display comparisons over successive years to show the leading variables in car accidents
-    Provide a geographical map of where filtered complaints occur

## Challenge B: Storytelling through visualization
Create a platform that focuses on an issue, problem, or question, invites users to learn more, and presents specifics and details through user interactions

– Identify a central question or issue to tell a data-driven story about complaints
- Create an interactive dashboard that leads users through a story
- Find correlations and co-occurrences of different variables
- Provide insights into the missing data
- Provide some tools for users to download their data and images.

# Stakeholders
●	City Officials & Government Agencies: They need real-time insights for decision-making, resource allocation, and policy  
●	Community Boards & Local Leaders: Local stakeholders require neighborhood-level data to address recurring issues and to advocate for community improvements.
●	The General Public: Residents can stay informed about the frequency and nature of service requests, fostering transparency and community engagement.
Key Analytical Questions
The visual analytics techniques implemented in this dashboard should address the following questions:
●	Complaint Trends:
○	What are the most common types of complaints in NYC in 2024?
○	How do these complaint types vary across boroughs and change month by month?
●	Response Times:
○	How long does it usually take to close or review a request?
○	Are there variations in response times based on complaint type, borough, or the agency involved?
●	Agency Involvement:
○	Which agency receives the most 311 requests and what types of complaints do they handle most frequently?
●	Communication Channels:
○	What is the most common method  by which residents submit their 311 requests?
●	Temporal Patterns:
○	When are most service requests submitted throughout the day?
By answering this question, the dashboard helps uncover service bottlenecks and inefficiencies while also equipping stakeholders with the insights they need to take targeted action. With this data, they can implement strategic improvements to streamline operations and enhance overall efficiency.
 

Proposed Project Plan
The project will span 2-3 weeks with the following phases and tasks:

Week 1: Data Exploration & Design Ideation

-	Data Import
  -	Import the 311 dataset using an API or RSocratic with a filter to dates in the last year to represent
  - Clean the pre-processing of the data (e.g., parsing dates for created_date and closed_date).
- Initial Sketch:
  -	Brainstorm and sketch initial dashboard layouts.
  -	Define key metrics and determine which visualizations best address our analytical questions.
-	First Meeting:
  -	Discuss roles and responsibilities and set communication channels among team members.

Week 2: Prototype Development
●	Visualization Prototyping:
○	Create initial ggplot prototypes for:
■	Complaint type bar charts.
■	Monthly trend line charts.
■	Time-of-day histogram.
○	Start processing calculations for response times (difference between created_date and closed_date).
●	Iterative Feedback:
○	Present prototypes in team meetings.
○	Refine visualizations based on feedback.
Week 3: Dashboard Build & Integration
●	Dashboard Development:
○	Integrate the refined visualizations into an interactive dashboard framework Develop interactive filtering and drill-down capabilities.
●	User Interface & Aesthetics:
○	Focus on the overall layout, color schemes, and responsiveness of the dashboard.
○	Incorporate the sidebar with filtering options and a dynamic header.
Week 4: Testing, Feedback, and Deployment
●	User Testing & Feedback Collection:
○	Share the dashboard with a small group of target users (stakeholders, peers) to collect feedback on usability and insights.
○	Identify and fix any bugs or usability issues.
●	Final Adjustments & Deployment:
○	Finalize the dashboard design, ensuring all visualizations and interactive elements work as intended.
○	Deploy the dashboard on a hosting platform and ensure the live data connection is functioning.
●	Documentation & Final Presentation:
○	Document the design process, coding decisions, and any challenges faced.
○	Prepare a final presentation outlining the project’s insights and outcomes.
Possible Team Roles
●	Project Manager: Oversees the timeline and coordinates group meetings.
●	Data Analyst/Engineer: Handles data cleaning, transformation, and calculations.
●	Visualization Specialist: Develops the static and interactive visualizations.



