# FitnessWorkout

## Table of Contents

1. [Overview](#Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)
4. [Schema](#Schema)

## Overview

### Description

FitnessWorkout is a fitness and exercise app designed to help users plan and track their workout routines. Whether you're a beginner or an experienced fitness enthusiast, this app provides features to support your fitness journey.

### App Evaluation

- **Category:** Health & Fitness
- **Mobile:** This app is primarily for mobile devices, providing users with workout plans on the go.
- **Story:** FitnessWorkout aims to make it easy for users to access and customize workout plans to meet their fitness goals.
- **Market:** The target market for this app is anyone interested in improving their fitness and tracking their progress.
- **Habit:** Users can create daily or weekly workout routines, and the app encourages regular exercise.
- **Scope:** Initially, the app will focus on generating random workouts, allowing customization, and tracking progress. It may expand to include additional features in the future.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

- [x] Users can create an account and log in.
- [x] Users can generate a random workout routine.
- [x] Users can customize and save workout routines.
- [ ] Users can track their workout progress.
- [ ] Users can view exercise demonstrations.

**Optional Nice-to-have Stories**

- [ ] Users can share their workout routines on social media.
- [ ] Users can receive workout reminders.
- [ ] Users can set fitness goals and receive recommendations.

### 2. Screen Archetypes

- [ ] Login
- [ ] Register
- [ ] Home (Workout Generation)
- [ ] Workout Customization
- [ ] Saved Routines
- [ ] Progress Tracking
- [ ] Exercise Library
- [ ] Social Sharing
- [ ] Notifications
- [ ] Settings

### 3. Navigation

**Tab Navigation** (Tab to Screen)

- Home
- Saved Routines
- Progress Tracking

**Flow Navigation** (Screen to Screen)

- Login
  - Home
- Register
  - Home
- Home (Workout Generation)
  - Workout Customization
  - Exercise Library
  - Social Sharing
- Workout Customization
  - Saved Routines
- Saved Routines
  - Workout Customization
- Progress Tracking
  - Home
- Exercise Library
  - Exercise Details
- Social Sharing
  - Home

## Wireframes



## Schema

### Models

- User
  - Username
  - Password
  - Email
  - Profile Picture
- Workout
  - Title
  - Description
  - Exercises
  - User (relationship)
- Exercise
  - Name
  - Description
  - Video Demo URL

### Networking

- Home Screen
  - Query for a random workout from the server.
- Workout Customization
  - Create and save a new workout on the server.
- Saved Routines
  - Query user-specific workout routines from the server.
- Progress Tracking
  - Log completed workouts and store data on the server.
- Exercise Library
  - Query and display a list of exercises with video URLs.
- Social Sharing
  - Share workout routines and achievements on social media.
- Notifications
  - Set and manage workout reminders.
- Settings
  - Update user profile information.

## License

    Copyright 2023 Henry Ingraham

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
