Username: Manny Password: Gatica


Authentication:

Method	URL	Description

[POST]	/api/auth/register	Requires a username and password and phone-number/string. Registers a new user.

[POST]	/api/auth/login	Requires a username and password. Logs the user in and returns token.

Users: RESTRICTED

Method	URL	Description
[GET]	/api/users/plants	Returns an array of plant objects belonging to logged in user.

[GET]	/api/users/	Returns information about the user.

[PUT]	/api/users/	Updates User Information Requires same payload as registering

Plants: RESTRICTED

Method	URL	Description

[GET]	/api/plants	Returns an array filled with plant objects.

[GET]	/api/plants/:id	Returns a plant object with the specified plant_id.

[POST]	/api/plants	Requires nickname, species, h20, and user_id .

[DELETE]	/api/plants/:id	Removes the plant with the specified plant_id.

[PUT]	/api/plants	Requires nickname, species, h20, and user_id .

