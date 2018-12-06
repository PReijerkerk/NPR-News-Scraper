# NPR News Scraper

This app allows users to view the latest NPR News articles, save any they would like for further reading, and comment on saved articles. The last twenty-four articles are displayed complete with headlines, an article summary, and the link to the original article. This app uses *Node.JS*/*Express* for the backend & routing; *MongoDB*/*Mongoose* for the database and models; *Express-Handlebars* for the layout and view; and *Cheerio*/*Axios* for scraping the data from www.npr.org

[Live Demo](https://tranquil-stream-58343.herokuapp.com/articles)

## Getting Started

The following will get you up and running with your own personal copy of the NPR-News-Scraper. Please make sure you have copies of [Node.js](https://nodejs.org/en/) and [MongoDB](https://www.mongodb.com/) installed locally.

1. Install dependencies
2. In your CLI, enter **mongod**
3. In a new CLI window, go to root of the cloned directory and enter **npm start**
4. In browser, navigate to **http://localhost:3000**

### Dependencies

You will need to npm install the following node modules:

1. [Express](https://www.npmjs.com/package/express)
2. [Express-handlebars](https://www.npmjs.com/package/express-handlebars)
3. [Mongoose](https://www.npmjs.com/package/mongoose)
4. [Cheerio](https://www.npmjs.com/package/cheerio)
5. [Axios](https://www.npmjs.com/package/axios)
6. [Morgan](https://www.npmjs.com/package/morgan)

These dependencies are currently included within the [package.json] Simply run the following in the root of your directory:

```
npm install
```

