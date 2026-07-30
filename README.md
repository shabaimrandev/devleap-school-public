# DevLeap Tech Institute Website

The official website for DevLeap Tech Institute, a tech training school in Abuja offering hands-on courses in web development, programming languages, and digital skills.

## Features

- **Public marketing pages** — Home, About, Courses, Blog, Careers, and Contact, all built on a unified design system.
- **Course catalog** — Lists available programs (Python, Java & OOP, Databases with PHP/SQL, Web Development, Full-Stack Software Engineering, Digital Skills) with duration and pricing.
- **Application flow** — Multi-field application form capturing course interest, experience level, preferred schedule/class type, age range, and referral source.
- **Secure account creation & login** — Users sign up with email and password; on registration, a confirmation email is sent to verify ownership of the email address before the account is activated. This prevents fake or mistyped emails from creating active accounts and keeps unverified users out of the student portal.
- **Student Portal** — Authenticated area for enrolled students, gated behind login.
- **Contact & lead forms** — Reach-out forms across Home, About, and Contact pages, protected by reCAPTCHA.
- **Team & social proof** — Meet-the-team section, testimonials, and stats to build trust with prospective students.

## Tech Stack

- Next.js + TypeScript
- Prisma (database ORM)
- NextAuth (authentication, email verification flow)
- Resend (transactional/verification emails)
- Paystack (payments)
- Cloudinary (authenticated dashboard avatar uploads)
- Postgres

## Status

Public pages, course catalog, and application flow are live. Account creation with email/password and email-verification-before-activation is implemented; student portal features are being expanded.
