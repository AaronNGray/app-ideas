# app-ideas

## Setting up PostgreSQL
```
DATABASE_URL=postgres://ideas:ideas@localhost/ideas
```

```
sudo -u postgres psql
postgres=# create database ideas;
postgres=# create user ideas with encrypted password 'ideas';
postgres=# grant all privileges on database ideas to ideas;
```

## Installing

```npm install```

## Running

```npm start```

## Using

```http://localhost:3000/ideas```
