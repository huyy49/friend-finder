### Overview
This Friend Finder module will first ask the current user to complete a survey with 10 questions. The answers will be compared with the previous entered users and the absolute differences of each answer will be calculated. The previous user with the minimum of sum of the differences will be suggested to the current user. The current user will then be added to the API as well.

### Required Node API/Packages
  * express
  * path

### Structure
FriendFinder
  - .gitignore
  - app
    - data
      - friends.js
    - public
      - home.html
      - survey.html
    - routing
      - apiRoutes.js
      - htmlRoutes.js
  - node_modules
  - package.json
  - server.js
