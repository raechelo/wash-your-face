## Wash Your Face!

> ![NOTE] This application is still in progress

Wash Your Face is an application that allows users to search for their favorite facial scrubs and check the ingredients for microplastics. It also allows for users to upload facial scrubs by name, and upon save, searches popular store inventory for the scrub to check for ingredients.

Wash Your Face was built as an attempt to refresh my knowledge and use of Node.js, particularly around writing and developing APIs, but also to refresh my knowledge of database creation and seeding. The backend repository can be found [here](https://github.com/raechelo/wash-your-face-be).

### How it works
When a user clicks to search, webscrapers run on Amazon and Walmart inventories to check for the scrub, and then subsequently check the scrub's ingredients. If any of the popular microplastics are included in the list, the user is alerted and the results are saved in the application's database for the next user.

### What it's built with
The front end is built with Vue.js, and the backend is built in Node.js with a Postgresql database, which was seeded using Knex.
