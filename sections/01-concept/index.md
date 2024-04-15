---
title: Concept
has_children: false
nav_order: 2
---

# Concept

The project consists in developing an instant messaging appliaction (WhatsApp clone). More specifically, the application will be composed of:
- Backend that will provide access to various functionalities and will handle data persistence management.
- Frontend, which will be provided both as a mobile application and as a web application.

## Use case 1: Sending Messages between Registered Users

- **Actors**: Registered User, Message Recipient
- **Description**: The registered user can send text messages, images, videos, or other types of content to the selected recipient.
- **Main Flow**:
    - The user opens the instant messaging application.
    - Selects a contact or searches for the recipient's name.
    - Composes the message (textual or multimedia).
    - Sends the message.   
    - The recipient receives the message and can view it.

## Use case 2: Creating Chat Groups

- **Actors**: Registered User, Group Members
- **Description**: The registered user can create chat groups to chat with multiple people simultaneously.
- **Main Flow**:
    - The user opens the instant messaging application.
    - Selects the option to create a new group.
    - Adds group members (existing contacts or new contacts).
    - Assigns a name to the group and, optionally, a profile picture.
    - Creates the group and sends an initial message.
    - Group members receive a notification and can start chatting in the group.