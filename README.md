# Hi 👋, I'm Alex Cutler

**Full-Stack & Mobile Developer | Cloud, APIs, and Web/Mobile Applications**

## About Me

Recent Software Engineering graduate building production-ready applications with modern full-stack technologies.  Interested in cloud systems, distributed systems, and full-stack and mobile development.

I am available for part time freelance software development work.  Feel free to look through my <a href="https://cacutler.github.io/">GitHub Page</a> for further details.

- 🔭 I'm currently working on a **fitness and calorie tracker and workout planner**.
- 🌱 I'm currently learning **Flutter/Dart, FastAPI/Python, and PostgreSQL**.
- 💬 Ask me about **web (backend and frontend) and mobile development**.
- 📫 How to reach me **calexcutler@gmail.com**.
- 👨‍💻 All of my projects are available at my **[GitHub Profile](https://github.com/cacutler)**.
- 📄 Know about my experiences on my **[resume](https://drive.google.com/file/d/18a-ig5-SYhSh4E9Z4K_2VpRcbv2kTaJ6/view?usp=sharing)**.

**Profile Views** <p align="left"><img src="https://komarev.com/ghpvc/?username=cacutler&label=Profileviews&color=0e75b6&style=flat" alt="cacutler"/></p>

## My Core Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

**Frameworks**

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

**Databases**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

**Cloud Platforms**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

## Hire Me For:

- Backend Development
- Frontend Development
- Fullstack Development
- Mobile Development

## Recent Projects

- The Recipe Archive
    - This project aims to "digitize" family recipes by allowing users to add in and search through recipes.
    - It uses Java and Spring Boot for the backend, PostgreSQL for the database, and Svelte and SvelteKit for the frontend.
    - The frontend uses REST APIs to connect to the backend and JWTs for user authentication.
    - Screenshot:
    ![Recipe Archive Homepage](Recipe-Archive-Homepage.png)
- Card Game Point Tracker
    - This is a point tracking app used to help keep track of points during card games (think games like Wackee Six, Cover Your Assets, Skull King, etc.)
    - The iOS app is built with SwiftUI and the Android app is built with Kotlin and Jetpack Compose.
    - I wrote several unit and instrumented tests for both apps.
    - Android Screenshot:
    ![Android Point Tracker Screenshot](Android-Home-Screen.png)
    - iOS Screenshot:
    ![iOS Point Tracker Screenshot](iOS-Home-Screen.png)
- Cutler Code Business Website
    - This is a website for a personal business idea I have in mind for creating custom software for clients who wish to work with me.
    - It uses MySQL for the database and the Laravel PHP framework for both the frontend and backend.
    - The frontend uses dozens of REST APIs to communicate with the backend.
    - I wrote several unit and feature tests to test the website and added a small CI/CD pipeline with GitHub Actions to automate the test runner when I push code to the repository.
    - Screenshot:
    ![Cutler Code Homepage](Cutler-Code-Homepage.png)

## Featured AWS Project: Serverless Payment Clearinghouse

**Python | AWS Lambda | DynamoDB | Distributed Systems**

Designed and implemented a scalable serverless API that abstracts payment processing between merchants and multiple financial institutions.  The system simulates hight-volume transaction flow while enforcing strict SLA and security constraints.

<details>
<summary>Click to expand details</summary>

**🏗️ Architecture**

- **Amazon Web Services Lambda** for stateless transaction processing
- **Amazon Web Services DynamoDB** for merchant authentication and transaction logging
- REST-based integration with heterogeneous downstream banking APIs
- Token-based merchant authentication model

**⚙️ Engineering Highlights**

- Routed transaction across 5 vendor-specific banking APIs with differing schemas
- Normalized inconsistent downstream responses into a unified status model
- Enforced <3 second SLA with timeout handling and graceful degradation
- Simulated 100+ concurrent merchants to evaluate scalability and resilience
- Processed 700+ transactions under load conditions
- Designed with PCI-aware constraints (no sensitive card data persisted)
- Identified and resolved JSON schema validation issue discovered during production-style testing

**📈 Production Considerations**

- Designed for horizontal scalability using serverless architecture
- Implemented defensive JSON parsing and error handling
- Evaluated cost vs availability tradeoffs in free-tier cloud environment
- Future enhancements: IAM role-based auth, structured logging, rate limiting, circuit breaker pattern

Source code remains private due to academic requirements. Architecture and design details are shared for portfolio purposes.

</details>

## Additional Languages and Tools I Used

<p align="left">
    <a href="https://developer.mozilla.org/en-US/docs/Web/android" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=androidstudio" alt="android" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/angular" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=angular" alt="angular" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/aws" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=aws" alt="aws" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/c" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=c" alt="c" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/cplusplus" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=cpp" alt="cplusplus" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/csharp" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=cs" alt="csharp" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/css3" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=css" alt="css3" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/django" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=django" alt="django" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/express" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=express" alt="express" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/figma" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=figma" alt="figma" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/firebase" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=firebase" alt="firebase" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/flask" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=flask" alt="flask" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/git" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=git" alt="git" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/html5" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=html" alt="html5" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/java" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=java" alt="java" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/javascript" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=js" alt="javascript" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/kotlin" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=kotlin" alt="kotlin" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/laravel" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=laravel" alt="laravel" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/linux" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=linux" alt="linux" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/mongodb" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=mongodb" alt="mongodb" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/mysql" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=mysql" alt="mysql" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/nestjs" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=nestjs" alt="nestjs" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/nextjs" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=nextjs" alt="nextjs" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/nginx" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=nginx" alt="nginx" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/nodejs" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=nodejs" alt="nodejs" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/nuxtjs" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=nuxtjs" alt="nuxtjs" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/php" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=php" alt="php" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/postgresql" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=postgres" alt="postgresql" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/postman" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=postman" alt="postman" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/python" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=py" alt="python" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/rails" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=rails" alt="rails" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/react" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=react" alt="react" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/ruby" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=ruby" alt="ruby" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/selenium" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=selenium" alt="selenium" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/spring" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=spring" alt="spring" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/sqlite" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=sqlite" alt="sqlite" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/swift" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=swift" alt="swift" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/tailwind" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=tailwind" alt="tailwind" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/typescript" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=ts" alt="typescript" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/unity" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=unity" alt="unity" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/vuejs" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=vue" alt="vuejs" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/vuetify" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=vuetify" alt="vuetify" width="40" height="40"/></a>
</p>

## How to Connect with Me

<p align="center">
    <a href="https://github.com/cacutler" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/github.svg" alt="cacutler" height="30" width="40"/></a>
    <a href="https://linkedin.com/in/cameron-cutler" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="cameron-cutler" height="30" width="40"/></a>
    <a href="https://stackoverflow.com/users/26648996/alex-cutler" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/stack-overflow.svg" alt="26648996/alex-cutler" height="30" width="40"/></a>
    <a href="https://fb.com/alex.cutler.10236" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="alex.cutler.10236" height="30" width="40"/></a>
    <a href="https://instagram.com/@cacutler1" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="@cacutler1" height="30" width="40"/></a>
    <a href="https://twitter.com/cacutler1" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="cacutler1" height="30" width="40"/></a>
    <a href="https://youtube.com/@alexsoftwarecorner" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="@alexsoftwarecorner" height="30" width="40"/></a>
    <a href="https://leetcode.com/agentalex" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="agentalex" height="30" width="40"/></a>
</p>

## My GitHub Stats

<p align="center"><img src="https://github-readme-stats-git-master-alex-cutlers-projects.vercel.app/api?username=cacutler&show_icons=true&locale=en" alt="cacutler"></p>
<p align="center"><img src="https://github-readme-stats-git-master-alex-cutlers-projects.vercel.app/api/top-langs/?username=cacutler&langs_count=20&layout=pie" alt="cacutler"></p>