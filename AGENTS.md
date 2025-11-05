# Agent Instructions

This repository is being built by AI agents. Follow these guidelines:

## Architecture

**Frontend**: Next.js 14 + TypeScript + Tailwind CSS + ShadcnUI
**Backend**: Node.js + Express + PostgreSQL + Prisma ORM + JWT
**Database**: PostgreSQL (Railway)

## Project Structure

```
/
├── frontend/       # Next.js 14 + TypeScript + Tailwind CSS + ShadcnUI
├── backend/        # Node.js + Express + PostgreSQL + Prisma ORM + JWT
├── README.md       # Project documentation
└── AGENTS.md       # This file
```

## Development Guidelines

### Code Quality
- Write clean, idiomatic code for the chosen language
- Include TypeScript types (if applicable)
- Add error handling for all operations
- Write comments for complex logic
- Follow best practices for the framework

### Testing
- Write unit tests for business logic
- Write integration tests for API endpoints
- Ensure all tests pass before merging
- Test error scenarios

### Git Workflow
1. Create feature branch: `feature/feature-name`
2. Implement feature with tests
3. Commit with clear messages
4. Push to branch
5. AI will test and merge to main

### API Guidelines
- RESTful endpoints
- Proper HTTP status codes
- JSON responses
- Error responses with helpful messages
- Input validation

### Database
- Use migrations for schema changes
- Index frequently queried fields
- Use foreign keys for relationships
- Validate data before saving

## Vision

Server-side rendered React application optimized for content delivery with SEO support, static generation for public pages, and dynamic rendering for authenticated user interactions

RESTful API handling authentication, CRUD operations for posts and comments, with JWT-based session management and markdown storage

## Requirements

- User authentication required
- Multi-user support required



## Deployment

This project will be automatically deployed to Railway when merged to main.

---

*This file is used by AI agents to understand the project architecture and coding standards.*
