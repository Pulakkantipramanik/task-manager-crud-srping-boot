# README.md তৈরি করুন
cat > README.md << 'EOF'
# Task Manager CRUD API - Spring Boot

A complete REST API for task management with MySQL database.

## Features
- Full CRUD operations
- MySQL integration
- RESTful endpoints

## API Endpoints
- GET `/api/tasks` - Get all tasks
- POST `/api/tasks` - Create task
- GET `/api/tasks/{id}` - Get task by ID
- PUT `/api/tasks/{id}` - Update task
- DELETE `/api/tasks/{id}` - Delete task

## Technologies
- Java 17
- Spring Boot 3.2.0
- MySQL
- Maven
EOF

# README add করুন
git add README.md
git commit -m "docs: add README.md with project documentation"
git push origin master
