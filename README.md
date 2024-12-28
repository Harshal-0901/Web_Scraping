# selenium-twitter-scraper

## Setup

1. Install dependencies

```bash
pip install -r requirements.txt
```

## Authentication Options

### Using Environment Variable

1. Rename `.env.example` to `.env`.

2. Open `.env` and update environment variables

```bash
TWITTER_USERNAME=# Your Twitter Handle (e.g. @username)
TWITTER_USERNAME=# Your Twitter Username
TWITTER_PASSWORD=# Your Twitter Password
```

### Authentication in Terminal

- Add a `username` and `password` to the command line.

```bash
python scraper --user=@elonmusk --password=password123
```

### No Authentication Provided

- If you didn't specify a username and password, the program will
  ask you to enter a username and password.

```bash
Twitter Username: @username
Password: password123
```

---

**_Authentication Sequence Priority_**

```bash
1. Authentication provided in terminal.
2. Authentication provided in environment variables.
```

