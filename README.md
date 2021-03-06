# Dilbertbot

A Daily Dilbert Comic Strip Bot for Slack

---

## Prerequisites

1. [brew](http://brew.sh)

  ```sh
  ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  ```

1. [node](http://nodejs.org/)

  ```sh
  brew install node
  ```

1. [n](https://www.npmjs.com/package/n)

  ```sh
  npm install n -g
  ```

---

## Setup

1. `git clone git@github.com:ilyakam/dilbertbot.git`
1. `cd dilbertbot`
1. `n 6.*`
1. `npm install`

---

## Workflow

* To run the app locally

  ```sh
  npm run dev
  ```

* To test

  ```sh
  npm run test
  ```

* To lint

  ```sh
  npm run lint
  ```

---

## Deploy

This bot can be deployed on different platforms. Simply follow the instructions below:

### [Zeit's Now](https://zeit.co/now)

  ```sh
  # Ensure you're inside the dilbertbot directory
  npm install now -g
  now deploy -e SLACK_WEBHOOK_URL=[your webhook URL]
  ```
