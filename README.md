<!-- TABLE OF CONTENTS -->
## Table of Contents

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)


<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

There are many great README templates available on GitHub, however, I didn't find one that really suit my needs so I created this enhanced one. I want to create a README template so amazing that it'll be the last one you ever need.

Here's why:
* Your time should be focused on creating something amazing. A project that solves a problem and helps others
* You shouldn't be doing the same tasks over and over like creating a README from scratch
* You should element DRY principles to the rest of your life :smile:

Of course, no one template will serve all projects since your needs may be different. So I'll be adding more in the near future. You may also suggest changes by forking this repo and creating a pull request or opening an issue.

A list of commonly used resources that I find helpful are listed in the acknowledgements.

### Built With
This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [React](https://reactjs.org/)
* [Redux](https://redux.js.org/)
* [Node.js](https://nodejs.org/)
* [Koa](https://koajs.com/)
* [Material UI](https://material-ui.com/)


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
```sh
npm install npm@latest -g
```

### Installation

1. Register your app and obtain OAuth 2.0 client keys at [Google APIs](https://console.developers.google.com/).

2. Subscribe you app to the YouTube v3 API and obtain an API key for the API.
3. Clone the repo
```sh
git clone https://github.com/your_username_/Project-Name.git
```
3. Install NPM packages for both client and server, by running the following command separately in the *client* and the *server* directory
```sh
npm install
```
4. Specify the following environment variables either in the server environment, or in a *.env* file inside the *server* directory:

  - GOOGLE_CLIENT_ID - client ID obtained from Google
  - GOOGLE_CLIENT_SECRET - client secret key obtained from Google
  - GOOGLE_REDIRECT_URI - callback URL specified in Google APIs (e.g. *http://localhost:3001/login/google-cb*)
  - CLIENT_URL - URL of the client part of the application, including port number (e.g. *http://localhost:3000*)
  - SERVER_HOST - host name on which the server is running (e.g. *localhost*)
  - SERVER_PORT - port on which the server is running (e.g. *3001*)
  - MONGODB_URI - connection URI for MongoDB (e.g. *mongodb://localhost:27017/devfitvid*)
  - SERVER_JWT_SECRET - secure secret for JWT signing

5. Specify the following environment variables either in the client environment, or in a *.env* file inside the *client* directory:

- REACT_APP_SERVER_URL - URL of the server part of the application, including port number (e.g. *http://localhost:3000*)
- REACT_APP_GOOGLE_API_KEY - API key for YouTube v3 API obtained from [Google APIs](https://console.developers.google.com/)

<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
