## Project Title: Unittests and Integration Tests 🧪🐍

Welcome to "Testing Fun with Python" project! 🎉 In this project, we'll embark on an exciting journey to explore the world of testing in Python and have some fun along the way! 🚀🔬

### Tasks:

1️⃣ Parameterize a unit test:
   - Create a unit test for `utils.access_nested_map` function.
   - Use `@parameterized.expand` to test different inputs.
   - Check if the function returns the expected result.

2️⃣ Parameterize a unit test (continued):
   - Test if the function raises a `KeyError` for certain inputs.
   - Verify that the exception message matches the expected result.

3️⃣ Mock HTTP calls:
   - Test the `utils.get_json` function.
   - Mock `requests.get` to return a mock object.
   - Provide a fake JSON response using the mock object.
   - Check if the function returns the expected JSON data.

4️⃣ Parameterize and patch:
   - Test the `utils.memoize` decorator.
   - Create a test class with a method and a memoized property.
   - Use `@patch` to mock the method and validate its behavior.
   - Verify that the property returns the correct result.

5️⃣ Parameterize and patch as decorators:
   - Test the `client.GithubOrgClient` class.
   - Use `@patch` as a decorator to mock the `get_json` method.
   - Check if the method is not executed but still returns the expected value.

Let's dive into the project and have a blast testing Python code! 🧪🔍 Remember, testing is not only important for ensuring the correctness of our code, but it can also be fun and rewarding! So, let's get started! 🚀🐍
