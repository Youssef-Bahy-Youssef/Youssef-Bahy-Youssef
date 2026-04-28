<div align="center">

```
██████╗  █████╗  ██████╗██╗  ██╗███████╗███╗   ██╗██████╗
██╔══██╗██╔══██╗██╔════╝██║ ██╔╝██╔════╝████╗  ██║██╔══██╗
██████╔╝███████║██║     █████╔╝ █████╗  ██╔██╗ ██║██║  ██║
██╔══██╗██╔══██║██║     ██╔═██╗ ██╔══╝  ██║╚██╗██║██║  ██║
██████╔╝██║  ██║╚██████╗██║  ██╗███████╗██║ ╚████║██████╔╝
╚═════╝ ╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═══╝╚═════╝
```

# Hey there, I'm Youssef Bahy 👋

**Backend Engineer** · Node.js & Go · Distributed Systems · Microservices

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/youssef-bahy-2062a224a/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:youssefbahy2022@gmail.com)
[![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/Y.Bahy)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Youssef-Bahy-Youssef)

</div>

---

## 🧠 About Me

```go
type Engineer struct {
    Name        string
    Role        string
    University  string
    Passions    []string
    Learning    []string
    SolvedProblems int
}

me := Engineer{
    Name:     "Youssef Bahy Youssef",
    Role:     "Backend Engineer",
    University: "Cairo University — Computer Engineering (GPA: 3.5)",
    Passions: []string{
        "Distributed Systems",
        "Microservices Architecture",
        "Go Concurrency Patterns",
        "System Design",
        "Clean & Scalable Code",
    },
    Learning:    []string{"Advanced Networking", "Advanced Databases", "Domain-Driven Design"},
    SolvedProblems: 900,
}
```

---

## 🚀 Featured Projects

### 🗄️ [Distributed File System](https://github.com/Youssef-Bahy-Youssef/distributed-file-system) &nbsp;`Go` `gRPC` `Raw TCP` `Protobuf`

> Production-grade DFS with automatic 3× replication, parallel chunked downloads, and heartbeat-based fault detection.

- **Control plane** via **gRPC** (metadata, heartbeats, replication coordination) · **Data plane** via **Raw TCP** (zero serialization overhead)
- Generic context-aware **Worker Pool** for bounded-concurrency TCP handling
- `sync.Map` fence prevents duplicate in-flight `(file, source, dest)` replication
- Full **graceful shutdown** on `SIGINT`/`SIGTERM` across all goroutines and servers
- Replication loop restores missing replicas to **3 copies within 10 seconds**

---

### 🎟️ [Ticketing Application](https://github.com/Youssef-Bahy-Youssef/ticketing) &nbsp;`TypeScript` `Node.js` `NATS` `Kubernetes`

> Full microservices system: Auth · Tickets · Orders · Payments — event-driven via NATS streaming.

- Deployed on **Kubernetes** with Docker containers; CI/CD via **GitHub Actions**
- Event-driven architecture with exactly-once delivery semantics via NATS

---

### 💬 [Chat Application](https://github.com/Youssef-Bahy-Youssef/chatApp) &nbsp;`Node.js` `Socket.IO` `MongoDB`

> Real-time chat backend with JWT auth, Socket.IO, RESTful APIs, and Mongoose ODM.

---

### ⚙️ [MIPS Pipelined Processor](https://github.com/Youssef-Bahy-Youssef/MIPS-Pipelined-Processor) &nbsp;`VHDL`

> 5-stage pipeline (Fetch → Decode → Execute → Memory → Write-back) with hazard detection and data forwarding.

---

### 🌿 [Natours](https://github.com/Youssef-Bahy-Youssef/Natours) &nbsp;`Node.js` `Express` `MongoDB` &nbsp;·&nbsp;
### 🖼️ [Image Compression System](https://github.com/Youssef-Bahy-Youssef/ImageProcessingProject) &nbsp;`Python`

---

## 💻 Tech Stack

### Languages
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

### Backend & Frameworks
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)

### Databases
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

### DevOps & Tools
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

---

## 🏗️ Architecture & Design Knowledge

| Domain | Topics |
|---|---|
| **Software Architecture** | 3-Tier Architecture · Clean Architecture · Microservices |
| **Domain-Driven Design** | Bounded Contexts · Aggregates · Ubiquitous Language |
| **System Design** | Scalability · Load Balancing · Caching · CAP Theorem |
| **Distributed Systems** | Replication · Fault Tolerance · Event-Driven Architecture |
| **Go Concurrency** | Goroutines · Channels · `sync` primitives · Worker Pools · Context cancellation |
| **Design Patterns** | Gang of Four Patterns · SOLID Principles · Low-Level Design |

---

## 📜 Certifications & Courses

| Course | Platform | Year |
|---|---|---|
| [Understanding Node.js Core Concepts](https://www.udemy.com/course/understanding-nodejs-core-concepts/) | Udemy | 2026 |
| [Microservices with Node.js and React](https://www.udemy.com/course/microservices-with-node-js-and-react/) | Udemy | Dec 2024 |
| [Node.js, Express, MongoDB & More: The Complete Bootcamp](https://www.udemy.com/course/nodejs-express-mongodb-bootcamp/) | Udemy | Aug 2024 |

---

## 📚 Currently Reading

- 📖 **Designing Data-Intensive Applications** — *Martin Kleppmann* (Chapter 7 / in progress)
- ✅ **Head First Design Patterns** — *Freeman & Robson* (completed)
- ✅ **Head First Object-Oriented Analysis and Design** (completed)

---

### ✍️ Dev Quote of the Day

<div align="center">

![Dev Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

</div>

---

<div align="center">

**🧩 900+ problems solved on competitive programming judges**

[![Profile Views](https://codeforces.com/profile/Y.Bahy)](https://codeforces.com/profile/Y.Bahy)

*Cairo, Egypt 🇪🇬 · Open to opportunities*

</div>
