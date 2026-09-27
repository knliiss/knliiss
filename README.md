<div align="center">

# Vitalii Lototskyi

### Software Engineer · Backend & Distributed Systems

I build backend-heavy products, distributed architectures, realtime systems and full-stack applications.

[![Telegram](https://img.shields.io/badge/Telegram-@knaliz-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/knaliz)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vitalii_Lototskyi-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vitalii-lototskyi-20aa25374/)
[![Email](https://img.shields.io/badge/Email-vitallot21%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:vitallot21@gmail.com)

</div>

---

## About

I focus on backend engineering and system architecture.

I enjoy building systems where the difficult part is not a single feature, but the interaction between service boundaries, messaging, authentication, realtime behavior, data consistency, deployment and maintainability.

Most of my work follows the whole lifecycle:

```text
architecture → backend → integrations → frontend → infrastructure → deployment → runtime debugging
```

My main active project is **Mnemos**.

---

# Mnemos

### Event-driven platform built around Kotlin, Spring and distributed services

**Mnemos** is the project I currently spend most of my development time on.

It has grown into a multi-service platform with independent domains for accounts, profiles, wallets, events, rewards, notifications, realtime communication, personalization, social features, moderation, payments, player data and Telegram integration.

Rather than growing as a single application, the system is structured around explicit service boundaries, shared contracts and reusable infrastructure.

### System structure

The backend currently contains dedicated services for:

```text
account            profile            wallet
event              reward             notification
realtime           personalization    social
moderation         payment            player-directory
telegram-bot       gateway
```

Shared platform components cover:

- Kafka-based messaging
- inbox / outbox processing
- inter-service contracts
- reusable security and web libraries
- Keycloak authentication
- realtime communication
- gateway routing
- common infrastructure shared across services

The user-facing web application is a React + TypeScript mini-app.

The Mnemos ecosystem also includes **Mnemos Collector** — a separate Rust client responsible for collecting and transmitting client-side data to the platform.

### Stack

**Backend:** Kotlin · Spring Boot · Spring Security  
**Messaging & realtime:** Kafka · WebSocket  
**Identity:** Keycloak  
**Data & infrastructure:** PostgreSQL · Redis · MinIO · Docker  
**Frontend:** React · TypeScript · Vite  
**Client tooling:** Rust

<p>
  <a href="https://github.com/knliiss/Mnemos"><strong>Explore Mnemos →</strong></a>
</p>

---

## Studium

### Full-stack Learning Management System

**Studium** is a microservice-oriented academic platform built around student, teacher and administrator workflows.

It covers authentication, academic structures, schedules, assignments, submissions, testing, grades, file storage, notifications, analytics, audit trails and Telegram integration.

The backend is split into domain-oriented Spring Boot services behind a common gateway. Kafka is used for asynchronous domain communication, PostgreSQL for persistence, Redis for supporting infrastructure and MinIO for object storage.

The frontend is a role-aware React + TypeScript application.

**Stack:** Java 21 · Spring Boot · Spring Cloud Gateway · Kafka · Redis · PostgreSQL · MinIO · React · TypeScript · Docker

<p>
  <a href="https://github.com/knliiss/Studium"><strong>Explore Studium →</strong></a>
</p>

---

## Technology

<table>
<tr>
<td valign="top">

### Backend

Kotlin  
Java  
Spring Boot  
Spring Security  
REST  
WebSocket

</td>
<td valign="top">

### Distributed systems

Kafka  
Redis  
Keycloak  
PostgreSQL  
MinIO  
Docker

</td>
<td valign="top">

### Frontend & tooling

React  
TypeScript  
Vite  
Rust  
Gradle  
GitHub Actions

</td>
</tr>
</table>

---

## Engineering interests

- distributed backend systems
- event-driven architecture
- service boundaries and communication
- realtime applications
- authentication and authorization
- reliability and data consistency
- production infrastructure
- architecture evolution and refactoring
- debugging real runtime behavior

I prefer developing a smaller number of systems deeply over collecting many small showcase projects.

---

<div align="center">

**Software Engineering · Lviv, Ukraine**

</div>
