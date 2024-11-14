# Online Quiz Application

## Project Overview
The **Online Quiz Application** is a web-based platform developed in **Java** with a **ReactJS** frontend and **Spring Boot** backend. It allows users to take quizzes on various topics with a user-friendly interface, multiple-choice questions, scoring feedback, and quiz history tracking. The application supports both user and admin roles, where admins can create and manage quizzes, while users can attempt quizzes and review their past attempts.

## Tech Stack
- **Frontend**: ReactJS, Vite (for faster builds)
- **Backend**: Java, Spring Boot
- **Database**: MySQL
- **Languages Used**: Java, JavaScript, HTML, CSS

## Features

1. **Quiz Management**:
   - Admins can create, edit, and delete quizzes with multiple-choice questions.
   - Each question includes a title, options, and correct answer(s).

2. **Quiz Taking**:
   - Users can choose from available quiz topics and take a quiz.
   - Each question is displayed with selectable options, and users receive immediate feedback on each answer.
   - The final score is calculated and displayed at the end of the quiz.

3. **Scoring and Progress Tracking**:
   - Tracks and displays users' scores after each quiz attempt.
   - Users can view their quiz history, including past scores and attempts.

4. **User Interface**:
   - Clean, user-friendly interface for easy navigation.
   - Responsive design for both desktop and mobile views.

5. **Data Persistence**:
   - Stores quiz data, user accounts, and scores in a MySQL database.
   - CRUD operations are implemented for managing database interactions.

6. **Documentation**:
   - Comprehensive code documentation and setup instructions provided for ease of use.

## Screenshots

*Include screenshots for different parts of the application here. Replace the `![Screenshot]()` placeholders with links to your actual screenshot files.*

- **Home Page**  
  ![Home Page](link_to_screenshot_home)

- **Quiz Page**  
  ![Quiz Page](link_to_screenshot_quiz)

- **Admin Panel**  
  ![Admin Panel](link_to_screenshot_admin_panel)

## Installation

### Prerequisites
- **Java Development Kit (JDK)** version 11 or above
- **Node.js** and **npm** installed
- **MySQL** for database setup
- **Vite** (if not already installed, it will be installed with the frontend dependencies)

### Full Setup Instructions

#### Step 1: Clone the repository
```bash
git clone https://github.com/your-username/online-quiz-application.git

#### Step 2: Backend Setup (Spring Boot)
Navigate to the backend folder:
```bash
cd online-quiz-application/backend

