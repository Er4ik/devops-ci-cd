# Devops CI/CD

## Installation

- Clone the repository

```bash
git clone https://github.com/Er4ik/dockerising_nodejs_app.git
```

## Usage

- If you have node and npm on your pc:

```bash
npm run start:js
```

- If you do not have node and npm on your pc:

```bash
cd devops-ci-cd
docker build -f Dockerfile -t lab3:01 .
docker run --rm -it -p 5001:3000 lab3:01
```

App running on Port 80
