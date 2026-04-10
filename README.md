# vlad

## 📝 Description

A small pet-project (~1.5h session) for practicing and showcasing software development decisions.

The project is not intended to be a polished product.
It exists to demonstrate learning, decision-making, and clean engineering rather than feature richness or visual design.

> Important note: If commits are sparse then I'm likely focused on another project.

---

## 🎯 Learning-First Philosophy

This project follows a strict rule:

> **Every feature must serve learning, not novelty or polish.**

### Hard Scope Lock

#### Allowed features:

- Authentication (register/login)
- CRUD habits
- Daily checkmark
- Weekly and monthly summary

#### Forbidden features:

- Dark mode
- Animations
- Notifications
- Mobile-first polish
- AI suggestions
- Gamification

> If it is not teaching a **core skills**, then it's not necessary.

## 🛠️ Tech Stack (`v1-structured` branch)

- HTML / CSS (SCSS)
- PHP (OOP, MVC)
- MySQL (PDO)
- Git (GitHub)

## 🚀 Roadmap

- v1 Structured PHP with MVC, PDO, OOP, clean commits
- v2 Basic CSS styling with SCSS
- v3 Improved styling with Tailwind CSS
- v4 Laravel integration

## 🏗️ Structure

```
project/
├── public/          - web root
├── src/             - application logic
```

## 🧩 Usage

Clone the repository (with Git) and use Docker Compose to build and run containers:

```bash
docker compose up --build
```

- Run detached

```bash
docker compose up -d
```

- Or run specific profile (where in this example php84 is created profile name):

```bash
docker compose --profile php84 up
```

> After running Docker, you should be able to access:
>
> - https://localhost:8881
> - https://localhost:8880

- To stop Docker containers run:

```bash
Ctrl+C
```

## ⏳ Status

🚧 In active development
