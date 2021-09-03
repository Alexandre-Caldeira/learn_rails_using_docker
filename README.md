# learning_rails_in_docker

This is literally a very simple implementation of rails on docker following a recipe from [THIS AWESOME REPO](https://github.com/alpinelab/docker-ruby-dev). 

## 🚀 Getting started

### 1. Dependencies:

You need to have: 

✔️ docker

✔️ docker-compose

installed and its recommended that you know how to use them.

### 2. Clone the repo:

```
git clone https://github.com/Alexandre-Caldeira/learning_rails_in_docker.git
```

### 3. Compose up and start working:

- Get inside the repo folder:

```
cd learning_rails_in_docker
```

- Build the app:

```
docker-compose up --build app
```

- Run it:

```
docker-compose up app
```

- Where's the website?

- "Home" page, autogenerated, copy-paste this on your browser:

```
localhost:5000
```

- Another one I created real fast to validate the project was working:
```
localhost:5000/articles
```

Based on [this beginner's tutorial (rubyonrails)](https://guides.rubyonrails.org/getting_started.html#say-hello-rails).

# ⏭️ Next step:
- Making it work with webpack following the original dev's recipes together with a PostgresSQL database container
