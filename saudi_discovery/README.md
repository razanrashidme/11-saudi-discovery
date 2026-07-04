# Discover Saudi 

## Project Overview
A dynamic web application designed to showcase Saudi Arabian tourist destinations. The system provides an interactive guide for exploring regions, landmarks, and traditions, featuring a secure Admin Dashboard for real-time content management.

## Key Features
* **Interactive Gallery:** Browse regions with real-time search and category filtering (City, Nature, Heritage, Religious).
* **Admin Dashboard:** A password-protected portal to Create, Read, Update, and Delete (CRUD) destination records.
* **Content Management:** Manage detailed descriptions, image galleries, and landmarks for each region.
* **Theme Switching:** JavaScript-powered Dark/Light mode toggle for an improved user experience.

## Technical Stack
* **Backend:** PHP, MySQL
* **Frontend:** HTML5, CSS3, JavaScript
* **Auth:** Session-based Admin Authentication

## Database Schema
The system uses a relational database (`saudi_discovery`) consisting of two main tables:
* **`admins`**: Stores admin credentials for secure dashboard access.
* **`places`**: Stores destination details including names, categories, descriptions, and file paths for image galleries.

## System Functionality
* **Dynamic Rendering:** Content is fetched directly from the database based on unique record IDs.
* **Admin Security:** Protects management pages via PHP sessions and uses input sanitization to ensure data integrity and security.

## Contributors
* Sara Alrowaily
* Haneen Alaqeel
* Razan Alenazi