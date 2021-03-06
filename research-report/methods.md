## Methods

***ATMOS’ core focus will be to create a sociable experience for users***

By focusing on the 3 main aspects: Music, Environment, and Users. The main
functionality of the system is that it should be a hangout for people to
socialize and/or listen to music.

The system will be built using React, the javascript library, and Material-UI
for the frontend UI components like buttons and tables. The backend will be a
Postgresql database that will connect to the frontend. Specific APIs will need
to be installed to handle playing audio on the site. Regular playlists can be
handled using the React Audio Player API, but ATMOS is also planned to allow
Spotify and Apple Music, so there will need to be 2 unique APIs. These will be
the React Spotify API and the Apple Music.js API.

The development of ATMOS will be split into various parts. First would be to lay
down the foundation of the site and then set up a basic sphere and the main page
to look for spheres. Next will be to implement music support which can just be
the regular playlist for now as the Spotify and Apple support can come later.
The addition of animated backgrounds and a chat will come afterwards. When all
is set for a basic user’s sphere, then account creation, management, and
administrative privileges is next. Lastly will be to connect everything to the
backend database so the core functionalities are all functional and can be
tested.
