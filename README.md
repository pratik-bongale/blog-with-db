# Daily Journal Blog - with database
Daily journal to share your thoughts, ideas, and interesting reads.

## Getting Started
- The App is currently hosted on Heroku. For a quick peek visit [Daily Journal]().
- To build this project locally, follow steps given below.

### Prerequisites
- Node, npm
- MongoDB Atlas account(free account works)
  - Visit [getting started guide](https://docs.atlas.mongodb.com/getting-started/) for steps of setting up your free cluster in the cloud.

### Installing
Clone this repository. 
```bash
$ git clone https://github.com/pratik-bongale/blog-with-db.git
```

Change directory
```bash
$ cd blog-with-db
```

Install all dependencies
```
$ npm install
```

Rename ".env_sample" to ".env"
```
$ mv .env_sample .env
```

Modify ".env", replace the MongoDB connection string with your own generated in your MongoDB Atlas account.
```
MONGODB_CONN=mongodb+srv://username:password@cluster0-in9xt.mongodb.net/todolistDB
```

Run app locally
```
$ node app.js
```

## Learnings
- This project demonstrates how to:
  - Export functions/variables from a module
  - Import functions/variables into a module
  - Use Embedded Javasciprt(EJS) to define views
  - Render EJS views using expresJS
  - Reuse EJS views(Header/Footer) across all pages for consistency
  - Handle get and post requests from the backend nodeJs script
  - Use route(url) parameters to display different content on a page based on url

## Author
- **Pratik Bongale** - *Initial work* - [Daily Journal](https://github.com/pratik-bongale/blog-with-db.git)


## Acknowledgments
- [The App Brewary](https://www.appbrewery.co/p/web-development-course-resources/)
- [The Web Developer Bootcamp](https://www.udemy.com/course/the-web-developer-bootcamp/)
