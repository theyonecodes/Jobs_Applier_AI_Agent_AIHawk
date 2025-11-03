# Tests

This folder contains test files for the AIHawk Jobs Applier AI Agent.

## Test Structure

Tests will include:
- Unit tests for individual components
- Integration tests for workflow validation
- End-to-end tests for complete application flow
- Mock tests for external API interactions

## Running Tests

```bash
# Install test dependencies
pip install -r requirements.txt

# Run all tests
pytest

# Run specific test file
pytest tests/test_filename.py

# Run with coverage
pytest --cov=src tests/
```

## Test Guidelines

- Write clear, descriptive test names
- Follow AAA pattern (Arrange, Act, Assert)
- Keep tests independent and isolated
- Mock external dependencies
- Aim for high code coverage
