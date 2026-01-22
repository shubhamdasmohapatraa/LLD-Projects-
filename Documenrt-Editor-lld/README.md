# Document Editor – Low Level Design (Java)

## Overview

This repository contains the low-level design (LLD) of a Document Editor system inspired by tools like Google Docs.

The design follows **SOLID principles** and clean object-oriented design in Java.

## Key Components

* **DocumentElement (interface)** – abstraction for all document elements
* **TextElement, ImageElement** – concrete implementations
* **Document** – composite that holds document elements
* **DocumentEditor** – handles editing operations
* **DocumentRenderer** – responsible for rendering
* **Persistence (interface)** – strategy for saving documents
* **FileStorage, DBStorage** – concrete persistence implementations

## Design Principles Used

* Single Responsibility Principle (SRP)
* Open/Closed Principle (OCP)
* Dependency Inversion Principle (DIP)
* Composite Pattern
* Strategy Pattern

## Notes

* This project focuses on design clarity rather than full implementation.
* The system is easily extensible for new element types or storage strategies.
