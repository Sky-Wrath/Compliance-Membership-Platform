# Compliance-Membership-Platform
A self hosted web application for compliance membership organization

# Compliance Membership Platform

A self-hosted web application for high-compliance membership organizations with verified anonymity, real-time chat, recruitment governance, and precision matching.

## Features

- **Verified Anonymity**: Users verify real identity via KYC but display anonymized handles
- **Onboarding Pipeline**: Sequential flow - Registration → KYC → Legal → Profile
- **Recruitment Committee**: Regional voting on applicants with Master Admin override
- **Real-time Chat**: WebSocket-based channels and direct messaging
- **Multi-region Governance**: Role-based access control per region
- **Moderation Suite**: Content flagging, review queues, suspension/ban tools
- **Events & Matching**: Event RSVP management and precision intro matching
- **Compliance Audit**: Full audit logging for regulatory compliance

## Tech Stack

- **Backend**: Node.js + Express
- **Real-time**: Socket.io (WebSocket)
- **Database**: PostgreSQL (relational) + Redis (sessions/presence)
- **Security**: JWT, AES-256 encryption, bcrypt
- **Deployment**: Railway.app, Docker

## Prerequisites

- Node.js >= 18.0.0
- npm >= 9.0.0
- Docker & Docker Compose (for local development)
- PostgreSQL 15+ (or via Docker)
- Redis 7+ (or via Docker)

## Local Setup

### 1. Clone Repository
```bash
git clone https://github.com/Sky-Wrath/compliance-membership-platform.git
cd compliance-membership-platform
