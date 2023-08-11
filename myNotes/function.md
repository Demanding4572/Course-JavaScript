```mermaid
gitGraph
  commit id:"Learn Basics"
  commit id:"DOM Manipulation"
  commit id:"Events and Event Handling"
  commit id:"Functions and Scope"
  branch develop
    commit id:"AJAX and Fetch API"
    commit id:"Promises and Async/Await"
    commit id:"ES6+ Features"
    commit id:"Module System (CommonJS, ES Modules)"
    commit id:"Unit Testing (e.g., Jest)"
    commit id:"Version Control (Git)"
  checkout main
    commit id:"Advanced JavaScript Concepts"
    commit id:"Design Patterns"
    merge develop
      commit id:"Build Tools (Webpack, Babel)"
      commit id:"Frameworks (React, Vue, Angular)"
      commit id:"State Management (Redux, Vuex)"
      commit id:"Routing and Navigation"
      commit id:"API Integration"
      commit id:"Responsive Design (CSS)"
      commit id:"Frontend Testing"
      commit id:"Linting and Code Quality"
      commit id:"Deployment and Hosting"
      commit id:"Continuous Integration/Continuous Deployment"
