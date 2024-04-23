# Tech Overflow - A developers community

## 📝 Description

- [Installation](#installation)
- [Usage](#usage)

## Setup Project

To get this project up and running in your development environment, follow these step-by-step instructions.

### Prerequisites

We need to install or make sure that these tools are pre-installed on your machine:

- [NodeJS](https://nodejs.org/en/download/): It is a JavaScript runtime build.

- [Git](https://git-scm.com/downloads): It is an open source version control system.

### Install Project

1. Clone the Repository

```bash
git clone https://github.com/Sumitkumar-Thakur/TechOverflow.git
```

2. Install packages

```
npm install
```

3. create a `.env` file add necessary credencitals

```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=
NEXT_CLERK_WEBHOOK_SECRET=
NEXT_PUBLIC_TINY_EDITOR_API_KEY=
MONGODB_URL=
NEXT_PUBLIC_SERVER_URL=
OPENAI_API_KEY=
NEXT_PUBLIC_RAPID_API_KEY=
```

4. Run the project using command below

```bash
npm run dev
```

### To-Do

- [ ] Enable users to save jobs to their favorites list.
- [x] Allow users to apply to a job directly from the app.
- [ ] Provide a simple and intuitive user interface for easy navigation.
- [ ] Allow users to filter jobs based on job title, location, or company.

### How to Contribute

Want to contribute? Great!

To fix a bug or enhance an existing module, follow these steps:

- Fork the repo
- Create a new branch (`git checkout -b improve-feature`)
- Make the appropriate changes in the files
- Add changes to reflect the changes made
- Commit your changes (`git commit -am 'Improve feature'`)
- Push to the branch (`git push origin improve-feature`)
- Create a Pull Request

### Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue.
