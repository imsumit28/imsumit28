# Sumit Kumar
### Full Stack Developer · Backend & Real-Time Systems

 India  
 [LinkedIn](https://www.linkedin.com/in/imsumit45/)  
 ersumitkumar45@gmail.com  

---

## About

Full Stack Developer focused on building scalable web applications with strong backend architecture, real-time systems, and production-oriented engineering practices.

### Current Focus
- Data Structures & Algorithms
- System Design fundamentals
- Distributed systems concepts
- Scalable backend architectures

---

# Featured Projects

## [Curlix](https://github.com/imsumit28/Curlix) — Scalable URL Shortener Platform

**Live:** https://curlix.vercel.app/

Engineering-focused URL shortening platform built for production. Anonymous link ownership with no accounts, sub-10ms redirects via a Redis-first hot path, and async analytics through a BullMQ queue.

### Core Engineering Features
- Redis-first redirect architecture for ultra-fast lookups
- Queue-based analytics processing using BullMQ
- Async event handling for non-blocking redirects
- Anonymous ownership system via bearer tokens — no accounts, no sessions
- Rate limiting, abuse prevention, and SSRF-safe URL validation
- 100% free infrastructure stack

### Tech Stack
`React` · `Node.js` · `Express` · `PostgreSQL` · `Supabase` · `Redis` · `BullMQ` · `Upstash` · `Vercel` · `Render`

---

## [CollabDocs](https://github.com/imsumit28/collabdocs) — Real-Time Collaborative Editor

**Live:** https://collabdocs2026.vercel.app

### Engineering Highlights
- Built real-time collaborative editing using Socket.io
- Implemented multi-user synchronization logic
- Optimized editor performance during concurrent updates
- Designed scalable WebSocket communication flow

### Tech Stack
`Next.js` · `TypeScript` · `Tailwind CSS` · `Node.js` · `Socket.io` · `MongoDB` . `Tiptap` . `Mammoth` . `Yjs (CRDT library) + Y-ProseEditor` . `Redis` . `JWT,OAuth2.0` . `CORS` . `ESlint`

---

## [NotifyX](https://github.com/imsumit28/NotifyX) — Notification System Backend

**Live:** https://notifyx-sumit.vercel.app/

### Engineering Highlights
- Distributed producer-worker architecture with BullMQ and Redis as the sole inter-process bridge — server and worker run as fully independent Node.js services
- Real-time notification delivery via Socket.io with offline sync: undelivered notifications are persisted and pushed on reconnect
- Two-layer idempotency: Redis SETNX at the API boundary and a MongoDB sparse unique index in the worker to prevent duplicate deliveries
- JWT authentication on all REST routes and Socket.io handshakes, with role-based access enforced at the middleware level

### Tech Stack
`Node.js` · `Express` · `React` · `MongoDB` · `JWT` · `Socket.io` · `BullMQ` · `BullBoard` · `Redis`

---

## [DevConnect](https://github.com/imsumit28/devconnect) — Developer Social Platform

**Live:** https://devconnect2026.vercel.app

### Engineering Highlights
- Implemented secure authentication with 2FA, OAuth (Google/GitHub), and JWT-based session management
- Built comprehensive REST APIs for posts, messaging, notifications, and real-time analytics
- Integrated WebSocket (Socket.io) for real-time notifications and live collaboration features
- Architected modular backend with domain-driven routing, middleware pipeline, and Mongoose ODM integration

### Tech Stack
`React` · `Node.js` · `Express` · `MongoDB` · `Socket.io` · `JWT` · `Bcryptjs` · `OAuth` · `2FA (TOTP)` · `CORS` · `node-cron` · `Cloudinary` · `Multer` · `qrcode` · `Helmet` · `ESLint`

---

# Technical Skills

### Frontend
`React` · `Next.js` · `TypeScript` · `Tailwind CSS` · `JavaScript` · `CSS`

### Backend
`Node.js` · `Express.js` · `REST APIs` · `WebSockets (Socket.io)` · `JWT Authentication`

### Databases & Caching
`MongoDB` · `Mongoose` · `PostgreSQL` · `Redis` · `Supabase`

### Advanced Backend Patterns
`BullMQ` · `Distributed Systems` · `Queue-based Architectures` · `Real-time Event Processing` · `Idempotency Patterns`

### Security & Authentication
`JWT` · `Bcryptjs` · `OAuth (Google/GitHub)` · `2FA/TOTP` · `Helmet` · `CORS` · `Rate Limiting`

### Tools & Infrastructure
`Git` · `Node-cron` · `Cloudinary` · `Multer` · `Vercel` · `Render` · `Upstash` · `Railway` · `Postman` · `ESLint`

---

# Education

### B.Tech in Computer Science  
Vellore Institute of Technology *(2024 – 2028)*

### Certifications & Courses
- Applied Machine Learning in Python (Coursera) - University Of Michigan *(2025)*

---

# Currently Learning

- Data Structures & Algorithms
- System Design and distributed systems
- Low-level design patterns
- Performance engineering and scalability

---

## Get in Touch

Have a project idea or want to collaborate? Feel free to reach out!

- 📧 **Email:** ersumitkumar45@gmail.com
- 🔗 **LinkedIn:** [linkedin.com/in/imsumit45](https://www.linkedin.com/in/imsumit45/)
- 💻 **GitHub:** [github.com/imsumit28](https://github.com/imsumit28)
