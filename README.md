
# PG_Life-Project
PG Life is a dynamic web application providing a user-friendly platform for managing shared accommodations, fostering seamless communication and streamlined organization.

# ABOUT
PG Life is a Full-Stack Web Application. This is a project that I was assigned to make during my
Internshala Full Stack Web Development Internship Training.
Tech Stack:- HTML, CSS, Bootstrap 5, Javascript, AJAX, PHP, MySQL.

This web app has the following functionalities:-

1. The home page:-
--------------------
	a. Search bar, where user can enter city name(in any case), and PGs listed in that city(if exists in database), will be shown as list.
	b. Contains main cities in the form of circular sections, clicking upon which user can get the list of pgs existing in that city.
![Screenshot (61)](https://github.com/Khushiarora18/PG_Life-Project/assets/91714234/7b48bcfa-3536-4e37-bc80-eb5660e01978)
![Screenshot (62)](https://github.com/Khushiarora18/PG_Life-Project/assets/91714234/7fffbf69-f69d-4452-8971-0e2bd6eb4c6b)



2. The PG list page:-
----------------------
	a. Shows the list of all the PGs and their main features in the selected city, in the form of beautiful cards.
	b. Filter bar, using which the PGs can be sorted according to rent and rating, in ascending or descending order.
	c. User can see here which PG is being marked interested by how many users, to know popularity.
	d. After logging in, user can mark any PG(s) as interested, from the list itself, by clicking on the heart icon.
	e. The heart icon toggles style in terms of fill color, when alternatively clicked to like or dislike the pg. Based upon click, interested user's number remains updated dynamically.
![Screenshot (63)](https://github.com/Khushiarora18/PG_Life-Project/assets/91714234/186b30a1-b529-4cdb-ba8c-525264196026)


3. The PG details page:-
-------------------------
	a. In the property list page, if any user clicks on "View" button, that pg's entire details is being displayed in the PG details page.
	b. Images of the selected PG is being viewed at top front as a beautiful carousel.
	c. The page shows all the details such as amenities, testimonials, address of the PG neatly.
	d. User can see the selected PG is being marked interested by how many users, to know popularity.
	e. After logging in, user can mark any PG(s) as interested, from the list itself, by clicking on the heart icon.
	f. The heart icon toggles style in terms of fill color, when alternatively clicked to like or dislike the pg. Based upon click, interested user's number remains updated dynamically.
![Screenshot (64)](https://github.com/Khushiarora18/PG_Life-Project/assets/91714234/915279a4-74f1-45ee-92f9-b3d7ca7b9637)
![Screenshot (65)](https://github.com/Khushiarora18/PG_Life-Project/assets/91714234/a09d1965-2db7-499c-9f19-c3a7e87edf89)
![Screenshot (66)](https://github.com/Khushiarora18/PG_Life-Project/assets/91714234/76d75550-be07-460c-a8f2-441705fda131)




4. The dashboard:-
--------------------
	a. Appears only for the logged in users.
	b. Shows the account details of the logged in users.
	c. Below profile details, there is a section for Interested properties, which shows the cards of those PGs which the logged in user marked interested, accross any city.
	d. From this list, user can click the heart icon on any PG card, to remove that PG from interested list, and that specific page section gets dynamically changed according to user's action.
![Screenshot (51)](https://github.com/Khushiarora18/PG_Life-Project/assets/91714234/c2a585ec-df06-44c4-b04d-958493f466af)


5. The Navbar:-
----------------
	a. Contains brand name.
	b. If NOT logged in, it shows option to Signup and Login.
	c. If logged in, it shows option to got to Dashboard and Logout. Also, it displays the user's first name who is being logged in currently, by using SESSION.
	d. Totally responsive toggler navbar.
![navbar before](https://github.com/Khushiarora18/PG_Life-Project/assets/91714234/4f0b7df5-7114-42a6-955c-2730b759db5f)
![Screenshot (49)](https://github.com/Khushiarora18/PG_Life-Project/assets/91714234/44e6e92e-0312-4ef8-bf2b-b1e8e9e12ad2)
![Screenshot (50)](https://github.com/Khushiarora18/PG_Life-Project/assets/91714234/fbff323e-8f17-40d3-9985-f8e536467b6d)

6. The Breadcrumb:-
--------------------
	a. Beautify shows the relative location of the user in the web app.
	b. Contains hyperlinks to easily navigate back and forth an endpoint.


7. The Footer:-
-----------------
	a. Shows the list(containg hyperlinks) to show the list of PGs in the most popular cities.
	b. Displays copywright information.
![footer](https://github.com/Khushiarora18/PG_Life-Project/assets/91714234/5ff59cca-5cb8-4d41-a386-a24e5c4bd8dc)


8. Entire web app can be surfed without logging in for user's ease and attraction for new users. Only 	certain features such as dashboard, and marking interested are available upon log in.
  

9 Through the entire web app, each and every excetion is handled well using custom codes and UI,	such that they are easily managed, and user can get to know the fault.
