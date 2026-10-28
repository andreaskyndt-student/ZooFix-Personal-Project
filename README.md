# ZooFix 🐘

ZooFix is a centralized animal management platform for zoos, providing an easy way to manage animal records, health, nutrition, behavior, breeding information, and daily care in one place.

> **Note:** ZooFix is a personal project developed in my free time. It is currently a work in progress and is **not intended for production use**.

## 🎯 Project Goal

The goal of ZooFix is to create a simple and intuitive platform that allows zoos and animal care teams to keep all relevant animal information organized in one place.

The initial focus is on **animal management**, with features centered around the care, health, behavior, nutrition, and breeding of individual animals.

## ✨ Planned Features

* 🐘 **Animal Management**

  * Create and manage animal profiles
  * Species and identification information
  * Birth and origin information
  * Enclosure assignments
  * Animal history

* 🩺 **Health Management**

  * Medical records
  * Health observations
  * Treatments and medical history
  * Health timeline

* 🥕 **Nutrition**

  * Feeding schedules
  * Food and feeding information
  * Feeding history

* 🧠 **Behavior & Observations**

  * Record behavioral observations
  * Track changes over time
  * Maintain an observation history

* 🧬 **Breeding**

  * Parent and offspring relationships
  * Breeding history
  * Family relationships

* 📊 **Dashboard**

  * Overview of the zoo's animals
  * Recent activity
  * Useful statistics and information

## 🛠️ Tech Stack

### Backend

* .NET
* C#
* Entity Framework

### Frontend

* React
* TypeScript

### Database

* PostgreSQL

### Architecture

ZooFix follows a client-server architecture:

```text
┌─────────────────────┐
│    React Frontend   │
│     TypeScript      │
└──────────┬──────────┘
           │
        REST API
           │
┌──────────▼──────────┐
│         .NET        │
│          C#         │
└──────────┬──────────┘
           │
    Entity Framework
           │
┌──────────▼──────────┐
│     PostgreSQL      │
└─────────────────────┘
```

## 🚧 Project Status

ZooFix is currently in **early development**.

The project is being built incrementally, starting with the core animal management functionality before expanding into additional features.

### Current Focus

* [x] Project setup
* [x] PostgreSQL database (in docker)
* [ ] Backend API
* [ ] React frontend
* [ ] Animal management
* [ ] Species management
* [ ] Enclosure management
* [ ] Health records
* [ ] Nutrition
* [ ] Behavior observations
* [ ] Breeding information
* [ ] Dashboard

## 📚 Purpose

ZooFix is primarily a personal learning and development project focused on building a full-stack application using modern web technologies.

The project provides an opportunity to explore:

* REST API development
* C# and .NET
* Entity Framework Core
* React and TypeScript
* PostgreSQL
* Database design
* Full-stack application architecture
* Distributed Monolith Architecture
* Docker and development workflows

## 📄 License

This project is currently a personal project and is not intended for production use.
