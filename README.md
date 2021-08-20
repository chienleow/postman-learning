# Postman Learning

## Gatsby
🎥 [Gatsby Tutorial](https://youtube.com/playlist?list=PL4cUxeGkcC9hw1g77I35ZivVLe8k2nvjB)
- React-based open-source framework for creating websites and apps.
- Static site generator (SSG)
- Uses a combination of React & GraphQL

## React
- **My React Notes: [React Recap]**(https://github.com/chienleow/react-notes)
- `dangerouslySetInnerHTML`
  -  React’s replacement for using innerHTML in the browser DOM.
  -  Resources: [React Doc](https://reactjs.org/docs/dom-elements.html#dangerouslysetinnerhtml)
- **Typechecking with PropTypes** - 📖 [React doc](https://reactjs.org/docs/typechecking-with-proptypes.html)
  - 🎥 [Learn React PropTypes In 13 Minutes](https://www.youtube.com/watch?v=cx0S8JyiVxc)
  - When writing React, a common bug - accidentally pass incorrect props to component, and it is difficult to track down these bugs
    - As an example: `age="15"` should be a number, but we pass in as a string, `${age + 5}` would return `155` instead of `20`
  - With PropTypes: easily define exactly what the props should be for a component, you will see errors in inspect when props are incorrect

## Web Dev
- **How Does a Trailing Slash Impact SEO?** 📖 [Read](https://www.safaridigital.com.au/blog/trailing-slash-seo/)
  - If there are two separate pages with the same content – one with a slash at the end of the URL and one without – the two separate pages will be identical, resulting in duplicate content. Google has a hard time figuring out which of the two is the original source, and the search engine crawlers are left confused.
- **Everything You Need to Know About rel=”noopener noreferrer”** 📖 [Read](https://clever-solution.com/everything-you-need-to-know-about-rel-noopener-noreferrer-tags-purpose-benefits-and-seo-impact/)
  - The noopener is needed to enhance the security of your website and prevent other websites from gaining access to your page (through the browser session).
  - The noreferrer is used to protect referral information from being passed to the target website and this also hides referral traffic in Google analytics.

## General Programming Questions
**1. What is Linting?** 📖 [Read](https://www.perforce.com/blog/qac/what-lint-code-and-why-linting-important)
- Linting is the process of checking the source code for programmatic and stylistic errors
- Done by using a lint tool (a.k.a Linter)
