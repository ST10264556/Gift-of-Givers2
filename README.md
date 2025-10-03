# Gift-of-Givers2
I was unable to upload the whole project due to not enough space, will be submitting the "Bin" on ARC as is it too large to be uploaded

GiftOfGivers - Disaster Relief Management Platform
Project Overview
GiftOfGivers is a comprehensive web application built with ASP.NET Core MVC that serves as a disaster relief coordination platform. The system enables communities to manage donations, coordinate volunteers, report incidents, and organize relief efforts during emergencies and natural disasters.
Core Features
🔐 Authentication & User Management
User Registration & Login: Secure cookie-based authentication with password hashing
User Profiles: Users can view and edit their personal information
Role-based Access: Support for different user roles (Admin, User, Volunteer)
💰 Donation Management
Donation Tracking: Log and track various types of donations (food, clothing, cash, etc.)
Donor Attribution: Link donations to registered users
Donation History: View all donations with timestamps and donor information
Quantity Tracking: Record amounts and quantities for different resource types
🎵 Event Management (Gigs)
DJ & Venue Coordination: Manage DJs and venues for fundraising events
Event Scheduling: Create and schedule gigs with specific dates and times
Venue Management: Full CRUD operations for venue information
🚨 Disaster Incident Reporting
Incident Submission: Users can report disasters and emergencies
Location Tracking: Record incident locations for emergency response
Incident History: View all reported incidents with timestamps
Reporter Attribution: Track who reported each incident
👥 Volunteer Management
Volunteer Registration: Register volunteers with contact information
Task Assignment: Basic volunteer task management system
Volunteer Tracking: Monitor volunteer participation and assignments
🏢 Venue Management
Venue Database: Maintain a database of available venues
Location Information: Store venue addresses and contact details
Event Association: Link venues to specific events and gigs
Technical Architecture
Backend Framework
ASP.NET Core 8.0 MVC: Modern web framework with dependency injection
Entity Framework Core: ORM for database operations
SQLite Database: Local database for development and testing
Cookie Authentication: Secure user session management
Database Schema
Users: ApplicationUser with authentication and profile data
Donations: Resource tracking with donor relationships
Gigs: Event management with DJ and venue relationships
IncidentReports: Disaster reporting with reporter attribution
Volunteers: Volunteer management with task assignments
Venues: Venue information for event coordination
Frontend & UI
Bootstrap 5: Responsive, modern UI framework
Razor Views: Server-side rendering with model binding
Professional Styling: Gradient navigation, card-based layouts
Form Validation: Client and server-side validation
Security Features
Password Hashing: Secure password storage using ASP.NET Identity
Anti-forgery Tokens: CSRF protection on forms
Authorization: Role-based access control
Input Validation: Comprehensive model validation
User Experience
Public Features
Browse donations, gigs, and incident reports
View venue information
Access about and contact pages
Authenticated Features
Create and manage donations
Report incidents and emergencies
Edit personal profile
Access volunteer management
Navigation
Home: Welcome page with quick access to main features
Donations: View and create donation records
Gigs: Manage events and DJ bookings
Venues: Venue management system
Incidents: Disaster reporting system
Volunteers: Volunteer coordination
About/Contact: Information pages
Development Features
Database Management
Automatic Schema Creation: Database tables created on startup
Data Seeding: Sample data for testing and demonstration
Migration Support: Easy database schema updates
Error Handling
Graceful Degradation: Safe error handling for database operations
User-friendly Messages: Clear error messages for users
Development Support: Detailed error information during development
Use Cases
Emergency Response
Community members can quickly report disasters
Emergency coordinators can track incidents and response efforts
Resource allocation based on real-time incident data
Fundraising & Events
Organize fundraising events with DJ and venue coordination
Track donations and donor contributions
Manage volunteer participation in relief efforts
Community Coordination
Centralized platform for disaster relief coordination
Volunteer management and task assignment
Resource tracking and distribution management
Technical Benefits
Scalable Architecture: Built with modern .NET patterns
Database Flexibility: Easy to switch between SQLite and SQL Server
Security First: Comprehensive authentication and authorization
User-friendly: Intuitive interface with professional styling
Maintainable: Clean separation of concerns with MVC pattern
This platform serves as a comprehensive solution for disaster relief coordination, combining donation management, volunteer coordination, incident reporting, and event management into a single, cohesive system.
