# Project Context for Claude Code

## Tech Stack
- Backend: Python (Flask) or Node.js (Express) — confirm as a team before Sprint 1
- Database: MySQL
- Frontend: HTML/CSS/JavaScript (or React)
- Payment: Razorpay (test mode)

## Folder Structure
- /auth        → User registration, login, role-based access, admin
- /restaurant  → Restaurant and menu management
- /orders      → Cart and order management
- /payment     → Payment gateway, delivery tracking, notifications
- /database    → Shared schema (schema.sql)

## Conventions
- Use snake_case for database columns, camelCase for JS variables
- All API routes prefixed with /api/
- Every module reads from the shared schema in /database/schema.sql — do not redefine tables locally

## Core Entities (from Class Diagram)
User, Customer, DeliveryAgent, Restaurant, MenuItem, Order, OrderItem, Payment
