# TechNova Solutions and Learning Center (TSLC) - Student Information System

## About TSLC

TechNova Solutions and Learning Center (TSLC) is a private review center located in Quezon City, Philippines, providing academic review programs and preparatory training for students preparing for licensure examinations, entrance tests, and professional certifications. Established in 2018 by a group of educators and IT professionals, TSLC delivers structured review sessions, mock examinations, and guided learning programs across various disciplines including Information Technology, Education, and Business.

## The Challenge

As TSLC experienced steady growth in student enrollees and review programs offered each term, the organization continued to operate using manual and semi-digital processes. Without a centralized Student Information System, student-related data were recorded through paper-based forms and stored across multiple spreadsheet files. This fragmented approach created significant challenges:

- **Data Inconsistency**: Information scattered across multiple sources
- **Accessibility Issues**: Difficulty retrieving student information quickly
- **Operational Inefficiencies**: Delays in encoding and managing records
- **Enrollment Tracking**: Challenges in monitoring enrollment status
- **Progress Monitoring**: Inconsistencies in tracking student progress and attendance
- **Department Coordination**: Lack of unified system hindering admin, instructor, and staff collaboration

## The Solution

This comprehensive Student Information System centralizes all operations and provides dedicated portals for administrators, staff, and students, enabling seamless data management and improved organizational efficiency.

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
