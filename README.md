<h1 align="center">
    <img alt="" title="" src=".github/logo.svg">
</h1>

<p align="center">	
	
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/brunocassis/be-the-hero">
	
  <a href="https://www.linkedin.com/in/bruno-conehero-de-assis-06073a104/">
    <img alt="Made by Bruno Assis" src="https://img.shields.io/badge/made%20by-BrunoAssis-%2304D361">
  </a>
  
  <a href="https://github.com/brunocassis/be-the-hero/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/brunocassis/be-the-hero">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
  
</p>

<p align="center">
  <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-Technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-use">How to use</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

## 💻 Project

Be the Hero is a project developed based on raising funds for NGOs, connecting people who want to help with people who need that help.
A web and mobile version were created. The mobile version is integrated with WhatsApp and E-mail.

<h1 align="center">
    <img alt="Example" title="Example" src=".github/home.png" width="100%" />
</h1>


## :rocket: Technologies

This project was developed with the following technologies:

- [Node.js][nodejs]
- [JavaScript][javascript]
- [React][reactjs]
- [React Native][rn]
- [Expo][expo]

## 🔖 Layout

To access the layout use [Figma](https://www.figma.com/file/2C2yvw7jsCOGmaNUDftX9n/Be-The-Hero---OmniStack-11?node-id=0%3A1). You need an account in order to access it.

## :information_source: How To Use

To clone and run this application, you'll need [Git](https://git-scm.com), [Node.js][nodejs] + [Yarn][yarn] or [npm][npm] installed on your computer.

From your command line:

### Install API 

```bash
# First, clone this repository
$ git clone https://github.com/brunocassis/be-the-hero.git

# Go into the repository
$ cd be-the-hero/backend

# Install dependencies
$ yarn install
# All yarn commands can be made using npm also!

# Run Migrates
$ yarn knex:migrate

# Run Seeds
$ yarn knex:seed

# Start server
$ yarn dev

#running on port 3333

```

### Install Front-end

```bash
# Clone this repository
$ git clone https://github.com/brunocassis/be-the-hero.git

# Go into the repository
$ cd be-the-hero/frontend

# Install dependencies
$ yarn install

# Run
$ yarn start

```

### Install Mobile

```bash
# Clone this repository
$ git clone https://github.com/brunocassis/be-the-hero.git

# Go into the repository
$ cd be-the-hero/mobile

# Install dependencies
$ yarn install

# Run
$ yarn start

# Expo will open, just scan the qrcode on terminal or expo page

```
## 🤔 How to contribute

-  Make a fork;
-  Create a branch with your feature: `git checkout -b my-feature`;
-  Commit changes: `git commit -m 'feat: My new feature'`;
-  Make a push to your branch: `git push origin my-feature`.

After merging your receipt request to done, you can delete a branch from yours.

## :memo: License

This project is under the MIT license. See the [LICENSE](https://github.com/brunocassis/be-the-hero/blob/master/LICENSE) for details.

---

Done by Bruno Assis :wave: [Get in touch!](https://www.linkedin.com/in/bruno-conehero-de-assis-06073a104/)

[npm]: https://www.npmjs.com/
[nodejs]: https://nodejs.org/
[javascript]: https://www.javascript.com/
[expo]: https://expo.io/
[reactjs]: https://reactjs.org
[rn]: https://facebook.github.io/react-native/
[yarn]: https://yarnpkg.com/
