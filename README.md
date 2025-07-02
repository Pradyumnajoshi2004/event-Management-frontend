' ==============================================================
' 🎉 Event Management Frontend
'
' This is the frontend of the Event Management System, developed using Angular,
' Material UI components, and styled primarily with Bootstrap 5.
' It allows users to view and interact with event information in a clean, responsive UI.
' ==============================================================

' 🚀 Features
' - View all upcoming events with date, time, and venue
' - Modal popup for detailed event information
' - Responsive layout using Bootstrap Grid
' - REST API integration with backend
' - Font Awesome icons for visual elements
' - Clean and modern design with Angular Material
' - User authentication (login/signup functionality)

' 🛠️ Tech Stack
' | Tech             | Purpose                          |
' |------------------|----------------------------------|
' | Angular          | Core frontend framework          |
' | Angular Material | UI components                    |
' | Bootstrap 5      | Styling and responsive layout    |
' | Font Awesome     | Icons                            |
' | HTML + CSS       | Page structure & styles          |
' | TypeScript       | Logic, components, and services  |

' 📦 Installation & Setup
' 1. Clone the repository
'    git clone https://github.com/your-username/event-management-frontend.git
'    cd event-management-frontend
'
' 2. Install dependencies
'    npm install
'
' 3. Run the Angular development server
'    ng serve
'
' 4. Open your browser and go to:
'    http://localhost:4200

' 📁 Folder Structure
' src/
' ├── app/
' │   ├── pages/
' │   │   ├── event-list/
' │   │   └── update-event/
' │   ├── services/
' │   │   ├── auth.service.ts
' │   │   └── event.service.ts
' │   ├── models/
' │   ├── app.module.ts
' │   ├── app.component.ts
' │   └── app-routing.module.ts
' ├── assets/
' ├── environments/
' │   └── environment.ts
' ├── index.html
' └── styles.css

' 🌐 Backend API
' This frontend consumes data from the backend hosted at:
' https://event-management-backend-w9uu.onrender.com/

' 🧪 Sample Event Object (From Backend)
' {
'   "_id": "64dfc8f1e3c2",
'   "eventName": "Art & Craft Expo",
'   "eventVenue": "JLN Stadium, New Delhi",
'   "eventDescription": "A weekend exhibition showcasing hand-made crafts, paintings, pottery, and DIY art workshops.",
'   "date": "2025-07-13T11:00:00.000Z"
' }

' 🤝 Contributing
' 1. Fork the repository
' 2. Create a new branch (git checkout -b feature-branch)
' 3. Commit your changes
' 4. Push to the branch
' 5. Open a Pull Request

' 📄 License
' MIT License

' 👨‍💻 Developed By
' Pradyumna Joshi
' Email: joshipradyumna517@gmail.com

