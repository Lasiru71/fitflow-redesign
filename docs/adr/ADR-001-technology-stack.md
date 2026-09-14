# ADR-001: Technology Stack for FitFlow

## Status

Accepted

## Context

For the FitFlow redesign, we needed a technology stack that could support both Android and iOS while keeping development and maintenance manageable.

The application also needs secure user authentication, real-time community features, fitness data storage, and AI-based features such as personalized workout recommendations and nutrition support.

## Decision

For the proposed FitFlow system, we selected:

- **React Native** for the mobile application
- **Node.js with Express.js** for the main backend API
- **PostgreSQL** for structured application data
- **Firebase Authentication** for login and user authentication
- **Firebase services** for notifications and real-time community features
- **TensorFlow Lite and cloud AI services** for AI-related features

## Why We Chose This Stack

React Native allows us to support Android and iOS without developing two completely separate applications.

Node.js and Express work well with React Native and are suitable for building the REST APIs needed by FitFlow.

PostgreSQL provides a reliable way to manage structured data such as user profiles, workout records, nutrition information, and progress data.

Firebase makes authentication and real-time features easier to manage, while keeping these services separate from the main backend.

The AI service is also separated from the main backend so that AI features can be improved later without making the main application unnecessarily complex.

## Consequences

This approach gives the project a good balance between development speed, performance, security, and maintainability.

One disadvantage is that the system uses several different technologies. Because of this, the responsibilities of the backend, database, Firebase services, and AI service need to be clearly separated.
