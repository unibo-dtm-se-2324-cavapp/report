---
title: Design
has_children: false
nav_order: 4
---

# Design

This chapter explains the strategies used to meet the requirements identified in the analysis

## Architecture

At a high level, Cavapp consists of 4 fundamental components:

- The backend, which provides an API for all application functionalities
- Two frontends: one web and one mobile, which interface with the backend through the REST API
- The database for data persistence

![Components](/imgs/component-diagram.svg)

The chosen architecture to implement all this is a layered architecture, comprising:

- Presentation layer: responsible for presenting data to clients and handling their requests
- Business layer: responsible for implementing the application's logic
- Persistence layer: acting as an interface between the business layer and the database layer
- Database layer: responsible for data storage and management


## Modelling

- This section explains how the domain has been modelled
- This section should contains some class diagrams
    - The application's most relevant design aspects are highlighted, showcasing how they solve the problems described in the analysis
    - Diagrams do not show implementation aspects that are not relevant, such as private fields
- This section describe how the tactical patterns and other aspects of DDD seen in class were applied


## Interaction
- This section explains the behavior of the system, for instance using sequence or activity diagrams

## Behaviour
- This section explains the possible states that the system can be in and the events that cause the transition from one state to another, for instance using UML state diagrams

## Data-related aspects
- This section explains all the details related to the data, for instance:
    - Data schema
    - Data persistence technologies (if used), for example: MySQL, MongoDB, ...
