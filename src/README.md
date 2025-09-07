# Mergington High School Activities

A comprehensive school activity management system that enables teachers to manage student enrollment in extracurricular activities. Built with FastAPI, MongoDB, and modern web technologies to provide a robust platform for activity coordination.

## Features

### Student Activity Management
- **Browse Activities**: View detailed information for 13+ extracurricular activities including Chess Club, Programming Class, Sports Teams, Art Club, Drama Club, and more
- **Advanced Search & Filtering**: Find activities using:
  - Text search by activity name or description
  - Category filters (Sports, Arts, Academic, Community, Technology)
  - Day-of-week filtering (Monday through Sunday)
  - Time-based filtering (Before School, After School, Weekend)
- **Activity Details**: Each activity includes schedule, participant limits, and current enrollment

### Teacher Authentication & Management
- **Secure Login System**: Teachers authenticate with username/password credentials
- **Role-Based Access**: Support for different teacher roles (teacher, admin)
- **Student Registration**: Teachers can register and unregister students for activities
- **Enrollment Tracking**: Monitor participant capacity and current enrollment levels

### Technical Features
- **RESTful API**: Built with FastAPI for modern, fast API development
- **Database Persistence**: MongoDB integration for reliable data storage
- **Responsive Design**: Modern UI with sidebar navigation and modal dialogs
- **Real-time Updates**: Dynamic content loading with JavaScript
- **Security**: Argon2 password hashing and authentication validation

## Available Activities

The system comes pre-configured with diverse extracurricular offerings:
- **Sports**: Soccer Team, Basketball Team, Morning Fitness
- **Academic**: Math Club, Programming Class, Science Olympiad, Debate Team
- **Arts**: Art Club, Drama Club
- **Technology**: Weekend Robotics Workshop
- **Community**: Chess Club, Sunday Chess Tournament, Manga Maniacs

## Development Guide

For detailed setup and development instructions, please refer to our [Development Guide](../docs/how-to-develop.md).
