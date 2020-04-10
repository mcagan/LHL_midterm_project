# Schoodle Project

The schoodle project was a simple and multipage Doodle app clone.

This app was built upon as a mock to practice our HTML, CSS, JS, jQuery and AJAX front-end skills, as well as Node, Express, and Postgresql back-end skills.

## Getting Started

1. Create the `.env` by using `.env.example` as a reference: `cp .env.example .env`
2. Update the .env file with your correct local information

- username: `labber`
- password: `labber`
- database: `midterm`

3. Install dependencies: `npm i`
4. Fix to binaries for sass: `npm rebuild node-sass`
5. Reset database: `npm run db:reset`

- Check the db folder to see what gets created and seeded in the SDB

7. Run the server: `npm run local`

- Note: nodemon is used, so you should not have to restart your server

8. Visit `http://localhost:8080/`

## Warnings & Tips

- Do not edit the `layout.css` file directly, it is auto-generated by `layout.scss`
- Split database schema (table definitions) and seeds (inserts) into separate files, one per table. See `db` folder for pre-populated examples.
- Use the `npm run db:reset` command each time there is a change to the database schema or seeds.
  - It runs through each of the files, in order, and executes them against the database.
  - Note: you will lose all newly created (test) data each time this is run, since the schema files will tend to `DROP` the tables and recreate them.

## Dependencies

- Node 10.x or above
- NPM 5.x or above
- PG 6.x
- body-parser
- chalk
- debug-log
- dotenv
- ejs
- express
- moment-timezone
- morgan
- node-sass-middleware

## Screenshots of app

!["Homepage landing"](https://github.com/mcagan/LHL_midterm_project/blob/master/public/docs/Homepage%20landing.png?raw=true)
!["Homepage body"](https://github.com/mcagan/LHL_midterm_project/blob/master/public/docs/Homepage%20body.png?raw=true)
!["Create event page 1"](https://github.com/mcagan/LHL_midterm_project/blob/master/public/docs/Create%20event%20page.png?raw=true)
!["Create event page 2"](https://github.com/mcagan/LHL_midterm_project/blob/master/public/docs/Create%20event%20page%202.png?raw=true)
!["Event detail page 1"](https://github.com/mcagan/LHL_midterm_project/blob/master/public/docs/Event%20detail%20page%201.png?raw=true)
!["Thank you page"](https://github.com/mcagan/LHL_midterm_project/blob/master/public/docs/Thank%20you%20page.png?raw=true)
