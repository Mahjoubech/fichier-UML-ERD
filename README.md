
# Blog Management System

## UML Use Case Diagram

This diagram illustrates the use cases for the Blog Management System. Below are the actors and their corresponding actions:

### Actors:
- **Visitor**: A visitor can read articles, comment on articles, and filter articles by category.
- **User**: A registered user can perform all the actions of a visitor, but also has the ability to create, edit, delete articles, and manage comments.
- **Admin**: An admin has all the rights of a user, plus the ability to manage users, moderate articles, moderate comments, view statistics, and manage categories.

### Use Cases:
1. **Visitor**:
    - Read Articles
    - Comment on Articles
    - Filter Articles by Category
    - Sign up and Sign in

2. **User**:
    - Create Articles
    - Edit Articles
    - Delete Articles
    - Manage Comments

3. **Admin**:
    - Manage Users
    - Moderate Articles
    - Moderate Comments
    - View Dashboard and Statistics
    - Manage Categories

## ERD (Entity Relationship Diagram)

The ERD provides the relationships between different entities in the system:

1. **User**: The user has attributes like user_id, name, email, password. A user can create, edit, and delete articles.
2. **Article**: An article has attributes like article_id, title, content, created_at, updated_at, and category_id.
3. **Comment**: A comment has attributes like comment_id, user_id, article_id, and content. It relates to articles and users.
4. **Category**: A category has attributes like category_id and name. It relates to articles.
5. **Admin**: An admin is a user with extended rights to manage users and moderate content.
6. **Action**: Actions include "create", "edit", and "delete" related to articles and comments.

### Relationships:
- **User** has a one-to-many relationship with **Article** (A user can create many articles).
- **Article** has a one-to-many relationship with **Comment** (An article can have many comments).
- **User** has a one-to-many relationship with **Comment** (A user can post many comments).
- **Article** belongs to a **Category** (Each article belongs to one category).
- **Admin** manages all entities and moderates content.
