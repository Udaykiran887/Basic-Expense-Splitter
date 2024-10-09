# Basic Expense Splitter

Basic Expense Splitter is a mobile application designed to help users easily split expenses within a group. The app allows users to create groups, add expenses, and automatically calculate how much each member owes or is owed based on the expenses added. It utilizes Android Studio for app development, Node.js for the backend, and MongoDB for persistent data storage.

## Features

- Create groups with a unique group name.
- Add expenses with details like who paid and how much.
- Automatically calculate how much each member owes or is owed.
- View a balance sheet showing who paid more and who owes the remaining amounts.
- Persistent storage using MongoDB for managing user data.

## Tech Stack

- **Android Studio**: For building the mobile application using Java or Kotlin.
- **React Native**: (Optional) For cross-platform development.
- **Node.js**: Backend server for handling API requests.
- **Express.js**: For creating RESTful APIs.
- **MongoDB**: For data storage and management.
  
## Installation

### Backend (Node.js + MongoDB)

1. Clone the repository:

   ```bash
   git clone https://github.com/Udaykiran887/expense-splitter.git
   ```

2. Navigate into the backend directory:

   ```bash
   cd expense-splitter/backend
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Set up your MongoDB database and create a `.env` file in the backend directory:

   ```env
   MONGO_URI=your-mongo-db-connection-string
   ```

5. Start the backend server:

   ```bash
   npm run server
   ```

### Frontend (Android Studio)

1. Open Android Studio and import the project files from the `frontend` directory.

2. Make sure your Android Studio is set up with the appropriate SDKs for Java or Kotlin development.

3. Configure your app to connect with the backend Node.js server by updating the base URL for API calls in your Android code.

4. Run the project on an Android emulator or physical device:

   - In Android Studio, click on **Run > Run 'app'**.

### React Native (Optional)

If you're using React Native for cross-platform development:

1. Navigate into the `frontend` directory:

   ```bash
   cd expense-splitter/frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the React Native app:

   ```bash
   npm start
   ```

## How to Use

1. Open the app and create a group by entering a unique group name.
2. Add group members and start adding expenses by specifying who paid and the amount.
3. The app will automatically calculate balances.
4. Use the balance sheet to view who paid more and who owes the remaining amount.

## Future Enhancements

- Integration with payment gateways.
- Add notifications for outstanding balances.
- Export the balance sheet to a PDF or CSV format.

## License

This project is licensed under the MIT License.

---

For any queries or suggestions, feel free to reach out:

- Email: [udaykirankothagattu@gmail.com](udaykirankothagattu@gmail.com)
- LinkedIn: [Uday Kiran Kothagattu](https://www.linkedin.com/in/uday-kiran-kothagattu)
- GitHub: [Udaykiran887](https://github.com/Udaykiran887)
