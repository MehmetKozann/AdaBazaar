<p align="center">
  <img src="./screenshots/logo.png" width="110" alt="AdaBazaar Logo"/>
</p>

<h1 align="center">AdaBazaar</h1>

<p align="center">
  <b>A Cross-Platform Mobile & Web Marketplace Application</b>
</p>

<p align="center">
  <a href="https://reactnative.dev"><img src="https://img.shields.io/badge/React_Native-0.74+-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React Native"/></a>
  <a href="https://www.typescriptlang.org"><img src="https://img.shields.io/badge/TypeScript-5.0+-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/></a>
  <a href="https://nextjs.org"><img src="https://img.shields.io/badge/Next.js-14+-000000?style=flat-square&logo=next.js&logoColor=white" alt="Next.js"/></a>
  <a href="https://nestjs.com"><img src="https://img.shields.io/badge/NestJS-10+-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS"/></a>
  <a href="https://firebase.google.com"><img src="https://img.shields.io/badge/Firebase-Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firebase"/></a>
  <a href="https://supabase.com"><img src="https://img.shields.io/badge/Supabase-Storage-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase"/></a>
</p>

---

## Overview

**AdaBazaar** is a production-grade, multi-platform marketplace application engineered to connect buyers and sellers seamlessly. Built with high performance, scalability, and user experience at its core, AdaBazaar offers comprehensive classifieds management across mobile (iOS & Android) and web platforms.

The application features real-time synchronization, intelligent location filtering, multi-currency support, in-app buyer-seller price negotiations, and cloud media management.

---

## Core Features

- **Authentication & Security**: Secure user authentication powered by Firebase Auth, supporting phone verification, social sign-in, and role-based access control (User, Premium Seller, Admin).
- **Marketplace & Classifieds**: Multi-category support including Electronics, Vehicles, Real Estate, and Student essentials with dynamic multi-currency pricing (TRY, GBP, USD, EUR).
- **Real-Time Messaging & Negotiations**: Integrated buyer-seller chat system with real-time price offer submission, acceptance, and direct negotiation chips.
- **Regional & Category Filtering**: Granular location filtering across districts and cities with responsive category browsing.
- **Multilingual Support**: Built-in Turkish (TR) and English (EN) internationalization (`i18n`).
- **Push Notifications**: Real-time push notifications powered by Firebase Cloud Messaging (FCM) for message alerts, offer updates, and listing status changes.
- **Cloud Infrastructure**: Hybrid cloud architecture leveraging Firebase Firestore for real-time NoSQL data synchronization and Supabase CDN for fast media storage.

---

## Tech Stack

| Domain | Technology | Description |
| :--- | :--- | :--- |
| **Mobile App** | React Native, TypeScript, Redux Toolkit, Expo | Cross-platform mobile client with native performance |
| **Web App** | Next.js (App Router), TailwindCSS, i18n | Responsive web client with SSR and SEO optimization |
| **Backend API** | NestJS, Node.js, Firebase Admin SDK | Enterprise REST API and business logic orchestration |
| **Database** | Firebase Firestore | NoSQL document database with real-time listeners |
| **Storage** | Supabase Storage | Object storage and global CDN delivery for media assets |
| **Push Service** | Firebase Cloud Messaging (FCM) | Reliable cross-platform messaging service |

---

## Application Showcase

<table align="center">
  <tr>
    <td align="center" width="33%">
      <img src="./screenshots/1.png" width="100%" alt="Authentication"/>
      <br/>
      <sub><b>01. Authentication & Guest Entry</b></sub>
    </td>
    <td align="center" width="33%">
      <img src="./screenshots/2.png" width="100%" alt="Home Feed"/>
      <br/>
      <sub><b>02. Home Feed & Categories</b></sub>
    </td>
    <td align="center" width="33%">
      <img src="./screenshots/3.png" width="100%" alt="Product Details"/>
      <br/>
      <sub><b>03. Product Details & Offers</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <img src="./screenshots/4.png" width="100%" alt="Real-Time Chat"/>
      <br/>
      <sub><b>04. Real-Time Chat & Offers</b></sub>
    </td>
    <td align="center" width="33%">
      <img src="./screenshots/5.png" width="100%" alt="Add Listing"/>
      <br/>
      <sub><b>05. Create New Listing</b></sub>
    </td>
    <td align="center" width="33%">
      <img src="./screenshots/6.png" width="100%" alt="User Profile"/>
      <br/>
      <sub><b>06. User Profile & Settings</b></sub>
    </td>
  </tr>
</table>

---

## Availability

- **App Store**: *(Private Distribution / Production)*
- **Google Play**: *(Private Distribution / Production)*

---

## Repository Topics

`react-native` • `typescript` • `firebase` • `ios` • `android` • `mobile` • `marketplace` • `nextjs` • `nestjs` • `expo` • `supabase`

---

## Source Code Notice

> [!NOTE]
> The source code is private because this is a production application.  
> This repository serves as a technical showcase of the application architecture, UI design, and feature set.

---

## License

This repository is licensed under the [MIT License](./LICENSE).
