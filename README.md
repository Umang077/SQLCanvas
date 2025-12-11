SQLCanvas

This project is a dynamic React-based web application featuring two SQL editors and a home page. It enables users to upload CSV files, run SQL queries directly in the browser, and analyze the resulting output tables.

🔗 Live Demo:
https://atlan-assignment-sql-runner-007-epf8fifpi.vercel.app/

🚀 Features
Editor 1: (CSV Upload + Auto Query Generator)

Upload any CSV file to generate a dynamic dataset.

Automatically generates SQL queries based on the uploaded schema.

Displays output tables for selected queries.

Fully interactive and supports multiple data types.

Editor 2: (Manual SQL Runner)

Includes built-in sample SQL queries.

Allows typing custom SQL queries.

Displays query output mapped to sample Northwind dataset.

Includes extra features:

Query history tracking

Delete past queries

Export query result as CSV

Sample Data

Demo data is sourced from the Northwind dataset:
https://github.com/graphql-compose/graphql-compose-examples/tree/master/examples/northwind/data/csv

🧰 Tech Stack
Frontend

React JS - For UI components and dynamic rendering.

Vite - For fast development server and optimized builds.

CSS - For styling and responsive layout.

📂 Project Structure
/src
  /components
  /pages
  /utils
  /data

📦 Installation
git clone <repo-url>
cd <project-folder>
npm install
npm run dev

✨ Future Enhancements

Support for JOIN queries across multiple user-uploaded CSVs.

Data visualization (charts/graphs) for query results.

Save projects locally using IndexedDB.
