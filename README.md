# QuestApp-Backend <br> <br>
In this project I used java and spring boot for backend, react for frontend and MySQL as
database.
Details: First, I made the project requirements and api design. Then I created the entity,
repository and controller structures on the back end of the project. Then I coded the mappings of
the database objects, their relations with each other (such as one to one, many to one, many to
many). I set up the relationship between the Service layers and Controller classes. While saving
the objects to the database, I edited the validations and met the post request. Then I created the
component structures on the frontend. I fetch data from backend by making API call and show it
in frontend. I set the Parent-Child components and the data transfer (props) between them. On
the frontend, I have completed the homepage functionality (like, post, comment). On the
backend, I made auto increment id recognitions for our entities and created a response object for
the like, so that the required information on the frontend can be accessed. Then I implemented
Spring Security using JWT on the backend. After adding the necessary configs, I completed the
login and register endpoints. On the frontend, I made changes to the login/register page and
authentication in other components. Now, when making a request to the backend, the token
obtained while logging in is used. I gathered the common codes in the places where fetch is done
on the frontend side, under a service. Then, on the backend, I refreshed the access token with
the JWT refresh token. I implemented the changes on the frontend and completed the flow. I
added custom exception structure.
