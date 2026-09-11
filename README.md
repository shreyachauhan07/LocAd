# LocAd

### Local Business × Local Influencer Collaboration Platform

A full-stack product prototype for connecting local businesses with local influencers through role-based workflows, campaign management and cloud-backed application data.

## Highlights

- Role-based business and influencer experiences
- Firebase Authentication with protected routes
- Campaign / advertisement management flows
- Separate dashboards for different user roles
- Firestore-backed application data and security rules
- Responsive React + TypeScript + Tailwind UI
- Modular page/component structure using Vite

## Tech stack

**React · TypeScript · Vite · Firebase · Firestore · Tailwind CSS · Zustand**

## Application flow

```text
User
 │
 ├── Business ──► Dashboard ──► Create/manage campaigns
 │                              │
 │                              └──► Discover influencers
 │
 └── Influencer ─► Dashboard ──► Discover opportunities
                                │
                                └──► Manage profile / support
```

## Engineering notes

The application uses Firebase Authentication for identity and Firestore for cloud data. Firestore security rules restrict writes based on authenticated ownership, while React Router protected routes control access to authenticated application areas.

The project demonstrates practical frontend/full-stack product engineering: translating product flows into typed React components, integrating cloud services, handling authenticated state and organizing role-specific application experiences.

## Project structure

The application source is contained in `LocAD-main/`.

```text
LocAD-main/
├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── services/
│   └── App.tsx
├── firestore.rules
├── firestore.indexes.json
├── package.json
└── vite.config.ts
```

## Project context

A portfolio project demonstrating product-focused software engineering, authentication, cloud data integration and responsive web application development.
