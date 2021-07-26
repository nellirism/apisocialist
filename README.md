# API Socialist

## Description:

This is a noSQL database using MongoDB that allows for API endpoints to interact with the database. Since this database is designed for a social networking platform, the database contains API endpoints for Users, their thoughts, and their friends' reactions to those thoughts.

# Table of Contents

- [Repository](#repository)
- [Walkthrough Video](#walkthrough%20video)
- [Examples](#examples)
- [Usage](#usage)
- [User Story](#user%20story)
- [Acceptance Criteria](#Acceptance%20criteria)
- [Contributions](#contributing)
- [Tests](#tests)
- [License](#license)
- [Questions](#questions)
- [Technologies Used](#languages)

## Repository:

- [My Github Profile](https://github.com/nellirism)

- [This Repository](https://github.com/nellirism/apisocialist)

## Walkthrough Video

## Usage:

- This database gives API endpoints for databse interaction with a soecial networking site.

## User Story:

- AS A social media startup
- I WANT an API for my social network that uses a NoSQL database
- SO THAT my website can handle large amounts of unstructured data

## Acceptance Criteria:

- GIVEN a social network API
- WHEN I enter the command to invoke the application
- THEN my server is started and the Mongoose models are synced to the MongoDB database
- WHEN I open API GET routes in Insomnia Core for users and thoughts
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
- THEN I am able to successfully create, update, and delete users and thoughts in my database
- WHEN I test API POST and DELETE routes in Insomnia Core
- THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list

## Tests:

- InsomniaCore

## Technologies Used:

- JavaScript
- Node
- Express
- Mongoose
