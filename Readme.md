**Overview**

This is a comprehensive AI-powered educational platform called "LearnAI" built as a full-stack web application. The system allows users to search for any topic and receive personalized educational content, adaptive quizzes, and AI-generated explanations tailored to their learning style and level. The platform tracks user progress, maintains learning streaks, and provides personalized recommendations to enhance the learning experience.

**User Preferences**

Preferred communication style: Simple, everyday language.

**System Architecture**

**Frontend Architecture**

Framework: React with TypeScript using Vite as the build tool

UI Library: Shadcn/ui components built on Radix UI primitives for consistent, accessible interface elements

Styling: Tailwind CSS with custom design system including dark mode support

State Management: TanStack Query (React Query) for server state management and caching

Routing: Wouter for lightweight client-side routing

Form Handling: React Hook Form with Zod validation resolvers

**Backend Architecture**

Runtime: Node.js with Express.js framework

Language: TypeScript with ES modules

Database ORM: Drizzle ORM for type-safe database operations

Authentication: Replit Auth integration with OpenID Connect for secure user authentication

Session Management: Express sessions with PostgreSQL storage using connect-pg-simple

**Database Design**

Database: PostgreSQL with Neon serverless driver

Schema:
Comprehensive relational design including:

User profiles with learning preferences and progress tracking
Topics with AI-generated content and metadata

Quiz system with questions, answers, and scoring

Search history and user progress tracking

Session storage for authentication

**AI Integration**

AI Provider: OpenAI API (GPT-4o model) for content generation

Content Generation: Personalized educational content based on user level and topic

Quiz Generation: Adaptive quiz questions with explanations

Personalization: AI-driven recommendations based on user history and preferences

**Development Environment**

Development: Replit-optimized with runtime error overlays and cartographer integration

Build Process: Vite for frontend bundling, esbuild for server compilation

Type Safety: Comprehensive TypeScript configuration with strict mode enabled

Code Quality: Path mapping for clean imports and component organization


**External Dependencies**

**Core Infrastructure**

Database: Neon Database (PostgreSQL serverless)

Authentication: Replit Auth with OpenID Connect

AI Services: OpenAI API for content and quiz generation

Session Storage: PostgreSQL-backed session management

**Key Libraries**

UI Components: Radix UI primitives for accessible component foundation

Styling: Tailwind CSS with PostCSS for utility-first styling

State Management: TanStack Query for efficient data fetching and caching

Form Validation: Zod for runtime type validation and schema definition

Date Handling: date-fns for date manipulation and formatting

Utilities: clsx and class-variance-authority for conditional styling

**Development Tools**

Build Tools: Vite with React plugin and TypeScript support

Replit Integration: Custom plugins for development environment optimization

Font Loading: Google Fonts integration for typography

Error Handling: Runtime error modal for development debugging

import type { Config } from "tailwindcss";


Loading... - Replit
