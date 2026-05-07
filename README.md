# Viktoria Ferstl

Hi! I’m Viky, a Software Engineer from Austria working mostly with TypeScript. I care about building accessible, thoughtful web experiences and enjoy supporting aspiring developers as they grow.

Outside of coding, I’m usually at a cozy café with friends, travelling, taking photos, boxing, or keeping my plants alive (most of the time).

This repository showcases selected software projects and engineering contributions, with a focus on full-stack architecture, integration work, and product-oriented delivery.

## Personal Projects

Fun little side projects I'm always working on – they're not perfect, but that's half the fun. ✨

| Project | Description | Year |
|---|---|---|
| [Vinyl Record Collection](#vinyl-record-collection) | Modern web app for a personal vinyl collection and wishlist with Contentful CMS and Discogs integration. | 2025 |
| [Photos Portfolio](#photos-portfolio) | Modern photo portfolio application that aggregates and displays photos from Pixelfed in a responsive gallery layout with RSS feed generation. | 2025 |

## Professional Projects

| Project | Description | Year | Company |
|---|---|---|---|
| [Business Flow](#business-flow) | | 2026 | Dynatrace |
| [Internal Sync / Time Tracking tool](#internal-sync--time-tracking-tool) | Full-stack Nx platform for time tracking and automated synchronization across Wrike, Personio, Runn and internal reporting. | 2025 | functn GmbH |
| [Birdlife Website](#birdlife-website) | Public-facing Contentful website for editorial content, wildlife stories and event presentation. | 2024 | functn GmbH |
| [HR Docs](#hr-docs) | HR documentation system with contract automation, e-signature workflows, and enterprise integrations. | 2024 | functn GmbH |
| [Energiegemeinschaften](#energiegemeinschaften) | Energy community platform built as a multi-app Nx monorepo with onboarding and sync services. | 2023 | functn GmbH |
| [Heylog Application](#heylog-application) | Logistics SaaS platform for delivery coordination, messaging and real-time order management. | 2023 | functn GmbH |

## Vinyl Record Collection

A web application showcasing my personal vinyl record collection, built with cutting-edge Next.js technologies and integrated with a headless CMS for dynamic content management.

**Live Demo:** https://records.viky.at/
**Repository:** https://github.com/fviktoria/vinyl-collection

### Tech Stack
- **Frontend Framework:** Next.js 16 (App Router) with Server Components
- **Language:** TypeScript
- **UI Library:** Chakra UI with Emotion
- **Styling:** Tailwind CSS
- **CMS:** Contentful (content management and rich media handling)
- **External API:** Discogs API (album metadata, covers, artist information)
- **Caching:** Upstash Redis (performance optimization)
- **Internationalization:** next-intl (multi-language support)
- **Animations:** Framer Motion
- **Components:** Splide (carousel/slider functionality)
- **Development Tools:** ESLint, TypeScript strict mode

### Key Features
- **Dual Collection Views:** Browse vinyl records in responsive grid and list layouts
- **Collection Management:** Organized display of owned albums with detailed metadata
- **Discogs Integration:** Automated album data retrieval (covers, artist information, release details) from Discogs API
- **Internationalization:** Full support for English and German language interfaces with locale-based routing
- **Responsive Design:** Fully responsive interface with adaptive layouts for all screen sizes
- **Album Cards:** Reusable component system with dynamic display variants (grid/list)

### Architecture Highlights
- **Server-Side Data Fetching:** Leverages Next.js server components for efficient content delivery
- **Content-Driven Layout:** Dynamic routing based on locale configuration with middleware
- **Type-Safe Content:** Generated TypeScript types from Contentful schema
- **Component Composition:** Modular component architecture with separated concerns (album cards, carousel, layout)
- **Environment Configuration:** Secure API key management with environment-based configuration
- **Custom Middleware:** Locale detection and routing middleware for seamless multi-language experience

This project demonstrates expertise in **modern React development**, **headless CMS integration**, **API data fetching**, **internationalization**, **performance optimization**, and **building production-ready applications** with Next.js.

## Photos Portfolio

A modern photo portfolio application that aggregates and displays photos from Pixelfed in a responsive gallery layout with RSS feed generation.

**Live Demo:** https://photos.viky.at
**Repository:** https://github.com/fviktoria/photos

### Tech Stack
- **Frontend Framework:** Next.js 15 (App Router, Turbopack)
- **Language:** TypeScript
- **Styling:** Tailwind CSS, CSS Modules
- **External APIs:** Pixelfed (photo aggregation and display)
- **RSS Generation:** RSS library for feed generation
- **Development Tools:** ESLint, PostCSS

### Key Features & Contributions

- **Pixelfed Integration:** Implemented API client to fetch photos from Pixelfed accounts with secure token-based authentication and error handling
- **Responsive Photo Gallery:** Built a masonry grid layout that dynamically adjusts columns based on screen size (1, 2, or 3 columns)
- **Custom Masonry Hook:** Developed `useMasonry` hook to calculate and apply dynamic row spacing for perfectly aligned image columns
- **Image Display Component:** Created reusable PixelfedMedia component to render media with captions and proper image dimensions
- **RSS Feed Generation:** Implemented automatic RSS feed generation from Pixelfed posts for content syndication (updates on every page build)
- **Server-Side Rendering:** Utilized Next.js server components to fetch data on the server, reducing client-side bundle size
- **Responsive Header & Navigation:** Designed responsive header component with branding and mobile-friendly navigation
- **Component Architecture:** Built modular, reusable components (Container, Header, Footer, Links) with consistent styling
- **Type Safety:** Implemented TypeScript throughout with custom types for Pixelfed API responses

### Project Highlights

This project demonstrates expertise in:
- **Modern Next.js Development:** Server-side data fetching with async components, optimized rendering strategy
- **External API Integration:** Secure API client implementation with proper authentication and error handling
- **Responsive Design:** Mobile-first CSS Grid and Tailwind CSS for adaptive layouts across devices
- **Client-Side Interactivity:** React hooks and refs for DOM manipulation and dynamic calculations
- **Performance Optimization:** Strategic use of server vs. client components and static generation
- **TypeScript & Type Safety:** End-to-end TypeScript implementation for maintainable code
- **Component Reusability:** Well-structured, composable components with clear separation of concerns

## Business Flow

A business observability application within the Dynatrace Platform, developed as part of Dynatrace – an observability and application performance monitoring platform that provides monitoring, analytics, automation, and AI-powered insights for cloud and enterprise systems. The Business Flow app enables users to model, visualize, and analyze business processes and their related telemetry data directly within the Dynatrace ecosystem.

[Business Flow Documentation](https://docs.dynatrace.com/docs/observe/business-observability/business-flow)￼

### Tech Stack

- **Frontend Framework:** React
- **Language:** TypeScript
- **State Management:** Zustand
- **Visualization & Graph UI:** React Flow
- **UI Framework:** Strato (Dynatrace design system and component library)
- **Query Language:** DQL (Dynatrace Query Language)
- **Platform Integration:** Dynatrace App SDKs and platform APIs
- **Testing**: Playwright, Jest
- **Tooling**: ESLint

### Key Contributions

- Frontend development: Contributed to the development of a business observability application within the Dynatrace platform, implementing interactive UI features and platform-integrated workflows in React and TypeScript.
- Platform integration: Integrated Dynatrace platform SDKs and APIs for data fetching, query execution, and application-level platform functionality.
- State management and UI architecture: Worked with Zustand-based state handling and reusable frontend patterns to support complex UI interactions and data-driven application behavior.
- Query-driven functionality: Implemented frontend features powered by DQL, enabling users to retrieve, filter, and analyze observability data within the application.
- Design system adoption: Developed and refined user interfaces using Strato, ensuring consistency with Dynatrace platform UX and accessibility standards.
- Collaboration within platform ecosystem: Contributed to applications that operate as part of the broader Dynatrace platform architecture, working within shared platform conventions, SDKs, and cross-team frontend patterns.

## Internal Sync / Time Tracking tool

A full-stack internal time tracking and synchronization platform built as an Nx monorepo
for automated time reporting and task sync across Wrike, Personio, Runn, and internal
reporting tools.

### Tech Stack

- **Monorepo:** Nx
- **Backend Framework:** NestJS 10
- **Frontend Framework:** React 18 with Vite
- **Language:** TypeScript
- **UI & Styling:** MUI 6, styled-components
- **State & Data Fetching:** TanStack React Query
- **ORM / Database:** Prisma 5
- **HTTP Client:** axios
- **Authentication / Security:** JSON Web Tokens, Cloudflare Access integration, session
  management
- **Background Processing:** Google Cloud Tasks / Cloudflare Workers via Wrangler
- **Infrastructure / Deployment:** Docker Compose, Terraform, Cloud Build, Wrangler
- **Testing:** Jest, Vitest, Playwright
- **Tooling:** ESLint, Prettier, Husky, pnpm
- **Utilities:** date-fns, zod, react-hook-form, Recharts

### Project Scope

- Backend API for time tracking, reporting, attendance, and synchronization
- Wrike data sync and webhook integration
- Personio attendance/time-off sync
- Runn project and assignment sync
- React-based dashboard and timer UI for internal time reporting
- Shared typed API contracts and translations across apps

### Key Contributions

- **Wrike synchronization backend:** Owned the core Wrike sync service and controllers,
  including sync flows for users, workflows, folders, tasks, timelogs, and custom Wrike
  fields.
- **Time tracking API:** Implemented primary time reporting services for availability,
  attendance, timer management, and reporting endpoints.
- **Frontend time tracking UX:** Contributed to dashboard pages, timer controls, task list
  components, and shared frontend providers for API, environment, real-time updates, and
  notifications.
- **Sync orchestration:** Built or maintained sync orchestration logic that coordinates
  nightly and full syncs across Wrike, Personio, and Runn.
- **Shared platform support:** Developed shared type definitions, DTOs, utilities, and
  translations to ensure consistent behavior across backend and frontend.
- **Infrastructure and tooling:** Updated repository tooling, package configuration,
  TypeScript setup, and deployment support for a stable developer experience.

### Highlights of Ownership

- Led backend synchronization for Wrike, including user, workflow, folder, task, timelog
  sync flows and webhook handling.
- Delivered core time tracking domain logic for attendance, availability, timer
  management, reporting, and validation.
- Built shared platform support for typed API contracts, translations, shared utilities,
  and configuration services used across backend and frontend.
- Contributed to frontend time tracking UX with dashboard pages, timer controls, task
  lists, and app-level providers for API access, real-time updates, notifications, and
  environment configuration.
- Supported repo stability through Prisma schema work, package configuration, and
  developer tooling improvements.

This summary is intended for external review and highlights the project’s technology and
your implementation ownership without exposing internal implementation details.


## Birdlife Website

A public-facing content website built for Birdlife, featuring dynamic content from Contentful and modern, responsive presentation for articles, birds, events, and publications.

https://www.birdlife.at/

### Tech Stack
- **Frontend Framework:** Next.js 14.2.3 (App Router)
- **Language:** TypeScript
- **Styling:** styled-components with styled-breakpoints for responsive design
- **CMS:** Contentful headless CMS via GraphQL
- **Images:** Next.js image optimization with a custom Contentful image loader
- **Animations & UX:** GSAP, embla-carousel-react, fslightbox-react, react-audio-visualize
- **Data integration:** GraphQL code generation with @graphql-codegen and typed client-side API helpers
- **Environment:** @t3-oss/env-nextjs and Zod for runtime environment validation
- **Developer tooling:** ESLint, Prettier, Husky, lint-staged, Storybook
- **Analytics & compliance:** Google Tag Manager and Usercentrics consent management
- **Performance:** Next.js ISR/revalidation, dynamic route handling, sitemap generation, static redirects and webhook-driven revalidation

### Key Contributions
- **Contentful integration:** Built and maintained the Contentful GraphQL integration layer, including typed query generation, preview mode support, and webhook-based revalidation for CMS updates.
- **Feature development:** Delivered content-driven pages for articles, birds, events, publications, and nested CMS pages with breadcrumbs, metadata, and dynamic routing.
- **Gallery & media experiences:** Implemented article gallery enhancements and image grid improvements to provide richer media layouts and better visual presentation.
- **Search and filtering:** Enhanced overview pages with filter support, query parameter synchronization, search term handling, and event filtering for user-facing content discovery.
- **Navigation and mobile UX:** Improved main navigation behavior, mobile nav height and styling, active item highlighting, and general layout polish across devices.
- **Quality and polish:** Fixed browser-specific issues such as iOS/Safari input behavior, FOUC, typography spacing, and breakpoint type issues while maintaining code quality through refactors and cleanup.
- **Compliance and analytics:** Added Usercentrics and Google Tag Manager integration, ensuring the website supports tracking and consent workflows consistently.

## HR Docs

A NestJS-based HR documentation system for managing employment contracts, document
generation, and e-signing integrations with external HR and signature services.

### Tech Stack

- **Backend Framework:** NestJS 10
- **Language:** TypeScript 5
- **Database:** PostgreSQL with Prisma ORM 5.22
- **Integrations:** Sage DPW API (HR data), Insign API (e-signatures), Azure Storage Blob,
  Microsoft Graph Client
- **PDF Generation:** @react-pdf/renderer 3.4.5
- **Validation:** class-validator, Zod 3.23
- **API Documentation:** Swagger/OpenAPI
- **Testing:** Jest
- **Containerization:** Docker, Docker Compose
- **Package Manager:** pnpm
- **Development Tools:** ESLint, Prettier, Husky pre-commit hooks, lint-staged

### Key Contributions

- **Employment Contract Module:** Developed comprehensive employment contract management
  system with document processing and lifecycle tracking
- **Document Templates System:** Created dynamic PDF templates for multiple companies supporting various ratings and personalization
- **Audit Logging:** Implemented event-driven audit logging for document operations,
  signatures, and system events
- **Sage DPW Integration:** Built client library for HR data synchronization with Sage
  DPW, including employee records and general data endpoints
- **Insign E-Signature Integration:** Developed e-signature workflow management with
  session handling and webhook processing
- **Azure Storage Integration:** Implemented secure document storage and retrieval using
  Azure Blob Storage
- **Email Notifications:** Added automated email functionality for contract and signature
  notifications (Microsoft Graph API)
- **API Testing Suite:** Created extensive Bruno test collections for Sage API endpoints
  covering employees, departments, and HR data
- **PDF Rendering Tools:** Built command-line tools for generating sample documents across
  different templates and configurations

This project demonstrates expertise in enterprise backend development, third-party API
integrations, document automation, and HR system digitization.

## Energiegemeinschaften

A modern energy community platform for an electricity provider, built as an Nx monorepo to support a production web frontend, NestJS API backend, synchronization service, and shared libraries.

### Tech Stack
- **Monorepo:** Nx 16, pnpm, TypeScript
- **Frontend:** React 18, React Router DOM 6, MUI 5, styled-components, Storybook
- **Backend:** NestJS 10, Express, Swagger, class-validator, class-transformer
- **Database / ORM:** PostgreSQL, Prisma 4, Drizzle ORM, Prisma DBML generation
- **Data Fetching:** TanStack React Query
- **Authentication / Security:** Keycloak, Passport JWT, express-session
- **Logging / Observability:** Pino, pino-loki, Swagger docs
- **Integrations:** Azure Blob Storage, SendGrid email, Slack webhooks, Unleash feature flags
- **Testing:** Jest, Cypress E2E, Storybook
- **Utilities:** Zod, date-fns, react-hook-form, react-phone-number-input, csv-parse

### Architecture
- Multi-application repository containing:
  - customer-facing React web application
  - NestJS backend API
  - synchronization service to get the electricity data from an external provider
  - end-to-end testing project
- Shared libraries include frontend components, utilities, API modules, translation assets, email templates, and common types.
- The frontend and backend are organized around reusable modules and shared type contracts to keep implementation consistent across apps.

### Key Contributions
- **Product onboarding and community setup:** Delivered the multi-step frontend wizard for energy community onboarding, including community type selection, personal data collection, production and consumption meter point forms, and review/founding flows.
- **Community and document services:** Implemented backend community management and document generation support, including admin endpoints, community member workflows, cofounder joining contracts, and migrated user handling.
- **Marketing and activation flows:** Added marketing opt-in functionality, activation flow improvements, and UI/UX refinements for customer onboarding and user conversion.
- **Shared localization and translation:** Managed translation assets and localization support for both frontend and API messaging.
- **Platform reliability and admin tooling:** Contributed to admin controls, impersonation handling (so support can login as a user to help them), document generation reliability, and migrated user locking logic.
- **Infrastructure and repo tooling:** Maintained the Nx monorepo configuration, package dependencies, Prisma schema, and custom NestJS library generation tooling.
- **UX polish and quality assurance:** Developed responsive navigation, dashboard layouts, progress navigation components, tooltip/error handling improvements, and ensured coverage through end-to-end tests.

### Notes
- This summary is based on the local repository contents and git history available in the current workspace.
- The repository includes extensive frontend, backend, and shared-library work, with strong emphasis on onboarding workflows, community management, and integration-driven platform features.

## Heylog Application

Built an MVP for a comprehensive logistics management platform with integrated messaging capabilities for
coordinating deliveries and managing driver communications.

https://heylog.com/features

### Tech Stack

- **Monorepo Tool:** Nx
- **Backend Framework:** NestJS (Node.js)
- **Frontend Framework:** React 18 with TypeScript
- **Database:** PostgreSQL with Prisma ORM
- **Authentication:** JWT with Passport.js
- **Messaging Integrations:** WhatsApp Business API, Facebook Messenger, Viber, Telegram,
  Twilio SMS
- **Real-time Features:** Pusher for notifications and real-time updates
- **File Storage:** Google Cloud Storage
- **Deployment:** Docker containers
- **Worker Runtime:** Cloudflare Workers
- **UI Library:** Material-UI (MUI) with styled-components
- **State Management:** SWR for data fetching
- **Internationalization:** i18next
- **Testing:** Jest with Cypress for E2E
- **Development Tools:** ESLint, Prettier, Husky pre-commit hooks, Prisma Studio

### Key Contributions

- **Database Architecture:** Designed and implemented a comprehensive database schema
  using Prisma, including models for workspaces, users, contacts, orders, conversations,
  messages, and billing systems
- **Backend API Development:** Built a full REST API with NestJS, implementing
  authentication, authorization (CASL), and business logic for logistics operations
- **Messaging System:** Integrated multiple messaging platforms (WhatsApp, Messenger,
  etc.) with support for templates, attachments, and real-time status tracking
- **Order Management:** Developed a complete order lifecycle system with status tracking,
  assignments to drivers, location management, and ETA functionality
- **Frontend Dashboard:** Created a React-based web application for workspace management,
  including contact management, order tracking, and conversation interfaces
- **Real-time Notifications:** Implemented push notifications and real-time updates using
  Pusher for seamless communication between drivers and dispatchers
- **Billing & Entitlements:** Built a subscription-based billing system with Stripe
  integration, including plan management and usage tracking
- **Internationalization:** Added multi-language support for German and other languages
  using DeepL translation API
- **Cloud Infrastructure:** Set up deployment pipelines with Docker and Cloudflare Workers
  for scalable backend services
- **Security & Compliance:** Implemented role-based access control, data validation, and
  secure API endpoints with Helmet and CORS

This project demonstrates expertise in full-stack development, API integrations, real-time
systems, and building scalable SaaS applications for logistics operations.
