
# CarePulse App

Welcome to the CarePulse App! This application is designed to streamline the management of patient information for healthcare providers. It provides features for managing patient records, appointments, and communication between doctors and patients.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Patient Records**: Manage patient information, including personal details, medical history, and current treatments.
- **Appointments**: Schedule, update, and cancel patient appointments.
- **Doctor-Patient Communication**: Secure messaging between doctors and patients.
- **User Authentication**: Secure login and registration for doctors and patients using Appwrite.
- **Dashboard**: Overview of patient statistics and upcoming appointments.

## Installation

### Prerequisites

- Node.js (v14.x or later)
- npm (v6.x or later) or yarn (v1.x or later)

### Steps

1. Clone the repository:

```bash
git clone https://github.com/meshack-mbuvi/carepulse.git
cd carepulse
```

2. Install the dependencies:

```bash
npm install
# or
yarn install
```

3. Set up environment variables:

Create a `.env.local` file in the root directory and add the following variables:

```env
NEXT_PUBLIC_API_URL=http://your-api-url
NEXT_PUBLIC_API_KEY=your-api-key
```

4. Run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.

## Usage

### Running Locally

To run the app locally, use the following command:

```bash
npm run dev
# or
yarn dev
```

Visit `http://localhost:3000` in your browser to access the app.

### Building for Production

To build the app for production, use the following command:

```bash
npm run build
# or
yarn build
```

The build artifacts will be stored in the `.next/` directory.

### Starting the Production Server

After building the app, you can start the production server using:

```bash
npm start
# or
yarn start
```

## Folder Structure

```
/carepulse-nextjs
├── app               # Next.js app pages
│   ├── api          # API routes
│   ├── patients     # Patient-related pages
│   ├── appointments # Appointment-related pages
│   └── index.js     # Home page
├── components        # Reusable components
├── public            # Static assets
├── styles            # CSS styles
├── utils             # Utility functions
├── lib               # Contains more utility functions
├── .env.local        # Environment variables
├── next.config.js    # Next.js configuration
└── package.json      # Project metadata and dependencies
```

## Technologies Used

- **Next.js**: React framework for server-side rendering and static site generation.
- **React**: JavaScript library for building user interfaces.
- **Tailwind CSS**: Utility-first CSS framework.
- **Appwrite**: Open-source backend server for user management, authentication, and real-time data.
- **Typescript**

## Contributing

We welcome contributions from the community! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
