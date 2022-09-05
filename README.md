# Blitt

![Blitt](https://user-images.githubusercontent.com/50238797/65367315-d7161d80-dc61-11e9-8f2d-9038afbe2a41.PNG)

Check out the full app here! https://blitt.herokuapp.com/blitt

## Objective

The app aims to ease users from the trouble of keeping record on how much they owe or owed on bills that are paid by themselves or others.

## Functions

- create and add new bill easily, with functions to automatically help user split the bill equally or user can input it manually for unequal splitting.
- create group with only people you associated with for different situations to better plan your financial.
- easily check how much you owe or how much others you through the group list or friend list page.
- calculations will be done whenver you settle the total amount with someone.
- a bar graph and line graph to show your past 30 days expenses, amount you borrowed or amount you lent, by category or daily expenses.

## Installation Instructions

1. Installs all the dependencies of the project using

```
npm install
```

2. Create the Postgres db for running on local

```
createdb DATABASE_NAME -U USERNAME
```

3. Creates the tables neccessary to run this project

```
psql -d DATABASE_NAME -U USERNAME -f tables.sql
```

4. Seed dummy data

```
psql -d DATABASE_NAME -U USERNAME -f seed.sql
```

## Technologies Used

- Front-end
- HTML, CSS, Javascript, ReactJS
- Backend
- NodeJS, ExpressJS
- Database
- PostgreSQL
- Others
- ChartJS, Cloudinary, QR code API
