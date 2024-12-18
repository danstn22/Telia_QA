# Telia Careers QA Test

This project is an automated testing framework for the **Telia Careers** website. It verifies the functionality of the job search feature and ensures that the website behaves as expected.

## Technologies and Dependencies

The project uses the following technologies:

- **Selenium WebDriver** – for browser automation.
- **JUnit 5** – for test execution and assertions.
- **AssertJ** – for writing readable assertions.

### Maven Dependencies:

- `selenium-java` – 4.25.0
- `junit-jupiter-api` – 5.11.3
- `junit-jupiter-params` – 5.10.2
- `assertj-core` – 3.26.3

These dependencies are specified in the `pom.xml` file and are automatically managed by Maven.

## Project Structure

The project structure is as follows:

- `src/test/java` - Contains all the test files and test classes.
- `pom.xml` - The Maven project configuration file, which lists all dependencies and plugins.

## Setup Instructions

To set up and run the project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/danstn22/Telia_QA.git
    ```

2. **Install dependencies:**

    Navigate to the project directory and install the dependencies using Maven:

    ```bash
    mvn install
    ```

3. **Run the tests:**

    To run the tests, use the following Maven command:

    ```bash
    mvn test
    ```

    This will execute all the tests defined in the project. Test results will be displayed in the terminal.

## Test Overview

The automated tests in this project focus on ensuring the correct functionality of the job search feature, including:

- **Job search results:** Verifying that valid job search results are returned.
- **No results scenario:** Ensuring that when no results are found, the appropriate message ("Oops! No results found") is displayed.
- **Basic user interaction checks:** Ensuring that essential interactions on the job search page work as expected.

## Planned Features and Improvements

- **Test Expansion:** Add more test cases for other features of the website, such as filtering results or pagination.
- **CI/CD Integration:** Integrate the tests with CI/CD tools (e.g., Jenkins, GitHub Actions) to run the tests automatically during the build process.
- **Cross-browser Testing:** Add cross-browser testing to ensure compatibility across different browsers (Chrome, Firefox, Edge, etc.).

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, feel free to contact the project maintainer at [your-email@example.com].
