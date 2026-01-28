## Project Setup

To run the project, in the root create a .env file and add these two variables, with your own values.

MONGO_URI
JWT_SECRET

Then run this command

```bash
npm install && npm start
```

## API Endpoints

### Authentication
| Method | Endpoint | Description |
|------|---------|-------------|
| POST | `/auth/register` | Register a new user |
| POST | `/auth/login` | Login user |

### Jobs
| Method | Endpoint | Description |
|------|---------|-------------|
| POST | `/jobs` | Create a new job |
| GET | `/jobs` | Get all jobs |
| GET | `/jobs/{id}` | Get a single job |
| PATCH | `/jobs/{id}` | Update job details |
| DELETE | `/jobs/{id}` | Delete a job |

> Base URL: `https://api.example.com/api/v1`  
> Authentication: Bearer Token (required for Jobs endpoints)

## Swagger screenshot

<p align="center">
  <img src="assets/ss.png" width="600" />
</p>
