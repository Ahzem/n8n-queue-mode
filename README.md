<h1 align="center">Build and Test n8n Workflows Like a Pro 🚀</h1>

<p align="center">A step-by-step local development setup for n8n with Queue Mode, Docker, PostgreSQL, and Redis.  
Easily scale and test your automations like a real developer!</p>

<div align="center">
<img align="center" src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*ZOM3RSqFE_ECIysFCwnILA.jpeg"></img>
</div>

---

## 📖 About

This repository contains everything you need to get started with a local n8n development environment using Docker Compose.  
You’ll find sample `.env` and `docker-compose.yml` files, plus a handy guide to help you set up, test, and scale your workflows.

- **Read the full tutorial on Medium:** [Build and Test n8n Workflows Like a Pro](https://medium.com/@ahzem/build-and-test-n8n-workflows-like-a-pro-complete-docker-setup-with-queue-mode-21d3f972b6d3)

## 🗂️ Project Structure

```
n8n-queue-mode/
├── n8n-data/               # Persistent n8n data
├── .env.sample             # Sample environment variables
├── docker-compose.yml      # Docker Compose config
└── README.md               # This file
```

---

## 🚀 Quick Start

1. **Clone this repo**
2. Copy `.env.sample` to `.env` and update secrets
3. Run:  
   ```
   docker-compose up -d
   ```
4. Visit [http://localhost:5678](http://localhost:5678) and log in

For detailed setup and explanations, [read the Medium article](https://medium.com/@ahzem/build-and-test-n8n-workflows-like-a-pro-complete-docker-setup-with-queue-mode-21d3f972b6d3).


## 📝 Files Included

- **.env.sample**  
  Sample environment variables for n8n, PostgreSQL, and Redis.

- **docker-compose.yml**  
  Pre-configured for queue mode, with worker, PostgreSQL, and Redis.


## 🙋‍♂️ Author

**Written by Ahzem**  
Trainee Software Engineer @ Efito


## 📄 License

MIT
