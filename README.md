## Water Consumption Tracker Application
The Water Consumption Tracker is a RESTful backend application designed to help users track their daily water intake. 
The system allows users to log water consumption, calculate daily intake, and view their water consumption history by day or month. 
It also includes user authentication and profile management features.

**Features**

**Server Setup**
- Module Integration: Necessary modules such as express, mongoose, cors, and others are integrated for a seamless server setup.
- CORS Configuration: CORS is enabled to allow cross-origin interaction between the frontend and backend.
- Error Handling: Custom error-handling functions capture and process errors for a better user experience.
**Database (DB)**
- Database Structure: The structure of the database is designed to accommodate user profiles, water consumption logs, and daily water rate records.Relationships between tables are defined based on user-specific water data.
- Database Connection: The application initializes and connects to the database using MongoDB, ensuring persistence for user data and water consumption logs.
**API Documentation**
- Swagger Integration: Swagger is used for API documentation, allowing developers to interact with the API through a user-friendly interface.
- Code Example: Swagger Implementation
- Example Documentation: SwaggerHub API Example
- Endpoint Descriptions: Each endpoint is documented with parameters, responses, and error messages.
  - User Registration.
  - User Login.
  - User Logout.
  - Allows users to upload or update their profile picture.
  - Retrieves user information.
  - Update User Information.
  - Updates specific fields such as contact information.

### Installing:
1. **Clone the repository**:
   ```bash
   git clone https://github.com/NatalySheludko/successful-minds-db.git

3. **Instal dependencies**:
   ```bash 
   npm install

4. **Run local server**:
   ```bash
   npm run dev

5. **Open localhost**:
   ```bash  		
   http://localhost:3090

## Technologies Used
- Node.js
- Express.js
- MongoDB with Mongoose
- Swagger for API documentation
- JWT for authentication
- CORS for cross-origin request handling
