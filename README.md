This repository demonstrates a common issue encountered when using nested routes in React Router v6.  The problem arises when navigating between nested routes and using the browser's back button; the route might unexpectedly reset to the default path instead of maintaining the correct navigation history.

The `bug.js` file contains the problematic code, showcasing how the back button functionality fails to work as expected. The solution is presented in `bugSolution.js` where the issue is addressed using the useNavigate hook.