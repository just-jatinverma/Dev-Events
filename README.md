# Dev Events

A platform for finding and booking developer events.

## About The Project

This is a full-stack application built with Next.js, TypeScript, and MongoDB. It allows users to browse, create, and book developer events.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
4. Run the development server
   ```sh
   npm run dev
   ```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## API Endpoints

The following API endpoints are available:

* `GET /api/events`: Fetches all events.
* `POST /api/events`: Creates a new event.
* `GET /api/events/[slug]`: Fetches a single event by its slug.