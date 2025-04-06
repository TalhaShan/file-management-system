# File Management System - Frontend

React frontend for the File Management System.

## Project Structure

```
frontend/
├── src/
│   ├── components/         # Reusable UI components
│   ├── pages/             # Page components
│   ├── services/          # API services
│   ├── store/             # Redux store
│   ├── types/             # TypeScript types
│   ├── utils/             # Utility functions
│   ├── hooks/             # Custom React hooks
│   ├── assets/            # Static assets
│   └── App.tsx            # Root component
├── public/                # Public assets
├── package.json           # Dependencies
└── tsconfig.json          # TypeScript configuration
```

## Dependencies

- React 18
- TypeScript
- Material-UI
- Redux Toolkit
- React Router
- Axios
- Formik
- Yup
- React Query
- Styled Components

## Features

- User authentication
- File upload/download
- File sharing
- File search
- User profile management
- Responsive design
- Dark/Light theme

## Pages

- Login/Register
- Dashboard
- File Explorer
- File Upload
- User Profile
- Shared Files
- Settings

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start development server:
   ```bash
   npm start
   ```

3. Build for production:
   ```bash
   npm run build
   ```

## Environment Variables

Create a `.env` file in the root directory:

```
REACT_APP_API_URL=http://localhost:8080/api
REACT_APP_AWS_REGION=your-aws-region
```

## Testing

- Unit tests: `npm test`
- Build: `npm run build`

## Code Style

- ESLint for linting
- Prettier for code formatting
- Husky for pre-commit hooks

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest) 