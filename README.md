Production-ready corporate website and contact handling system developed for Troy Technologies.
This repository is intended for technical overview and demonstration purposes only.

# Troy Technologies – Corporate Website & Contact Infrastructure

> Production-ready corporate website and contact handling system developed for Troy Technologies.
This repository is intended for technical overview and demonstration purposes only.

---

## Overview

This project provides a complete corporate web solution including:

- Static frontend (React + Vite)
- Backend contact API
- SMTP-based email system
- Security and anti-spam mechanisms

---

## Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Vite

### Backend
- Node.js
- Express.js
- Nodemailer
- Zod

### Infrastructure
- DirectNIC
- SMTP server

---

## Architecture

Client → React Frontend → /api/contact → Express Backend → SMTP → Email Inbox

---

## Key Features

- Responsive UI
- Contact form with backend processing
- Email delivery via SMTP
- Rate limiting & validation
- Production deployment

---

## Engineering Decisions

### SMTP instead of third-party services
- No dependency on external APIs
- Lower cost
- Full control

### Separate backend service
- Keeps credentials secure
- Enables validation and rate limiting

### Anti-spam system
- Rate limiting
- Honeypot field
- Input validation
