#### Install PostgreSQL on MacOS

```bash
brew install postgresql
brew services start postgresql
```

#### Test local server

```bash
heroku local web --port 5001
```

#### Deploy to Heroku

```bash
git push heroku main
```
