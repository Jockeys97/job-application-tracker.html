
A modern, responsive web application to track and manage your job applications. Built with vanilla HTML, CSS, and JavaScript - perfect for showcasing frontend development skills.

🚀 Features
Core Functionality

📝 Full CRUD Operations: Add, edit, and delete job applications
🔍 Search & Filter: Real-time search by company/position and filter by application status
📊 Statistics Dashboard: Visual overview of application statistics
📱 Responsive Design: Works seamlessly on desktop, tablet, and mobile devices

User Experience

🌙 Dark Mode: Toggle between light and dark themes
✨ Modern UI: Clean, professional interface with smooth animations
⚡ Fast Performance: Lightweight vanilla JavaScript implementation
🎯 Intuitive Navigation: User-friendly modal forms and table interactions

🛠️ Technologies Used

HTML5: Semantic markup and modern structure
CSS3: Custom properties, Grid, Flexbox, and responsive design
Vanilla JavaScript: ES6+ features, DOM manipulation, and event handling
No Dependencies: Pure frontend code with no external libraries

📋 Application Fields
Each job application includes:

Company Name (required)
Position Title (required)
Application Date (required)
Status (required): Applied, Interview, Offer, Rejected
Notes (optional): Additional details and comments

🎨 Design Features

Responsive Grid Layout: Adapts to different screen sizes
Status Badges: Color-coded status indicators
Interactive Tables: Hover effects and action buttons
Modal Forms: Clean popup forms for adding/editing applications
Theme Toggle: Switch between light and dark modes
Modern Typography: Clean, readable font stack

🚀 Getting Started
Prerequisites

Any modern web browser (Chrome, Firefox, Safari, Edge)
No server setup required - runs entirely in the browser

Installation

Clone the repository
bashgit clone https://github.com/yourusername/job-application-tracker.git
cd job-application-tracker

Open the application
bash# Simply open the HTML file in your browser
open index.html
# or
double-click index.html

Start tracking your applications!

💻 Usage
Adding Applications

Click the "Add Application" button
Fill in the required information
Click "Save Application"

Managing Applications

Edit: Click the "Edit" button on any application row
Delete: Click the "Delete" button and confirm removal
Search: Use the search bar to find specific companies or positions
Filter: Use the status dropdown to filter by application status

Viewing Statistics
The dashboard shows:

Total number of applications
Applications by status (Applied, Interview, Offer, Rejected)

📁 Project Structure
job-application-tracker/
├── index.html          # Main application file
├── README.md           # Project documentation
└── screenshots/        # Application screenshots (optional)
🔧 Customization
Adding New Status Options
To add new application statuses, modify the status options in the HTML:
html<option value="Phone Screen">Phone Screen</option>
<option value="Technical">Technical Interview</option>
And add corresponding CSS classes:
css.status-phone-screen {
    background: #e0e7ff;
    color: #3730a3;
}
Enabling localStorage
To persist data between sessions, you can extend the application to use localStorage:
javascript// Save to localStorage
function saveToStorage() {
    localStorage.setItem('jobApplications', JSON.stringify(applications));
}

// Load from localStorage
function loadFromStorage() {
    const stored = localStorage.getItem('jobApplications');
    return stored ? JSON.parse(stored) : [];
}
🌟 Future Enhancements
Potential features to add:

 Data export to CSV/PDF
 Application deadline reminders
 Interview scheduling integration
 Document attachment support
 Email templates for follow-ups
 Analytics and reporting
 Cloud storage integration

🤝 Contributing
Contributions are welcome! Here's how you can help:

Fork the project
Create a feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.
👨‍💻 Author
Your Name

GitHub: @yourusername
LinkedIn: Your LinkedIn
Portfolio: Your Portfolio

🙏 Acknowledgments

Design inspiration from modern web applications
Icons and emojis for enhanced user experience
CSS Grid and Flexbox for responsive layouts

📱 Browser Support

✅ Chrome (recommended)
✅ Firefox
✅ Safari
✅ Edge
✅ Mobile browsers

🐛 Known Issues

None currently reported

📊 Performance

Lightweight: ~15KB total file size
Fast loading: No external dependencies
Smooth animations: Hardware-accelerated CSS transitions


⭐ Star this repository if you found it helpful!
Made with ❤️ for job seekers everywhere
