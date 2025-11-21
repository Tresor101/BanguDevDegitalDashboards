
# Student Dashboard

This folder contains the student dashboard for College Congo. The dashboard is designed for students to easily access their academic information, attendance, fees, notifications, and more, all in a modern, responsive, and accessible interface.

## Features

- **Card-Only Navigation:** All dashboard features are accessible via interactive cards. Each card has a "View Details" button that opens a modal with more information.
- **Performance Trend:** Visualizes academic progress using a Chart.js line chart.
- **Attendance Tracking:** Shows attendance rate with a progress bar and details modal.
- **School Fees:** Displays total, paid, and balance with a details modal.
- **Average Percentage:** Shows academic average with a progress bar and modal.
- **Courses & Timetable:** Cards link to modals listing subjects, teachers, and class schedules.
- **Notifications:** Card and modal for recent announcements.
- **Profile:** Card and modal for student profile details.
- **Exam Timetable:** Card and modal for upcoming exams.
- **Logout:** Card to sign out of the dashboard.

## Code Structure

- `student.html`: Main dashboard page. Uses Bootstrap 5 for layout and modals, Font Awesome for icons, and Chart.js for the performance chart. All navigation is via cards; there is no sidebar.
- `../style.css`: Centralized CSS for all dashboards. Includes custom styles for cards, icons, backgrounds, and responsive design.
- Modals: Each card's "View Details" button opens a Bootstrap modal with more information or actions.
- Chart.js: Used for the performance trend chart, with a y-axis in steps of 10 for clarity.

## Design Principles

- **Modern UI:** Uses a soft card background, subtle borders, and a gradient animated background for a fresh look.
- **Responsive:** The layout adapts to all screen sizes using Bootstrap's grid system and custom media queries.
- **Accessibility:** ARIA labels, alt text for images, and high-contrast color choices are used for better accessibility.
- **Separation of Concerns:** All custom styles are in `style.css` to keep HTML clean and maintainable.

## How It Works

1. Open `student.html` in your browser.
2. The dashboard displays cards for each feature (Attendance, Fees, Average, Performance, Courses, Timetable, Notifications, Profile, Exam, Logout).
3. Click "View Details" on any card to open a modal with more information.
4. The performance trend chart is rendered using Chart.js and updates responsively.
5. All content is static by default but can be connected to dynamic data sources as needed.

## Customization

- To change card colors or styles, edit the `.dashboard-card` class in `../style.css`.
- To add or modify features, update the cards and modals in `student.html`.

## Accessibility & Best Practices

- All images have descriptive `alt` text.
- Buttons and links are keyboard accessible.
- Color contrast meets accessibility standards.

## Usage

Open `student.html` in a browser to access the student dashboard interface.
