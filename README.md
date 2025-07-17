# Flight-Booking-App-MERN
Demo - <a href="https://drive.google.com/file/d/1Q0XwKtAz7EkaKNJv3_gbo6mZE9nfuBTK/view?usp=drive_link">view video</a>

INTRODUCTION
   Project Title: Flight Finder: Navigating Your Air Travel Options
    Team Members: Team Size: 4
          Team Leader:  Shaik Shaheera Anjum
          Team member: Perugu Veera Venkata Swetha
          Team member: K Yaswani
          Team member: K Yakshitha

In today's fast-paced world, travel has become an essential part of our lives, whether it's for business, leisure, or personal reasons. With the advent of technology, booking flights has become more accessible and convenient than ever before, thanks to flight booking apps. A flight booking app is a mobile application that allows users to search, compare, and book flights easily from the comfort of their smartphones or tablets. The primary purpose of a flight booking app is to streamline the process of planning and booking air travel. These apps provide users with a range of features and functionalities that simplify the entire journey, from searching for flights to managing bookings and receiving travel updates. 
Description:
This Flight Booking APP is the ultimate digital platform designed to revolutionize the way you book flight tickets. With this app your flight travel experience will be elevated to new heights of convenience and efficiency. Our user-friendly web app empowers travelers to effortlessly discover, explore, and reserve flight tickets based on their unique preferences. Whether you're a frequent commuter or an occasional traveler, finding the perfect flight journey has never been easier.
This successful flight booking app combines a user-friendly interface, efficient search and booking capabilities, personalized features, robust security measures, reliable performance, and continuous improvement based on user feedback.


Scenario

●	John, a frequent traveler and business professional, needs to book a flight for an upcoming conference in Paris. He prefers using a flight booking app for its convenience and features.
●	John opens the flight booking app on his smartphone and enters his travel details for Departure as New York City, Destination as Paris, Date of Departure on April 10th and return on April 15th and Class as Business class, Number of passengers as 1
●	The app quickly retrieves available flight options based on John's preferences. He sees a range of choices from different airlines, including direct flights and those with layovers. The results show details such as price, airline, duration, and departure times.
●	Using the app's filters, John narrows down the options to show only direct flights with convenient departure times. He also selects his preferred airline based on past experiences and loyalty programs.
●	After choosing a flight, John proceeds to select his seat in the business class cabin. The app provides a seat map with available seats highlighted, allowing John to pick a window seat with extra legroom.
●	John securely enters his payment information using the app's integrated payment gateway. The app processes the payment and generates a booking confirmation with his e-ticket and itinerary details.
●	This scenario demonstrates how a flight booking app streamlines the entire travel process for users like John, offering convenience, customization, and real-time assistance throughout their journey.

TECHNICAL ARCHITECTURE
 
In this architecture diagram:
●	The frontend is represented by the "Frontend" section, including user interface components such as User Authentication, Flight Search, and Booking.
●	The backend is represented by the "Backend" section, consisting of API endpoints for Users, Flights, Admin and Bookings. It also includes Admin Authentication and an Admin Dashboard.
●	The Database section represents the database that stores collections for Users, Flights, and Flight Bookings.

Milestone 4: Frontend development.
1.	Login/Register
●	Create a Component which contains a form for taking the username and password.
●	If the given inputs matches the data of user or admin or flight operator then navigate it to their respective home page
2.	Flight Booking (User):
●	In the frontend, we implemented all the booking code in a modal. Initially, we need to implement flight searching feature with inputs of Departure city, Destination, etc.,
●	Flight Searching code: With the given inputs, we need to fetch the available flights. With each flight, we add a button to book the flight, which redirects to the flight-Booking page.
3.	Fetching user bookings:
●	In the bookings page, along with displaying the past bookings, we will also provide an option to cancel that booking.
4.	Add new flight(Admin):
●	Now, in the admin dashboard, we provide functionality to add new flights.
●	We create a html form with required inputs for the new flight and then send an httprequest to the server to add it to the database.
5.	Update Flight:
●	Here, in the admin dashboard, we will update the flight details in case if we want to make any edits to it
●	Along with this, implement additional features to view all flights, bookings, and users in the admin dashboard.

●	Landing page UI
<img width="975" height="454" alt="image" src="https://github.com/user-attachments/assets/0913fe18-3457-4da2-b748-d9b84d885f9a" />
●	Authentication
<img width="969" height="453" alt="image" src="https://github.com/user-attachments/assets/3a838eaa-bbf4-411e-9808-17d8f798afd8" />
●	User bookings
<img width="975" height="452" alt="image" src="https://github.com/user-attachments/assets/7e842cee-8129-475d-b1b1-70cb0d6d977f" />
●	Admin Dashboard
<img width="975" height="452" alt="image" src="https://github.com/user-attachments/assets/903c170d-216d-4803-adef-7e0de4ba4caa" />
●	All users 
<img width="975" height="448" alt="image" src="https://github.com/user-attachments/assets/d1f38d77-d71e-4c71-9884-af7226336c01" />
●	Flight Operator
<img width="975" height="454" alt="image" src="https://github.com/user-attachments/assets/47ae7e07-9d45-4920-b6d3-7573c7156ce2" />
●	All Bookings
<img width="975" height="456" alt="image" src="https://github.com/user-attachments/assets/f6cc8584-a5d0-4d55-b628-51b303d5233d" />

The demo of the app is available at:
https://drive.google.com/file/d/1Q0XwKtAz7EkaKNJv3_gbo6mZE9nfuBTK/view?usp=sharing 





