# Angular GitHub User Viewer

This is an Angular application that allows users to view information about a GitHub user, including their repositories and the languages used in those repositories.

## What I've Done in This Project

- Developed an Angular application that fetches and displays GitHub user information and repositories.
- Implemented unit tests for the application using Angular's testing tools and Jasmine.
- Created a responsive and user-friendly user interface for viewing GitHub data.

## Assumptions Made

- This project does not require a GitHub API key.
- ### Features and Functionality

    - The topics are presented in a scrollable format.
    - A search bar is provided at the top of the page, enabling users to input a GitHub username.
    - By default, the page loads with the data of the GitHub user "johnpapa".
    - The repository descriptions are designed to be scrollable vertically

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Running the Tests](#running-the-tests)

## Getting Started

### Prerequisites

Before you begin, make sure you have the following tools installed:

- [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/)
- [Angular CLI](https://angular.io/cli)

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/your-repo.git
    ```
2. **Navigate to the project directory:**

    ```bash
    cd your-repo
    ```

3. **Install the project dependencies:**

    ```bash
    npm install
    ```

## Usage

1. **Start the development server:**

    ```bash
    ng serve
    ```

2. **Open your web browser and go to [http://localhost:4200/](http://localhost:4200/) to view the application.**

3. **Enter a GitHub username in the input field to view user details, repositories, and their associated languages.**

## Running the Tests

To run the unit tests for this project, use the following command:

```bash
ng test
```
