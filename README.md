# Project Name

Distributed Application task week 5

## Table of Contents

- [Deploying the Frontend](#deploying-the-frontend)
- [Database Connection and E2E Flow](#database-connection-and-e2e-flow)

## Deploying the Frontend

To deploy the frontend on a separate server, follow the steps below:

1. **Remove Frontend from Backend:**
   - Ensure that the frontend is decoupled from the backend. Remove any dependencies that link the frontend to the backend.

2. **Deploy Frontend:**
   - Host the frontend on a separate server or platform of your choice. You can use services like Netlify, Vercel, GitHub Pages, or any other suitable platform.

3. **Update Configuration:**
   - If there are configuration files or environment variables related to the frontend, update them to reflect the new deployment URL or settings.

## Database Connection and E2E Flow

To establish a connection to the database and ensure the end-to-end (E2E) flow is working, follow the steps below:

1. **Database Setup:**
   - Configure your database connection settings in the backend. This includes database URL, credentials, and any other relevant configurations.

2. **Run Migrations:**
   - Ensure that your database schema is up-to-date by running any necessary database migrations using the following command:
     ```bash
     python manage.py migrate
     ```

3. **Backend Sysout Setup:**
   - Verify that the user input is being displayed in the backend's `sysout`. Check the backend logs or console output for user input confirmation.

4. **UI Display Setup:**
   - Confirm that contents from the database are displayed on the UI. Implement the necessary API calls or queries to fetch data from the database and render it on the frontend.

5. **End-to-End Testing:**
   - Perform end-to-end testing to ensure that user input is correctly stored in the database and displayed on the UI.

## Additional Notes

- Include any additional information or considerations specific to your project.
- Provide information on how to report issues or contribute to the project if applicable.

## License

This project is licensed under the [License Name] - see the [LICENSE.md](LICENSE.md) file for details.
