# question_system

## Dynamic Survey Creation & Response System
This system allows administrators to create different types of questions (multiple choice, short answer, ranking, etc.) to compose surveys that users can respond to.

## Core Features:

### Question Administration Panel:
- Create new questions.
- Edit existing questions.
- Delete questions.
- Support for different question types (multiple choice, short answer, ranking, etc.).

### Survey Generation:
- Combine individual questions to form a survey.
- Set survey status (active, inactive).

### User Panel:
- Respond to active surveys.
- View previously answered surveys.

### Reporting & Analysis:
- Generate reports based on survey answers.
- Analyze data for trends or patterns.

## Technical Architecture:

### Backend:
- **Kotlin** as the main language.
- **Spring Boot** to orchestrate APIs and services.
- **Spring Security** for authentication and authorization.
- **Spring Data JPA** for database interaction.
- **Database:** You can opt for PostgreSQL, MySQL, or another preferred relational database.
