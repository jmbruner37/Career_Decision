# Job Decision App

The Job Decision App is a web application that helps you make informed decisions about job opportunities by calculating your potential income over time based on various factors. It allows you to input specific variables related to your job and generates visualizations to help you compare different scenarios.

## Features

- Input various job-related variables such as age, industry, rate, bonus, rate increase, taxes, inflation, years worked, investment percentage, and many more.
- Calculates your total income over a specified number of years based on the provided variables.
- Generates visualizations to compare different job scenarios based on the input variables.

## Prerequisites

To run the Job Decision App locally, you need to have the following installed:

- Web browser
- Backend API (refer to the code implementation for details)

## How to Use

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in your preferred web browser.
3. Enter the values for the job-related variables in the input fields.
4. Click the "Calculate" button to calculate the total income and generate visualizations.
5. The calculated total income will be displayed on the page, and the visualizations will be shown below.

## Backend API

The Job Decision App interacts with a backend API to perform the income calculation and retrieve the necessary data for visualization. You need to implement the backend API separately using your preferred programming language or framework.

The backend API should handle the POST request sent by the app, perform the income calculation based on the provided variables, and respond with the following JSON data:

```json
{
    "yearsWorked": 10,
    "totalIncome": 100000,
    "variables": ["Variable 1", "Variable 2", ...],
    "values": [10, 20, ...]
}

