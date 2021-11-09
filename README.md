# Postman Learning
- [Gatsby](#gatsby)
- [React](#react)
- [JavaScript](#javascript)
- [Web Dev](#web-dev)
- [API](#api)
- [NPM](#npm)
- [General Programming Questions](#general-programming-questions)

## Gatsby
🎥 [Gatsby Tutorial](https://youtube.com/playlist?list=PL4cUxeGkcC9hw1g77I35ZivVLe8k2nvjB)
- React-based open-source framework for creating websites and apps.
- Static site generator (SSG)
- Uses a combination of React & GraphQL

## React
- [What is React?](https://github.com/chienleow/react-notes#what-is-react)
- [Why use React?](https://github.com/chienleow/react-notes#why-use-react)
- [Components](https://github.com/chienleow/react-notes#components)
- [State](https://github.com/chienleow/react-notes#state)
- [Hooks](https://github.com/chienleow/react-notes#hooks)

### Styled Components in React
- 🎥 [Styled Components Crash Course & Project](https://youtu.be/02zO0hZmwnw)
- styled-components allows us to write CSS in JS in an elegant and reusable way

### `dangerouslySetInnerHTML`
  -  React’s replacement for using innerHTML in the browser DOM.
  -  Resources: [React Doc](https://reactjs.org/docs/dom-elements.html#dangerouslysetinnerhtml)
### Typechecking with PropTypes - 📖 [React doc](https://reactjs.org/docs/typechecking-with-proptypes.html)
  - 🎥 [Learn React PropTypes In 13 Minutes](https://www.youtube.com/watch?v=cx0S8JyiVxc)
  - When writing React, a common bug - accidentally pass incorrect props to component, and it is difficult to track down these bugs
    - As an example: `age="15"` should be a number, but we pass in as a string, `${age + 5}` would return `155` instead of `20`
  - With PropTypes: easily define exactly what the props should be for a component, you will see errors in inspect when props are incorrect
### React fragments vs div containers
  - Component returns multiple elements, to avoid adding extra nodes to the DOM, `<React.Fragment>` let you group a list of children.

## JavaScript
### How to Choose the Right NPM Package for Your Project? 📖 [Read](https://betterprogramming.pub/how-to-choose-the-right-npm-package-for-your-project-c3d1cc25285e)

## Web Dev
### How Does a Trailing Slash Impact SEO? 📖 [Read](https://www.safaridigital.com.au/blog/trailing-slash-seo/)
  - If there are two separate pages with the same content – one with a slash at the end of the URL and one without – the two separate pages will be identical, resulting in duplicate content. Google has a hard time figuring out which of the two is the original source, and the search engine crawlers are left confused.
### Everything You Need to Know About rel=”noopener noreferrer” 📖 [Read](https://clever-solution.com/everything-you-need-to-know-about-rel-noopener-noreferrer-tags-purpose-benefits-and-seo-impact/)
  - The noopener is needed to enhance the security of your website and prevent other websites from gaining access to your page (through the browser session).
  - The noreferrer is used to protect referral information from being passed to the target website and this also hides referral traffic in Google analytics.
### Be Sure to Provide Titles for Iframes (for accessibility) 📖 [Read](https://dequeuniversity.com/tips/provide-iframe-titles)
  -  When an iframe is given a meaningful title, screen reader users can pull up a list of frames and identify the content or purpose of the iframe based on its title.
### Increasing Headline Clicks with Eyebrow Text 📖 [Read](https://uxmovement.com/content/increasing-headline-clicks-with-eyebrow-text/)
  -  Eyebrow text is a descriptive keyword or phrase placed above the main headline and blurb.

## API
### OpenAPI 3.0 📖 [Docs](https://support.smartbear.com/swaggerhub/docs/tutorials/openapi-3-tutorial.html) 🎥 [How to Design and Document APIs](https://youtu.be/6kwmW_p_Tig)
- The latest version of the OpenAPI Specification - an open source format for describing and documenting APIs
  <details><summary>A simple OpenAPI 3.0 specification</summary>
  <p>
  
  ```
  openapi: 3.0.0
  info:
    version: 1.0.0
    title: Sample API
    description: A sample API to illustrate OpenAPI concepts
  paths:
    /list:
      get:
        description: Returns a list of stuff              
        responses:
          '200':
            description: Successful response
  ```
  </p>
  </details>

### API design
  - The process of developing Application Programming Interfaces (APIs) that expose data and application functionality for use by developers and users
  
### Differences Between API Documentation, Specifications, and Definitions
  - All related, but different entities, each serves a crucial purpose
  - **API Documentation:** _Instructions for developers and API consumers how to use the API_
  - **API Specification:** _Provides a broad understanding of the functionality of the API and the expected results_
  - **API Definition:** _Machine consumption of an API, providing machine-readable format for use_

### REST vs. SOAP
- REST and SOAP are 2 different approaches to online data transmission, both define how to build APIs

### API Testing
- API (Application Programming Interface) is the code that enables communication between two software programs
- API Testing ensures APIs meet functionality, security, performance and reliability expectations
- Making requests to one or more API endpoints, comparing the response with expected results

## NPM
### UUID
- [uuid](https://www.npmjs.com/package/uuid)
- Generate unique identifier for your React app.

### React Share
- [react-share](https://github.com/nygardk/react-share)
- Social media share buttons and share counts for React.

## General Programming Questions
### 1. What is Linting? 📖 [Read](https://www.perforce.com/blog/qac/what-lint-code-and-why-linting-important)
- Linting is the process of checking the source code for programmatic and stylistic errors
- Done by using a lint tool (a.k.a Linter)
- [ESLint](https://eslint.org/) for JavaScript

## Git
### Git Commands Explained with Cats! 🐱 📖 [Read](https://girliemac.com/blog/2017/12/26/git-purr/)
