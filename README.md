# refactoring_badbank
Bad Bank Refactored

<h2>Description</h2>
<p>This project intents to show the flow of a three tiered application, starting form the front end all the way up to the back end, in order to connect the user interface to the database making requests by using express API, thereafter we will use authentication and authorization in order to grant access to the functionality of this application</p>

<h2>Installation Guidelines</h2>
<p>In order to start the project it is neccessary to start with the architecture of the app, separating all the front end files in a separate file called Public</p>

<h2>Technology used</h2>
<p>In the Front End HTML, Bootstrap, Javascript and React. In the Back End, Node, Express, MongoDB and Firebase for the Authentication and Authorization</p>

<h2>Features</h2>
<p>The project has some interesting features, it displays a form in order to create new users, this new user becomes a client of a digital bank in which he starts with a balance with 0 and he cand deposit and withdraw money acoordingly depending on it's necesities, the balance will be connected to a MongoDb database in which all the transactions are held and the new state of the balance will automatically modify the balance on the database. The user can display this balance in the UI. plus there is a table in which all the clients are displayed. Also once a new user is created he will have the oportunity to login next time and with the use of Firebase for Authentication and authorization he will be able to continue his transactions in the future or next time he logs in with his secret password</p>

<h2>License</h2>
<p>MIT</p>