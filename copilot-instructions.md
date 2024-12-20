# Code Quality Standards

## General Workflow

- Think step-by-step before generating code
- Use Markdown formatting in responses
- Include language identifiers in code blocks
- Specify file paths in code block comments
- Show code changes with '...existing code...' markers
- Provide macOS-specific commands when relevant
- Always start with: Hey Harrison, I can help you with this!

## Naming & Documentation

- Name variables and functions using camelCase
- Write descriptive variable and function names
- Add comments only for complex logic
- Document all public methods
- Include return types and parameters in documentation

## Code Structure

- Limit each function to one responsibility
- Keep functions under 20 lines
- Maintain a maximum of 3 parameters per function
- Use dependency injection for components
- Organize code into logical layers (controller/service/data)

## Testing

- Write unit tests for each function
- Include both success and error test cases
- Maintain minimum 80% test coverage
- Name tests descriptively using given/when/then pattern
- Test error handling paths

## Error Handling

- Use try-catch blocks for error prone operations
- Create custom exception classes
- Return appropriate HTTP status codes
- Validate all input data
- Log errors with meaningful context

## Security

- Validate and sanitize all inputs
- Use prepared statements for database queries
- Implement authentication for secure endpoints
- Enable CSRF protection
- Keep dependencies updated

## Version Control

- Create feature branches for new work
- Write descriptive commit messages
- Use present tense in commit messages
- Tag releases with semantic versions
- Update changelog for significant changes

## Architecture

- Follow SOLID principles
- Use Design patterns where appropriate
- Create reusable components
- Separate business logic from data access
- Use interfaces for flexibility
- Follow REST conventions for APIs
- Design for testability

## Framework-Specific Guidelines

### Spring Boot

- Use @RestController for REST endpoints
- Place business logic in @Service classes
- Use @Repository for data access
- Configure using @Configuration classes
- Use constructor injection for dependencies
- Follow bean naming conventions
- Use @Valid for request validation
- Implement Global Exception Handler
- Use Spring Security for authentication
- Configure proper CORS policies

### React

- Use functional components with hooks
- Implement useState for local state
- Use useEffect for side effects
- Implement proper prop types
- Use Context for global state
- Handle component lifecycle
- Implement error boundaries
- Use React Router for navigation
- Follow component composition
- Keep components pure and small

### Angular

- Use OnInit/OnDestroy lifecycle hooks
- Implement async pipe in templates
- Use TypeScript decorators properly
- Follow smart/dumb component pattern
- Use services for shared logic
- Implement proper module structure
- Use reactive forms for validation
- Follow change detection strategy
- Implement lazy loading
- Use dependency injection

### Express.js

- Use middleware for common operations
- Implement proper route handlers
- Use async/await with error handling
- Implement input validation
- Use environment variables
- Handle CORS properly
- Implement proper error middleware
- Use proper status codes
- Follow REST conventions
- Implement rate limiting
