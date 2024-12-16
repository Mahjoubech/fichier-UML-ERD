
# Blog Management System

## Overview
This document outlines the Blog Management System, its functionalities, and the database schema. The system includes features for managing blog articles, comments, categories, and user roles (visitor, user, admin). 

## System Features
- **Visitor:**
    - Read articles
    - Comment on articles
    - Filter articles by category
- **User:**
    - Create articles
    - Edit articles
    - Delete articles
    - Manage comments
- **Admin:**
    - Manage users
    - Moderate articles
    - Moderate comments
    - View dashboard and statistics
    - Manage categories

## Icons & Design
![System Design](https://img.icons8.com/color/48/000000/blogger.png)  

The Blog Management System features various roles and interactions between the system and users.

## UML Use Case Diagram
Below is the UML Use Case Diagram for the Blog Management System.

![UML Use Case Diagram](![alt text](image.png))

## Entity-Relationship Diagram (ERD)
Here is the ERD representing the structure of the database for the Blog Management System.

![ERD Diagram](![alt text](image-1.png))

## Key Features Explained

### 1. **Visitor Role:**
   - **Read Articles**: Visitors can read articles posted by users and admins.
   - **Comment on Articles**: Visitors can comment on articles using their name and email.
   - **Filter Articles by Category**: Visitors can filter articles by category.

### 2. **User Role:**
   - **Create Articles**: Registered users can create new articles with titles, content, and optional images.
   - **Edit Articles**: Users can edit articles they've created.
   - **Delete Articles**: Users can delete their own articles.
   - **Manage Comments**: Users can moderate their comments on articles.

### 3. **Admin Role:**
   - **Manage Users**: Admins can manage users and assign roles.
   - **Moderate Articles**: Admins can moderate the articles published by users.
   - **Moderate Comments**: Admins can approve or delete comments.
   - **View Dashboard and Statistics**: Admins have access to various system statistics, including the number of articles, users, and comments.
   - **Manage Categories**: Admins can create, edit, and delete categories for structuring articles.

## Conclusion
The Blog Management System provides an intuitive platform for users to share articles and interact with others through comments. Admins have full control over managing users, articles, and comments, while visitors can browse and engage with the content.

---


