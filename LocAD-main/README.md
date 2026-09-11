# LocAd

### Local business × local influencer collaboration platform

LocAd is a full-stack web application designed to help local businesses create advertising campaigns and connect with relevant community influencers.

## What it demonstrates

- **Role-based product flows** for businesses and influencers
- **Authentication and protected routes** using Firebase Authentication
- **Campaign management** for creating and viewing advertisements
- **Separate dashboards** for business and influencer workflows
- **Cloud data integration** with Firebase Firestore
- **Responsive UI** built with React, TypeScript and Tailwind CSS
- **Modular frontend architecture** with reusable components, hooks and page-level features

## Tech Stack

- **Frontend:** React, TypeScript, Vite, Tailwind CSS
- **Routing:** React Router
- **State:** Zustand
- **Backend / Cloud:** Firebase Authentication, Firestore
- **Tooling:** ESLint, PostCSS

## Application Flow

```text
                    ┌──────────────────┐
                    │      LocAd       │
                    └────────┬─────────┘
                             │
                ┌────────────┴────────────┐
                │                         │
          Business User             Influencer
                │                         │
         Authentication            Authentication
                │                         │
          Business Dashboard       Influencer Dashboard
                │                         │
         Create / manage ads       Discover available ads
                │                         │
                └────────────┬────────────┘
                             │
                     Firebase / Firestore
```

## Engineering Highlights

The application uses a component-based React architecture with protected routes for authenticated workflows. Authentication state is synchronized with Firebase and shared through application state, while reusable dashboard components separate business and influencer functionality.

The repository also includes Firestore configuration and security rules, making the project more representative of a real application than a purely static frontend.

## Project Structure

```text
LocAD-main/
├── src/
│   ├── components/
│   ├── hooks/
│   ├── lib/
│   ├── pages/
│   └── store/
├── firestore.indexes.json
├── firestore.rules
├── package.json
└── vite.config.ts
```

## Note

This project is presented as a portfolio project demonstrating full-stack web application development, authentication, cloud data integration and product-focused frontend engineering.
