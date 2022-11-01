# Liveify
A web app that allows you to create custom concert playlists from spotify!

# 🎬 Video Demo 
[![Demo](https://img.youtube.com/vi/bUbI6wvxlF0/0.jpg)](https://www.youtube.com/watch?v=bUbI6wvxlF0)

# 💡 Inspiration
Over the past six months, the number of confirmed cases of coronavirus has risen to over 3.3 million in the United States alone. As the world battles COVID-19, the entertainment industry has been put on pause. In an effort to prevent spreading the virus, many prominent venues, like Carnegie Hall and Lincoln Center, and artists, like The Weeknd and Billie Eilish, have canceled their concert tours. Liveify will create personalized, live concerts for users to listen to from home. 

# 🎵 What it does
User interaction has three main parts.  First, the user must authenticate and sync up their Spotify account with Liveify. Second, the user inputs the desired mood/positivity, danceability, and energy of their concert. Liveify will take the user inputs and auto-generate a personalized concert playlist on the user’s Spotify account. Third, the user can relax or dance to their live concert!

# 🔨 How we built it
Front End: HTML | CSS
APIs: Spotify API
Back End: Python | Flask | Tekore 

The majority of Liveify is built in Python with Flask, and we used HTML/CSS to build the UI. The mood/positivity, danceability, and energy metrics were accessed through the Spotify API using a Python library called Tekore. 

# 😓 Challenges we ran into
Before implementing Tekore, we tried using Spotipy at first. For 3 hours, we were trying to pass Strings as Floats since we forgot to cast, simply because we are noobs. Spotipy also caused later issues with user authentication, so we pivoted and used Tekore instead. 

# 🌟 Accomplishments that we're proud of
This was our first time creating a web app and using an API, so we’re pretty proud of pulling everything together and creating a useful/functional product!

# 🧠 What we learned
Since we are both not too experienced with hackathons yet, we learned lots about time management during a hackathon as we went through so many ideas and iterations. 

# What's next for Liveify🎶
Next, it would be nice to expand the library from which Liveify pulls songs from, increase the accuracy of its algorithm, and improve the UI. Then, we hope to put Liveify out for everyone to use, which means deploying it to the web. 


 Built with
	Python, Flask, APIs, CSS, HTML, Tekore.
