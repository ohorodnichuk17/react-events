# React Events Application

This React project is a complete event management system. It uses `React Router` for navigation, `React Query` for data fetching and mutation, and includes various components to manage events such as creating, editing, viewing, and deleting events. The project utilizes a REST API to fetch and manage event data.

## Features

- **View Events:** Browse through the list of all events.
- **Create Event:** Allows users to create a new event with details such as title, description, date, time, location, and an associated image.
- **Edit Event:** Edit the details of an existing event.
- **Delete Event:** Delete an existing event with confirmation via a modal.
- **Search Events:** Search for events by name or criteria.
- **Event Details:** View detailed information about an event, including date, time, and location.

## Technologies Used

- **React**: The core JavaScript library for building the UI.
- **React Router**: Handles client-side routing and navigation between pages.
- **React Query**: For data fetching, caching, synchronization, and error handling.
- **React Portals**: Used for modal dialog boxes.
- **TanStack Query**: Advanced hooks for managing server state and data synchronization.

## Components Overview

1. **EventList**: Displays a list of all events.
2. **EventDetails**: Provides detailed information about a specific event, with options to delete or edit.
3. **EventForm**: A reusable form component for creating or editing events.
4. **Modal**: A reusable modal component for confirmation dialogs and forms.
5. **ImagePicker**: Allows users to select images from a set of available event images.
6. **Header**: Displays the main header of the application, with navigation links.
7. **LoadingIndicator**: A simple loading spinner for asynchronous actions.
8. **ErrorBlock**: A component to display error messages when something goes wrong.

## API Endpoints

- **Fetch Events**: Fetches a list of all events from the server.
  - URL: `http://localhost:3000/events`
  - Method: `GET`

- **Create Event**: Creates a new event.
  - URL: `http://localhost:3000/events`
  - Method: `POST`

- **Fetch Event by ID**: Fetches the details of a specific event by its ID.
  - URL: `http://localhost:3000/events/{id}`
  - Method: `GET`

- **Update Event**: Updates an existing event.
  - URL: `http://localhost:3000/events/{id}`
  - Method: `PUT`

- **Delete Event**: Deletes an event by ID.
  - URL: `http://localhost:3000/events/{id}`
  - Method: `DELETE`

- **Fetch Selectable Images**: Fetches a list of images that can be used for events.
  - URL: `http://localhost:3000/events/images`
  - Method: `GET`

<img width="1440" alt="Screenshot 2024-09-12 at 18 34 51" src="https://github.com/user-attachments/assets/3b8d35d9-5bb0-4275-9f4c-a3b917ff0eaa">

<img width="1440" alt="Screenshot 2024-09-12 at 18 34 43" src="https://github.com/user-attachments/assets/d8b2eab3-db03-4df9-a2d6-842419738bc1">

<img width="1440" alt="Screenshot 2024-09-12 at 18 34 37" src="https://github.com/user-attachments/assets/f9648403-412b-4c67-abec-ce97047fddde">

<img width="1440" alt="Screenshot 2024-09-12 at 18 34 29" src="https://github.com/user-attachments/assets/b1d60c2b-ec33-4249-83f4-9239a0f57e84">

<img width="1440" alt="Screenshot 2024-09-12 at 18 33 59" src="https://github.com/user-attachments/assets/a519c452-6244-45de-9969-4a526ec12c62">

<img width="1440" alt="Screenshot 2024-09-12 at 18 33 48" src="https://github.com/user-attachments/assets/78413077-4270-4c39-b66c-9c0ec0b9f5c6">
