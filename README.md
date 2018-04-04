![cf](https://i.imgur.com/7v5ASc8.png) Lab 38: Asset Uploads
======

## Submission Instructions
* Work in a fork of this repository
* Work in a branch on your fork
* Write all of your code in a directory named `lab-` + `<your name>` **e.g.** `lab-susan`
* Open a pull request to this repository
* Submit on canvas a question and observation, how long you spent, and a link to your pull request

## Configuration
Configure the root of your repository with the following files and directories. Thoughtfully name and organize any additional configuration or module files.
* **README.md** - contains documentation
* **.gitignore** - contains a [robust](http://gitignore.io) `.gitignore` file
* **.eslintrc.json** - contains the course linter configuration
* **.eslintignore** - contains the course linter ignore configuration
* **.babelrc** - contains babel config
* **package.json** - contains npm package config
* **webpack.config.js** - contains webpack config
* **src/** - contains the frontend code
* **src/components/** - contains your components
* **src/main.js** - contains the entire app
* **src/style** - containing your `.scss` partials and styles
* **src/style/main.scss** - contains the entry point for `.scss` partials

## Feature Tasks
##### Minimum Requirements

### Components
For this assignment, the naming convention and creation of your application components are up to you.  Given that you are following a convention similar to what we've been doing in lecture, you may want to organize your components as follows:

```html
<App />
  <Provider /> 
    <BrowserRouter />
      <LandingContainer />
        <AuthForm />
      <SettingsContainer />
        <ProfileForm />
```

### Clone Sluggram
Clone, configure and run the [sluggram](http://github.com/slugbyte/sluggram) application.

### Create a Frontend
Continue working on the application that you started yesterday.  You'll want to create a `<SettingsContainer>` (or similar), that contains a multi-purpose `<ProfileForm>` (or similar) that will give the user the ablity to create or update their profile.

### Testing
* Test all of your authentication based actions
* Test to ensure that authentication based actions are properly evalutated in your reducer
