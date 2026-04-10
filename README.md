# TechNova - Education Management System

A comprehensive web-based education management system with dedicated portals for administrators, staff, and students.

## Getting Started

### To run the website:

1. Open the `Public/index.html` file in your web browser
2. You will be presented with the landing page
3. Navigate to the appropriate portal using the provided navigation links

## Project Structure

```
APPDEV/
├── Public/
│   ├── index.html          (Landing page - START HERE)
│   ├── Logo-main.png
│   └── landing-hero.png
├── Admin_portal/
│   ├── index.html          (Dashboard)
│   ├── schedule.html       (Review Schedule)
│   ├── monitoring.html     (Student Monitoring)
│   ├── records.html        (Records Management)
│   ├── settings.html       (Settings)
│   └── auth.html           (Authentication)
├── Staff_portal/
│   ├── index.html          (Dashboard)
│   ├── schedule.html       (Staff Schedule)
│   ├── monitoring.html     (Student Monitoring)
│   ├── records.html        (Records)
│   └── auth.html           (Authentication)
└── Student_portal/
    ├── index.html          (Profile)
    ├── schedule.html       (Schedule)
    ├── grades.html         (Grades)
    └── attendance.html     (Attendance)
```

## Features

### Portals

- **Admin Portal**: Dashboard, Review Schedule, Student Monitoring, Records Management, Settings
- **Staff Portal**: Dashboard, Staff Schedule, Student Monitoring, Records Management
- **Student Portal**: Profile, Schedule, Grades, Attendance
- **Public Landing Page**: Project overview and access point

### Technology Stack

- HTML5
- Tailwind CSS
- Bootstrap Icons
- Responsive Design

## Navigation

Each portal includes:
- Desktop sidebar navigation with Bootstrap icons
- Mobile-responsive menu
- Consistent styling and branding
- Smooth transitions and hover effects

## Quick Start

```bash
# Simply open in your browser:
File > Open > Public/index.html
```

Or double-click `Public/index.html` and it will open in your default browser.

## Notes

- All files are static HTML files
- No backend server required
- Fully responsive design works on desktop, tablet, and mobile
- Uses CDN-hosted Tailwind CSS and Bootstrap Icons
