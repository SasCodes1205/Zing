# Zing 🦇 
# 👥 The Team
# Sasindi Welagedara - Lead Architect & Full Stack Developer
# Navithma Mudalige - Associate Architect & AI/ML Engineer
> **Status:** 🚧 Work in Progress (Planning & Architecture Phase)

**Zing** is a niche dating application inspired by the concept of a "soulmate bond" from *Hotel Transylvania*. While most apps focus on superficial swiping, Zing is designed to match users based on **High-Fidelity Compatibility**: a composite of music, literature, cinema tastes, and core social/political beliefs.

![App Mockup](https://via.placeholder.com/800x400?text=App+Mockup+-+Dark+Mode+UI+with+Neon+Accents)

---

## 🎯 The Vision
Modern dating apps suffer from "choice overload" and superficial matching. **Zing** aims to return intentionality to the process by matching "Zest for Life" through shared cultural and moral DNA.

## 🧩 Core Features (Planned)

* **The Weighted Zing Algorithm:** A proprietary matching engine that calculates compatibility scores based on:
    * **Foundation (50%):** Political, social, and religious beliefs.
    * **Vibe (30%):** Music (Spotify integration), Movies, and TV Shows.
    * **Intellect (20%):** Literature and personal hobbies.
* **Taste Clusters:** Instead of a standard bio, users build a "Vault" of their favorite media and cultural touchstones.
* **Belief-Alignment Toggle:** Strictness filters for social issues (e.g., "Must share my views on Climate Change").
* **"The Spark" Chat:** AI-generated icebreakers based on specific shared niche interests (e.g., *"You both love 'Dune'—who is your favorite character?"*).

---

## 🏗️ Technical Architecture (MERN Stack)
To handle the complex matching logic and real-time nature of the app, the following stack was selected:

| Layer | Technology | Reason |
| :--- | :--- | :--- |
| **Frontend** | React Native | Cross-platform mobile deployment for iOS and Android. |
| **State** | Redux Toolkit | Managing global state for user "Vaults" and notifications. |
| **Backend** | Node.js / Express | Scalable handling of RESTful APIs and matching logic. |
| **Database** | MongoDB | Document-based storage ideal for diverse interest "clusters." |
| **Real-time** | Socket.io | Instant messaging and "Zing" alerts. |
| **Auth** | JWT / Firebase | Secure, encrypted user authentication. |

---

## 🗺️ Project Roadmap

- [x] **Phase 1: Research & Design** (Current)
    - [x] Concept validation and feature mapping.
    - [ ] Database Schema design and "Zing" Algorithm weighting.
    - [ ] High-Fidelity Figma Wireframes.
- [ ] **Phase 2: MVP Development**
    - [ ] Implementation of User Authentication (JWT).
    - [ ] Building "The Vault" interest selection UI.
    - [ ] Basic Keyword-based Matching Engine.
- [ ] **Phase 3: Advanced Matching & Social**
    - [ ] Spotify & Media API integrations.
    - [ ] Full implementation of the Weighted Algorithm.
    - [ ] Real-time Chat via WebSockets.
- [ ] **Phase 4: Beta Testing**
    - [ ] Deployment to TestFlight/Expo for closed-group testing.

---

## 🛠️ Installation (For Developers)
*Note: The codebase is currently in the initial setup phase.*

