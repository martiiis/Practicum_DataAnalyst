# Project description

You work as a video ad analyst at the Sterling & Draper advertising agency. You devote a lot of time to analyzing trending videos on YouTube to determine what content deserves marketing attention.
Each video has a specific category (Entertainment, Music, News & Politics, etc.), region, and trending date.
A video can be in the trending section for several days in a row.

# Table of Contents

**Part 1. Drawing Up Technical Requirements**

Every week, the new employees Melanie and Ashok ask you the same questions:
What video categories were trending last week?
How were they distributed among various regions?
What categories were especially popular in the United States?
In your sixth week on the job, you decide that it's high time the process were automated. You're going to make a dashboard for Melanie and Ashok.

After talking to the managers and database administrators, you've drawn up brief technical requirements:
- Business goal: analyze trending-video history on YouTube
- How often the dashboard will be used: at least once a day
- Target dashboard user: video ads planning managers
- Dashboard data content:
    - Trending videos from the past, broken down by day and category
    - Trending videos, broken down by countries
    - A table of correspondence between categories and countries
- Parameters according to which the data is to be grouped:
    - Trending date and time
    - Video category
    - Country
- The data:
    - Trending history — absolute values with a breakdown by day (two graphs: absolute numbers and percentage ratio)
    - Events, broken down by countries — relative values (% of events)
    - The correspondence between the categories and countries — absolute values (a table)
- Importance: all graphs are equally important
- Data sources for the dashboard: the data engineers promised to create an aggregate table called trending_by_time. Here's its structure:
    - record_id — primary key
    - region — country/geographical region
    - trending_date — date and time
    - category_title — the video category
    - videos_count — the number of videos in the trending section
- The table is stored in the data-analyst-youtube-data. database, which was created especially for your needs
- Data update interval: once every 24 hours, at midnight UTC
- Graphs, dashboard controls, and their arrangement:


**Part 2. Building the Dashboard -- Tableau**


- The date and time filter and country filter should modify all of the dashboard's graphs. Note that the interaction history graphs "Trending History" and "Trending History, %" should have date and time along the X axis. "Trending History" should have the number of videos in the trending section (the videos_count field) along the Y axis, and the other graph should have the percentage there.
- To build the dashboard, complete the following steps:
- In Tableau Public, use trending_by_time.csv (see the bottom of this page to download) to create a dashboard modeled on the draft.
    - Publish the dashboard on the Tableau Public server. Make sure it's available for the entire internet: try opening it in several browsers. If it isn't accessible, the reviewer won't be able to check it.
- Use your dashboard to answer the questions the managers asked you:
    - Which video categories trended most often?
    - How were they distributed among regions?
    - What categories were especially popular in the United States? Were there any differences between the categories popular in the US and those popular elsewhere?

Prepare a brief presentation containing a report (answers to these questions and graphs).
