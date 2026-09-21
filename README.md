# Offer-Radar

**Project:**                   Coworking with Claude to search for and process open job postings based on specified criteria (artifact + scheduled task).

**Consumer:**                  Personal Project

**Program languages:**         No coding at all

**Description:**               Sometimes I get an irresistible urge to engage in the old-fashioned task of searching for open job positions, creating resumes and cover letters tailored to them, and filling out application forms on companies’ career pages. This involves keeping track of applications sent, rejections received, scheduled interviews, and so on. It’s a long, tedious, and laborious process. But fortunately, there’s now a great helper for all of this — Claude from Anthropic.

________________________________________
*What I Did:*

At the coworking space, I explained to Claude my task of creating a dashboard (an interactive spreadsheet) that I would use to track job openings.
I also provided him with a list of companies I was interested in and the criteria for selecting open positions at those companies, which, in general terms, were as follows:

 - Location (SF Bay Area) 
 - Sample range of roles (based on my experience and skills)
 - Salary range (positions without a salary listed will not be considered)
 - Exceptions on role screening (security, too high or too low positions, etc.)

________________________________________
*What Claude Did:*

 - Created a collection to store data in the built-in storage
 - Created a dashboard in the form of a private, interactive web page
 - Scanned the career pages of the specified companies, identified the possibilities and limitations for parsing open job postings, and found ways to access them via APIs, available mirrors, etc.
 - Created a task for the built-in scheduler to periodically compile a list of suitable job openings (with possible personal exclusions and additions)

________________________________________
*What Claude Does:*

 - Scans companies' career pages according to a set schedule or on an ad hoc basis, in response to my specific requests
 - Adds suitable job openings to the collection, checking for duplicates with those previously uploaded
 - Creates resumes and cover letters tailored to each specified position (upon my request)
 - Fills out the fields and makes the necessary selections from the lists on job application forms
 - Leaves the forms for me to do a final check and click the "Apply" button
 - Analyzes job openings and provides recommendations based on a comparison of the position's requirements with my professional experience

________________________________________
*Identified Limitations:*

 - It works very poorly and slowly with Google Drive
 - Cannot attach documents to forms on their own


**Results / Key Findings:** The process of searching for job openings, analyzing and organizing them, preparing resumes and cover letters, filling out forms, and keeping track of all this stuff  has turned from a tedious routine into an exciting game.

The repository contains a file with instructions for the task scheduler, written by Claude based on my requests.


**Illustration:** The dashboard in light and dark themes

[![Watch the video](demo_preview.png)](https://github.com/dmitrii-govorukhin/Offer-Radar/blob/main/dark_theme.png)

[![Watch the video](demo_preview.png)](https://github.com/dmitrii-govorukhin/Offer-Radar/blob/main/light_theme.png)
