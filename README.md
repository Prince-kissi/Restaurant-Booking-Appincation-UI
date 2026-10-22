# Restaurant Booking Application

A restaurant table reservation interface for **La Cuisine Elegante**,
built with React and TypeScript. Guests can choose a reservation date,
time, and party size, enter their contact details, add special requests,
and view a reservation confirmation.

## Features

-   Restaurant landing page with a dining-themed hero image
-   Two-step reservation flow
-   Date, time, and party-size selection
-   Guest contact form (name, email, and phone)
-   Optional special requests
-   Reservation confirmation displaying booking details
-   Option to start a new reservation
-   Responsive interface components and Lucide icons

## Tech Stack

-   **React 18**
-   **TypeScript**
-   **Vite**
-   **Material UI** and Emotion
-   **Lucide React** icons
-   **React Day Picker** for date selection
-   **Tailwind CSS** tooling and project design tokens

## Getting Started

### Prerequisites

-   Node.js and npm
-   Git (optional, for cloning the repository)

### 1. Clone the repository

Replace `Prince-Kissi` with your GitHub username if you are cloning
from GitHub.

``` bash
git clone https://github.com/Prince-Kissi/restaurant-booking-application.git
cd restaurant-booking-application
```

If you downloaded the source code instead, open a terminal in the
project folder.

### 2. Install dependencies

``` bash
npm install
```

If the repository includes a `pnpm-lock.yaml` and you use pnpm, you can
install dependencies with `pnpm install` instead.

### 3. Run the project locally

The original project configuration includes Vite. If a development
script is available in `package.json`, run:

``` bash
npm run dev
```

If there is no `dev` script, you can start Vite directly with:

``` bash
npx vite
```

Open the local URL printed in the terminal (commonly
`http://localhost:5173`).

### 4. Build for production

``` bash
npm run build
```

Vite generates the production build in the `dist` directory.

## How It Works

1.  Choose a date, available time, and party size.
2.  Enter guest details and any special requests.
3.  Submit the form to view the reservation confirmation.
4.  Start another reservation when needed.

## Restaurant Contact Details

The interface currently displays the following sample contact
information:

-   **Phone:** `+233 123456789`
-   **Address:** `123 Banku Street, Greater Accra`

Update these values in the relevant application component if they are
placeholders.

## Important Notes

This repository was created from a Figma Make project export. The
reservation flow shown in the exported application manages the booking
in the frontend. A backend API, database persistence, authentication,
email/SMS notifications, and live table availability are not confirmed
as part of this export. Add and configure these services before using
the application for real customer bookings.

## Screenshots

Add screenshots of the application here after uploading them to your
repository. For example:

``` markdown
![Restaurant booking home page](docs/screenshots/homepage.png)
![Reservation confirmation](docs/screenshots/confirmation.png)
```

## Future Improvements

-   Connect reservations to a backend and database
-   Check real-time table availability
-   Add customer accounts and reservation history
-   Send booking confirmations by email or SMS
-   Add reservation cancellation and modification
-   Add automated tests and deployment instructions

## License

No license has been specified yet. Add a `LICENSE` file if you intend to
publish the project under an open-source license.
