# travelling-form
# ✈️ Travel Application — 3D Boarding Pass

A modern, responsive **Travel Application** built with **HTML, CSS, and JavaScript**.
The application uses a 3D boarding-pass inspired interface to collect traveler information, trip details, travel preferences, and confirm a travel application.

## 🌍 Live Features

* ✈️ 3D boarding-pass style interface
* 🎨 Modern dark travel-themed UI
* 🖱️ Interactive 3D mouse-parallax effect
* 📱 Responsive design for mobile and desktop
* 🧑 Traveler information form
* 🌎 Destination selection
* 📅 Departure and return date selection
* 🧳 Travel purpose selection
* 👥 Number of travelers
* 💺 Travel class selection
* 🏨 Accommodation selection
* 📝 Special requests
* ✅ Form validation
* 📋 Application review page
* 🎫 Automatic travel reference number
* 🎉 Application confirmation screen
* 🔄 Start a new application
* ♿ Reduced-motion support

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript**
* CSS Grid
* CSS Flexbox
* CSS 3D Transforms
* CSS Animations
* HTML5 Form Validation
* Google Fonts

The project imports **Fraunces, Inter, and Space Mono** fonts from Google Fonts.

## 📂 Project Structure

```text
travel-application/
│
├── travel-application-3d.html
└── README.md
```

The project is currently implemented as a **single HTML file** containing the HTML structure, CSS styling, and JavaScript functionality.

## 🚀 Getting Started

### 1. Download or Clone the Project

```bash
git clone https://github.com/your-username/travel-application.git
```

Then open the project folder:

```bash
cd travel-application
```

### 2. Open the Application

You don't need a backend server or database to run the current version.

Simply open:

```text
travel-application-3d.html
```

in a modern web browser.

You can also use **VS Code + Live Server** for development.

## 🧑‍💼 Step 1 — Traveler Details

The first step collects:

* Full name
* Email
* Phone number
* Nationality
* Passport number

These fields are required before continuing to the next step.

## 🌎 Step 2 — Trip Details

The second step collects:

* Destination
* Purpose of travel
* Number of travelers
* Departure date
* Return date

Available travel purposes include:

* Tourism
* Business
* Study
* Family visit
* Other

## 🧳 Step 3 — Travel Preferences

Users can select:

* Travel class
* Accommodation
* Special requests

Travel classes include:

```text
Economy
Premium economy
Business
First
```

Accommodation options include:

```text
Hotel
Resort
Hostel
Rental / Airbnb
Not needed
```

## 📋 Step 4 — Review & Submit

Before submitting, the application displays a summary containing information such as:

* Traveler
* Email
* Nationality
* Passport number
* Destination
* Purpose
* Departure date
* Return date
* Number of travelers
* Travel class
* Accommodation

The user must confirm that the information is accurate before submitting.

## 🎫 Application Confirmation

After submission, the application generates a reference number in this format:

```text
TRV-XXXXX-2026
```

The confirmation overlay displays:

> Application submitted

and provides an option to start a new application.

## ✨ 3D Interaction

The boarding-pass card responds to mouse movement using CSS 3D transforms.

The card rotates according to the mouse position, creating a parallax effect:

```javascript
card.style.setProperty('--ry', (x*7) + 'deg');
card.style.setProperty('--rx', (y*-7) + 'deg');
```

The effect is disabled for touch devices and users who prefer reduced motion.

## 📅 Date Validation

The application automatically prevents selecting a departure date before the current date.

The return date is also restricted so that it cannot be earlier than the departure date.

## 📱 Responsive Design

The interface adapts to smaller screens.

On mobile devices:

* Form fields become single-column.
* Ticket information changes to a two-column layout.
* Padding is reduced.
* Step indicators become smaller.

## 🎨 Design

The application uses a travel/boarding-pass visual style with:

* Navy background
* Gold accents
* Teal highlights
* Cream typography
* Animated stars
* Flying airplane
* Dashed ticket perforation
* 3D card effect
* Animated confirmation stamp

The main interface is built around a 3D card with CSS perspective and `rotateX` / `rotateY` transforms.

## 🔄 Application Flow

```text
Start
  │
  ▼
Traveler Details
  │
  ▼
Trip Details
  │
  ▼
Travel Preferences
  │
  ▼
Review Application
  │
  ▼
Confirm Details
  │
  ▼
Application Submitted
  │
  ▼
Reference Number Generated
```

## 🧠 JavaScript Functionality

The JavaScript controls:

* Step navigation
* Required-field validation
* Progress indicators
* Review summary
* Date formatting
* Reference-number generation
* Application submission
* Form reset
* Live boarding-pass updates
* 3D mouse interaction

The application uses four steps and updates the progress indicators as the user moves through the form.

## 🔮 Future Improvements

Possible improvements for a production version:

* 🔐 User authentication
* 🗄️ Database integration
* 🌐 Backend API
* ✈️ Real flight search
* 🏨 Real hotel search
* 💳 Online payment
* 📧 Email confirmation
* 📱 SMS notifications
* 🗺️ Interactive maps
* 🌦️ Weather information
* 📄 PDF boarding-pass generation
* 👤 User dashboard
* 🔑 Secure account management
* ☁️ Cloud deployment
* 🤖 AI travel recommendations

## ⚠️ Current Limitations

This version is a **frontend-only application**.

The current code does not provide:

* A backend server
* Persistent database storage
* Real flight booking
* Real hotel booking
* Actual email delivery
* Payment processing

The submission currently displays a confirmation overlay and generates a client-side reference number rather than sending the application to a backend service.

## 💻 Browser Support

Recommended browsers:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

Use a modern browser with JavaScript enabled.

## 👨‍💻 Author

**Kamil Zeya**

Computer Science Student

### Skills

* HTML
* CSS
* JavaScript
* Python
* Java
* C
* Git & GitHub
* Generative AI

## 📄 License

This project is intended for **educational and personal use**.

You are free to modify and improve the project for learning and portfolio purposes.

---

⭐ If you like this project, consider giving the GitHub repository a **star**!

### Made with ❤️ and ✈️

