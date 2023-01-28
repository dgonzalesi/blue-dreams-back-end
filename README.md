<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
  - [:card_index: Entity Relationship Diagram](#er-diagram)
  - [🚀 Live Demo](#live-demo)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
  - [Deployment](#triangular_flag_on_post-deployment)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [❓ FAQ](#faq)
- [📝 License](#license)

<!-- PROJECT DESCRIPTION -->

# 📖 Blue Dream Yatch Booking App 
Blue Dream Yatch Booking Backend is a yacht booking application where user can register new accounts, login and book a set of different boats. It is built and connected by using two different repos, including Back-end(Rails) and Front-end(React/Redux).

#### Link to React App [Blue-Dream-Booking-Frontend](https://github.com/dgonzalesi/blue-dreams-front-end.git)

## 🛠 Built With <a name="built-with"></a>

- Ruby on Rails
- Ruby
- Bubocop
- Gems
  - Rspec
  - Capybara
  - Selenium-webdriver
  - Bcrypt
  - JWT
  - Devise

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Client</summary>
  <ul>
    <li>React</li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li>Ruby on Rails</li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>

- **[Create and run necessary migration files]**
- **[Match table and column names to the ERD diagram.]**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ER DIAGRAM-->

## :card_index: Entity Relationship Diagram <a name="er-diagram"></a>

The end result should follow the following data model (this is an Entity Relationship Diagram that you are already familiar with):

![image](https://drawsql.app/teams/microverse-96/diagrams/blue-dream-yatch)
  
<!-- LIVE DEMO -->

## 🚀 Live Demos and Importand links <a name="live-demo"></a>

- [Blue Dream  Frontend deployment link]()

- [Blue Dream Backend deployment link](https://blue-dreams-back-end.herokuapp.com/)
> Note this is for information purpose, however if you go to this link you wont be able to see a content, since it is API only(It will retrieve json responses)
<p align="right">(<a href="#readme-top">back to top</a>)</p>

- [Link to the Blue-Dream-Yatch API documentation](https://documenter.getpostman.com/view/25472635/2s8ZDbUzpv#162b150b-68bd-4c85-860b-157a56653ab9)

## Roadmap

 - Set up the repository/repositories on GitHub and use Gitflow.
 - Set up Postgres for the database
 - Create controllers, endpoints and models
 - Use Rails to create API.
 - Use React & Redux to create frontend UI.
 - Create README

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

## Frontend repository

- Run the command bellow first in your terminal in a different folder and open the file using cd <the name of the file> if needed.
> git clone https://github.com/dgonzalesi/blue-dreams-front-end.git
### Prerequisites

In order to run this project you need:
`Git` and `Ruby`

```
 gem install rails
```

### Install

Install this project with:

Run the command bellow first and open the file using cd <the name of the file> if needed.

> git clone github.com/dgonzalesi/blue-dreams-back-end.git
```sh or bash
  bundle install
```

Create and migrate the database
```sh or bash
 rails db:create
 rails db:migrate
 rails db:seed
```

### Usage

To run the project, execute the following command:

```sh or bash
  rails server or rails s
```
  
  
### Tests Procedure

When you are going to start the tests, please follow commands in your terminal:

```- rspec or,
   - rspec spec/models/user_spec.rb, in order to specify the exact path
   - rspec spec/models/user_spec.rb:10, in order to specify a special test method
  
  It's a good practice to run the tests after making any changes to the codebase or before deploying the application to ensure that everything is working as expected.
  
  Finally, you can check the RSpec documentation on how to use those options and configure it according to your project needs.
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AUTHORS -->
## 👥 Authors <a name="authors"></a>

<div id="badges"align="center">

## 👤 **Maximiliano Ungredda**

</div>
<div id="badges"align="center">
  <a href="https://www.linkedin.com/in/maximiliano-ungredda/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://github.com/renercrows">
    <img src="https://img.shields.io/badge/github-black?style=for-the-badge&logo=github&logoColor=white" alt="Github Badge"/>
  </a>
  <a href="https://twitter.com/">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>
<div id="badges"align="center">

## 👤 **Robin Benitez**

</div>
<div id="badges"align="center">
  <a href="https://www.linkedin.com/in/robin-benitez-mora/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://github.com/robinbenitezmora">
    <img src="https://img.shields.io/badge/github-black?style=for-the-badge&logo=github&logoColor=white" alt="Github Badge"/>
  </a>
  <a href="https://twitter.com/mecanico_robin">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>
<div id="badges"align="center">

## 👤 **Diego Hernández**

</div>
<div id="badges"align="center">
  <a href="https://www.linkedin.com/in/diegoarturoh/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://github.com/diegoh40">
    <img src="https://img.shields.io/badge/github-black?style=for-the-badge&logo=github&logoColor=white" alt="Github Badge"/>
  </a>
  <a href="https://twitter.com/Diegoart80">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>
<div id="badges"align="center">

## 👤 **Daniel Gonzales**

</div>

<div id="badges"align="center">
  <a href="https://www.linkedin.com/in/daniel-g-sierra-60472719">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://github.com/dgonzalesi/">
    <img src="https://img.shields.io/badge/github-black?style=for-the-badge&logo=github&logoColor=white" alt="Github Badge"/>
  </a>
  <a href="https://twitter.com/dgonzalesi">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>
<div id="badges"align="center">

## 👤 **Andy Menutti**

</div>

<div id="badges"align="center">
  <a href="http://linkedin.com/in/andres-menutti/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://github.com/andym80/">
    <img src="https://img.shields.io/badge/github-black?style=for-the-badge&logo=github&logoColor=white" alt="Github Badge"/>
  </a>
  <a href="http://linkedin.com/in/andres-menutti/">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

- [ ] **[Controllers, and Models specs]**
- [ ] **[Improve overrall style and perfomance of the application]**
- [ ] **[Admin role to allow only admins to Add hotels]**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

Give a ⭐️ if you like this project!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

- We want to say thank you to [Murat Korkmaz](https://www.behance.net/muratk) on Behance the creator of this beautiful [design](https://www.behance.net/gallery/26425031/Vespa-Responsive-Redesign) that we used as a guide to build our project.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FAQ (optional) -->

## ❓ FAQ <a name="faq"></a>

- **Can i use this project as mine?**

  - This project is for educational purposes and it belongs to its creators, however you can clone it and use it a guide for creating yours as part of
  an educational project.

- **This project is availabe to do actual reservations?**

  - No, however it works almost the same, and you could use it in the future for creating your own app.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./MIT.md) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
