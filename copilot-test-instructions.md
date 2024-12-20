# Test Generation Instructions

## Java

- Use JUnit 5 with AssertJ assertions
- Follow AAA pattern (Arrange-Act-Assert)
- Test class naming: `{ClassUnderTest}Test`
- Use `@DisplayName` for readable test cases
- Implement parameterized tests where applicable
- Coverage: unit, integration, mock with Mockito
- Use `@SpringBootTest` for integration tests

## JavaScript/TypeScript

- Jest for unit testing
- React Testing Library for components
- Test file naming: `*.test.js` or `*.spec.js`
- Use describe/it blocks
- Mock external dependencies
- Snapshot testing when appropriate
- E2E with Cypress or Playwright

## Python

- pytest as testing framework
- Test file prefix: `test_`
- Use fixtures for test setup
- parametrize for multiple test cases
- Mock with unittest.mock or pytest-mock
- Coverage with pytest-cov

## Testing Patterns (All Languages)

- One assertion per test
- Clear test naming: should_doSomething_when_condition
- Mock external dependencies
- Test edge cases and error scenarios
- Avoid test interdependence
- Include positive and negative tests
- Test async operations properly
