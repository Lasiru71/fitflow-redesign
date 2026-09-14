# FitFlow Redesign

FitFlow Redesign is a fitness tracking mobile app redesign created as part of the IT3060 Human Computer Interaction module.

The main idea of this project is to improve the existing FitFlow experience by making it more personalized, easier to use, and more engaging. The redesign focuses on some of the main problems identified in the case study, such as generic workout plans, difficult nutrition tracking, lack of motivation, and limited social interaction.

## What We Want to Improve

With this redesign, we mainly want to:

- Give users workout plans that better match their needs and routines.
- Make food and nutrition tracking quicker and easier.
- Show fitness progress in a simple and understandable way.
- Help users stay motivated through challenges and community features.
- Keep user accounts and fitness information secure.
- Build the system in a way that can be improved and expanded later.

## Technology Stack

For the mobile application, we selected **React Native** because it allows us to develop for both Android and iOS using a shared codebase.

The main backend will use **Node.js with Express.js** to handle application logic and API requests.

**Firebase Authentication** will be used for user login and authentication. Firebase services can also support real-time features such as notifications and community updates.

For structured application data, **PostgreSQL** can be used to store important user, workout, and fitness-related information.

AI features will be handled separately using **TensorFlow Lite** and cloud-based AI services when needed. This can support features such as personalized workout recommendations and smarter nutrition tracking.

## Project Structure

The repository is organized into a few main sections:

- `frontend/` - React Native mobile application
- `backend/` - Node.js and Express backend
- `ai-service/` - AI and machine learning related features
- `docs/` - Project documentation

Inside the `docs` folder, we keep the technology comparison, architecture diagram, and Architecture Decision Record (ADR).

## Main Features

The proposed FitFlow redesign includes:

- Personalized workout recommendations
- Workout and progress tracking
- Easier nutrition tracking
- Community challenges and social features
- Secure user authentication
- Real-time notifications
- Better control over personal fitness information

## System Overview

The React Native mobile app communicates with the Node.js/Express backend through APIs.

Firebase Authentication handles user authentication, while Firebase services can be used for real-time notifications and community-related updates.

The AI service is kept separate from the main backend so that features such as workout personalization and nutrition recognition can be developed and improved independently.

## Documentation

This repository also contains the supporting documents prepared for the FitFlow technology selection and system design:

- Technology Comparison Matrix
- High-Level Architecture Diagram
- Architecture Decision Record (ADR)

## Module Details

**Module:** IT3060 - Human Computer Interaction  
**Year:** 3rd Year, Semester 2 - 2026  
**Lab Exercise:** 05  
**Project:** FitFlow Redesign  
**Student ID:** IT23556034
