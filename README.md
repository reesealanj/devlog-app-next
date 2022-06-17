# Devlog Web Application

An application project that seeks to create a web app for a developer to use to create a log of their work and search that base of notes based on filters and keywords.

## Author

- [Reese Jones](https://github.com/reesealanj)

## Requirements

1. Firebase account configured with both Firebase Authentication and FireStore

## Installation

1. Clone the repo
2. `cd` into the `devlog-app-next` directory
3. Ensure you make a copy of the `/config/env.local` and input all your proper keys
4. Run `npm install` to install all required packages and dependencies
5. Run `npm run dev` to start the dev server for the Next.js application

## Contribution

If you found a problem or want to submit an improvement to the project, use the Github Issues tab to create an Issue with a description of what you think needs to be changed/added. If you'd like to submit a PR with an update/fix, reference the issue number you created. Also please make sure to squash all your commits into one when you make your PR into the repository.

### Github Branching Strategy

- `main` - main branch, this is what will be deployed to DigitalOcean/whatever service it runs on
- `develop` - this is the "working branch" that is being used to develop while keeping production releases clean

## Project Goals/Wishlist

(feel free to make a PR to add to this list)

- Upload notes and comments/resources to a central database
- Aggregate notes into "books"/collections by project, technology, date/time
- Be able to full text search your previous work
- Once web application is polished out and well featured extend this into an Electron desktop app.
- more tbd...
