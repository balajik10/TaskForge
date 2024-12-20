# TaskForge

TaskForge is a robust Project Management Dashboard application built using modern web technologies to streamline task and team management. Designed for scalability, it integrates Next.js, Tailwind CSS, and AWS services like EC2, RDS, and Cognito. TaskForge simplifies project tracking, collaboration, and timeline management for teams of all sizes.

---

## Features

- **Interactive Dashboard**: Real-time project tracking with Gantt charts and visual data representation.
- **Team Collaboration**: Manage teams, assign roles, and monitor tasks effortlessly.
- **Task Management**: Create, edit, prioritize, and search tasks efficiently.
- **Authentication**: Secure user authentication powered by AWS Cognito.
- **Scalability**: Deployed on AWS EC2 and RDS for high performance and reliability.
- **Modern UI**: Sleek, responsive interface built with Tailwind CSS and Material UI.

---

## Tech Stack

### Frontend:
- **Next.js**: Framework for server-rendered React applications.
- **Tailwind CSS**: Utility-first CSS framework for custom UI.
- **Redux Toolkit**: State management and data fetching.
- **Material UI**: Advanced data grids and charts.

### Backend:
- **Node.js**: Backend runtime environment.
- **Express.js**: Web server framework.
- **Prisma**: Database ORM for PostgreSQL.
- **PostgreSQL**: Relational database.

### AWS Services:
- **EC2**: Compute service for hosting backend.
- **RDS**: Managed PostgreSQL database.
- **Cognito**: User authentication and management.
- **S3**: Storage for assets.
- **API Gateway**: Secure API endpoints.

---

## Getting Started

### Prerequisites

1. Node.js (v18 or higher)
2. PostgreSQL
3. AWS Account
4. Docker (for local development)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/balajik10/taskforge.git
   cd taskforge
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables:
   - Create a `.env` file in the root directory.
   - Add database and AWS credentials:
     ```env
     DATABASE_URL=postgresql://username:password@localhost:5432/taskforge
     AWS_REGION=your-region
     AWS_COGNITO_USER_POOL_ID=your-user-pool-id
     AWS_COGNITO_CLIENT_ID=your-client-id
     ```

4. Start the application:
   ```bash
   npm run dev
   ```

5. Access the application at `http://localhost:3000`.

---

## Deployment

1. Deploy the backend to AWS EC2:
   - Create an EC2 instance.
   - Install Node.js and configure the server.

2. Set up RDS for PostgreSQL:
   - Create a PostgreSQL database instance on AWS RDS.

3. Configure AWS Cognito for authentication.

4. Deploy the frontend using AWS Amplify or Vercel.

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Submit a pull request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact

For questions or feedback, please contact:
- Email: balajik.0204@gmail.com
- GitHub: [balajik10](https://github.com/balajik10)

