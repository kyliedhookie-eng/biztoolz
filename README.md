BizToolz

Two simple tools for small businesses, built with plain HTML, CSS and JavaScript.

Live demo: https://biztoolzbykylie.netlify.app

BizToolz home page

Features
Booking system
Choose a service, date and time slot
Time slots that are already taken are blocked, so double bookings are not possible
Validates the name, phone number and date before saving
Bookings are sorted by date and time, and can be cancelled
Bookings are still there after refreshing the page
Invoice generator
Add and remove items with quantity and price
Calculates the subtotal, 15% VAT and total automatically
Invoice numbers count up for each new invoice
Print or save as PDF with a clean print layout
The current invoice is kept after refreshing the page
Design
Black, green and teal theme
Fully responsive: tables turn into stacked cards on phones
Keyboard-friendly with visible focus states
Built with
HTML5
CSS3 (custom properties, grid, flexbox, print styles)
JavaScript (no frameworks or libraries)
localStorage for saving data in the browser
Run it locally
Download or clone this repository.
Open the folder in VS Code.
Install the Live Server extension.
Right-click index.html and choose Open with Live Server.

You can also just double-click index.html to open it in your browser.

Project structure
biztoolz/
├── index.html      Home page
├── booking.html    Booking system
├── invoice.html    Invoice generator
├── style.css       Shared styles
└── README.md
Notes

Data is saved in the visitor's own browser using localStorage, so it is not shared between devices or people. This keeps the demo simple. For real clients, the next step would be a backend and database.

Ideas for future versions
Backend and database so bookings are shared
Admin login to manage bookings
Email or WhatsApp confirmations
Business logo upload and PDF download on invoices
Author

Kylie Dhookie, software engineering student LinkedIn# biztoolz
