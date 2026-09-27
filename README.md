# DevLeap Tech Institute Website

The official website for DevLeap Tech Institute, a tech training school in Abuja offering hands-on courses in web development, programming languages, and digital skills.

## Features

- **Public marketing pages** — Home, About, Courses, Blog, Careers, and Contact, all built on a unified design system.
- **Course catalog** — Lists available programs (Python, Java & OOP, Databases with PHP/SQL, Web Development, Full-Stack Software Engineering) with duration and pricing.
- **Application flow** — Multi-field application form capturing course interest, experience level, preferred schedule/class type, age range, and referral source.
- **Secure account creation & login** — Email/password signup with email verification before account activation, preventing fake or mistyped emails from creating active accounts.
- **Role-based dashboards** — Permission-scoped Admin, Teacher, and Student dashboards with secured routing, each gated behind authentication and role checks.
- **Contact & lead forms** — Reach-out forms across Home, About, and Contact pages, protected by reCAPTCHA.
- **Team & social proof** — Meet-the-team section, testimonials, and stats to build trust with prospective students.

## Tech Stack

- Next.js + TypeScript
- PostgreSQL
- Prisma (database ORM)
- NextAuth (authentication, email verification flow)
- Resend (transactional/verification emails)
- Paystack (payments)
- Cloudinary (authenticated dashboard avatar uploads)

## Status

Public pages, course catalog, application flow, and account creation with email verification are live. Admin, Teacher, and Student dashboards are built and in production use, with role-based access control across all three.
