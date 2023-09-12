# React Tabs with Router
 [DEMO LINK](https://nazarbaraban.github.io/react_tabs-with-router/)

 Navigation Links:

Implemented navigation links for both the Home and Tabs pages.

Ensured that these links are visible on every page.

Applied the is-active class to highlight the active link, providing visual feedback to users.

TabsPage Nested Routes:

Created a TabsPage component that works for both /tabs and /tabs/:tabId paths using nested routes.

Utilized React Router's <Route> component with index and parameterized routes for flexible routing.

Tab Selection and URL Update:

Implemented tab selection functionality that updates the URL on tab clicks.

Constructed URLs following the format /tabs/:tabId where tabId is replaced with the actual tab's ID.

Replaced <a href="#..."> with <Link to="/tabs/..."> and removed onClick handlers.

Utilized the useParams hook to read tabId from the URL.

Displayed a "Please select a tab" message if the tabId does not match any available tab.

Persistent State After Reload:

Ensured that the page maintains the same content after a page reload, providing a seamless user experience.
Redirect from /home to /:

Added a redirect from /home to the root path / using the <Navigate> component to maintain consistent navigation.
Page Not Found:

Displayed the "Page not found" title for all other URLs, enhancing user experience with clear error messages.

