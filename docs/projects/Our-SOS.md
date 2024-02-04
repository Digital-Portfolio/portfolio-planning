## Our SOS


- Your lifeline in times of crisis. The app provides accessibility using language translation—and Alerts users when an emergency is near them. It also includes AI help in case of crisis.

### Initial Idea
The Initial Ideation for the App was done by the D3 Students (Meelaud, Neema, and Parker), who we worked with to develop this app. The idea was to create a public safety app using the latest data and train AI to help people in Danger. The app also incorporated a translation feature for people with a native language different than English. We also added features like Friends, where users can ensure all their friends and family members are safe even though they might be in a different part of the world.

### Design of the Project
The D3 students created the design of the app; the design had three simple tabs for three different views for a dashboard, map, and settings page.

### Development
In the project's development, the team decided creating an app for mobile devices would be better. So, the app's front end used Expo, Typescript, and Tailwind. As it is a public safety app, we wanted the best performance and created a Backend in GO. I mainly worked on the Backend, where I pulled data from different APIs using a cron job and Stored it in a Redis Storage. For user data management, we used PostgreSQL. The images were uploaded to Azure Blobs. We ensured that only the emergencies near the user location or their friends were shown for optimization.

### Take Away
I learned about Expo, Golang, and cache. Many things were built on top of my previous knowledge, but there were things I learned about Go's concurrency model and validating/invalidating the cache. I also experienced mobile development, where we converted a mobile Figma design to an actual working app that provides value to users. Also, we had a big team of 8 people, so communication was the key, and I definitely improved my communication skills while working in a development team.

### Things to improve
The things to improve would be taking smaller steps and incremental development and deployment. Some parts of the app would not make it to the final version as they were breaking things. If we had caught them early on, we would have development would have been much smoother. But overall, the project turned out great, and I am thankful for everyone who contributed.