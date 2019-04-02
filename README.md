# Scaffold Application

Create Rails App Using CLI 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

* Ruby version

  - Ruby-2.6.1

* Rails vesrion

  - Rails-4.2.5 

### Installing

A step by step series of examples that tell you how to get a development env running

- clone this repository

```
git clone https://github.com/DeepaDhiman/Scaffold_Application.git
```

- Move to application folder after repository clone completed

```
cd Scaffold_Application
```

- Inatall bundle to install the application dependencey

```
bundle install
```

- Rename the *config/secrets.example.yml* to *scerets.yml* and update the required informarion in *secrets.yml*

## Database Configuration

*sqlite3* used as database for this application.

- Run migration to create database and tables 

```
rails db:migrate
```

- check the *db/schema.rb* after migration completed successfully
- Run *db/seed.rb* file to create sample data for application

```
rails db:seed
```
## Running Application

- Start rails server

> Make sure you are in the application folder

```
rails s
```

- Check the application on browser, open the any browser of your choice and hit the following in the browser url

> Make sure server listen on port 3000

```
localhost:3000
```
## Author

* **Deepa Dhiman** - [GitHub profile](https://github.com/DeepaDhiman)
