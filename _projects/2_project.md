---
layout: page
title: Crimson Code 2024
description: Social Connections - A Proximity based social networking app
img: assets/img/CrimsonCode24/SocialCOnnections2.png
importance: 2
category: work
---

Social Connections was my team's entry into the Crimson Code 2024 Hackathon. On a team with two other computer science majors from WSU Tri-Cities we developed a proximity based social networking app to help combat the lonliness epidemic on college campuses. It can be difficult for students with social anxiety to integrate into the community on college campuses, so we thought an app that connected students with other students looking for friends would help create a starting point. My contributions were mainly to the backend, I researched options that were compatible with Unity (the utility used to create the front end) and settled on SQLite as the best option. I then designed the database schema and wrote SQL queries to allow the front end to insert and retrieve data from the database. 

div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/CrimsonCode24/SocialCOnnections1.png" title="App main Screen" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/CrimsonCode24/SocialCOnnections2.png" title="Login Screen " class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/CrimsonCode24/SocialCOnnections3.png" title="User Profile" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Screenshots from the App
</div>

While we had a complete mock-up in Figma, for the competition we focused on programming 3 of the screens - the login page, main page showing neaby "students" and the user profile page. All of the data used by the app - user logins, lat and long coordinates, profile bios and other information is all stored in the SQLite database. Unity then uses a plugin to access the database and extract data. The map shown on the main screen is dynamically adjustable and resizeable and was created using the Mapbox API. 

I was very pleased with the progress we were able to make during the hackathon, we got a mobile app with 3 screens built for Android that we were able to test on actual hardware. In the future, we would like to interface with the android Bluetooth and NFC APIs to allow for a more granular selection of other users and introduce students to people passing by in the halls, the library, etc. 

