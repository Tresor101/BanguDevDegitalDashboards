
# Parent Dashboard

This folder contains the parent dashboard for College Congo. The dashboard is designed for parents or guardians to easily monitor their children's academic progress, fees, notifications, and behavior notices in a modern, responsive, and accessible interface.

## Features

- **Card-Only Navigation:** All dashboard features are accessible via interactive cards. Each card has a "View Details" button that opens a modal with more information.
- **Children Profiles:** View details of each child, including academic and personal information, via a modal.
- **School Fees:** Displays total, paid, and balance for each child, with a details modal.
- **Exam Timetable:** Card and modal for upcoming exams.
- **Notifications:** Card and modal for recent announcements and messages from the school.
- **Behavior Notices:** Card and modal for teacher-submitted behavior notices, each with a timestamp and teacher's name.
- **Logout:** Card to sign out of the dashboard.

## Code Structure

- `parent.html`: Main dashboard page. Uses Bootstrap 5 for layout and modals, Font Awesome for icons. All navigation is via cards; there is no sidebar.
- `../style.css`: Centralized CSS for all dashboards. Includes custom styles for cards, icons, backgrounds, and responsive design.
- Modals: Each card's "View Details" button opens a Bootstrap modal with more information or actions.

## Design Principles

- **Modern UI:** Uses a soft card background, subtle borders, and a gradient animated background for a fresh look.
- **Responsive:** The layout adapts to all screen sizes using Bootstrap's grid system and custom media queries.
- **Accessibility:** ARIA labels, alt text for images, and high-contrast color choices are used for better accessibility.
- **Separation of Concerns:** All custom styles are in `style.css` to keep HTML clean and maintainable.

## How It Works

1. Open `parent.html` in your browser.
2. The dashboard displays cards for each feature (Children, Fees, Exam, Notifications, Behavior Notices, Logout).
3. Click "View Details" on any card to open a modal with more information.
4. Behavior notices include the teacher's name and a timestamp for each entry.
5. All content is static by default but can be connected to dynamic data sources as needed.

## Customization

- To change card colors or styles, edit the `.dashboard-card` class in `../style.css`.
- To add or modify features, update the cards and modals in `parent.html`.

## Accessibility & Best Practices

- All images have descriptive `alt` text.
- Buttons and links are keyboard accessible.
- Color contrast meets accessibility standards.

## Usage

Open `parent.html` in a browser to access the parent dashboard interface.
