# Movie Ticket Booking System (PHP)

This is a **Movie Ticket Booking System** built using **PHP**. The system allows users to book tickets, administrators to manage movies and showtimes, and theater assistants to assist with the booking process. 

## Features

### 1. **Admin Panel**
The Admin has full control over the system and can manage movies, showtimes, and user activities. The key functionalities available to the Admin are:

- **Manage Movies:**
  - Add new movies to the system.
  - Edit movie details (e.g., title, genre, release date, etc.).
  - Delete movies from the system.

- **Manage Showtimes:**
  - Add new showtimes for movies.
  - Edit showtimes (timing, movie association).
  - Delete showtimes from the system.

- **View Bookings:**
  - View all booking information, including user details and tickets purchased.
  - Cancel bookings (if necessary).

- **User Management:**
  - View registered users.
  - Delete or modify user accounts.

### 2. **Theater Assistant Panel**
The Theater Assistant helps users during the ticket booking process and handles seat allocation. The key functionalities for the Theater Assistant are:

- **Assist with Booking:**
  - Help users select movie showtimes and seats.
  - Allocate seats to users when booking tickets.

- **View Current Bookings:**
  - View ongoing bookings and available seats.
  - Modify bookings (e.g., add/remove tickets or change showtimes).

- **Seat Management:**
  - Manage seat availability for different movies.
  - Mark seats as booked or available.

### 3. **User Panel**
Users can easily browse movies, book tickets, and view their bookings. The main functionalities for Users are:

- **Browse Movies:**
  - View a list of movies currently playing in theaters.
  - View movie details such as title, genre, description, and showtimes.

- **Book Tickets:**
  - Select a movie and showtime.
  - Choose available seats.
  - Complete the booking by providing necessary details (e.g., name, contact).
  - View a confirmation of booking with the option to print or save the ticket.

- **View Bookings:**
  - View a list of all their past and upcoming bookings.
  - Cancel bookings if necessary (if allowed).

### Technologies Used:
- **PHP**: Server-side scripting language for dynamic content.
- **MySQL**: Database for storing movie and user data.
- **HTML/CSS**: Frontend design for user interface.
- **JavaScript**: For enhancing frontend interactivity (optional, if used).
- **Bootstrap**: Responsive UI design.

## Installation Instructions

### Prerequisites:
- **PHP** version 7.x or higher
- **MySQL** database server
- **Apache** or any other web server with PHP support

### Steps to Install:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sankarasubramanian7/movieticketphp.git
