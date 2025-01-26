**Week 5: Real-Time Communication with Socket.io**

**Objective:**

- Develop a real-time web application utilizing Socket.io.
- Apply concepts of WebSockets, rooms, and namespaces.
- Understand how to integrate real-time functionality into a full-stack MERN application.

**Project Suggestion:** Build a "Real-Time Collaborative Notes" application that allows multiple users to create, edit, and view notes in real time.

**Instructions:**

1. **Project Setup:**
   - Create a new project folder named `real-time-notes`.
   - Set up a backend using Express.js and Socket.io.
   - Initialize a frontend using React.

2. **Application Features:**
   - Users should be able to:
     - Join a specific "room" to collaborate on a shared note.
     - See real-time updates when another user edits the note.
     - Create new notes and edit existing ones.
     - Receive notifications when a new user joins or leaves a room.

3. **Backend Requirements:**
   - Implement WebSocket connections using Socket.io.
   - Create RESTful endpoints for saving and retrieving notes.
   - Implement room-based communication for collaborative editing.

4. **Frontend Requirements:**
   - Implement a UI for creating, viewing, and editing notes.
   - Allow users to join specific rooms via a unique URL or code.
   - Display a list of online users in each room.

5. **State Management:**
   - Use React state and context API to manage application state.
   - Handle incoming real-time data efficiently to update UI.

6. **Testing:**
   - Test real-time functionality by opening multiple browser tabs.
   - Ensure messages and updates are reflected correctly across all clients.

7. **Deployment:**
   - Deploy the backend to a cloud service such as Render.
   - Deploy the frontend to Vercel.
   - Ensure proper environment variable setup for production.

8. **Documentation:**
   - Write a `README.md` file including:
     - Project overview.
     - Steps to install and run the project.
     - Explanation of key real-time concepts used.

9. **Submission:**
   - Push your project to your GitHub repository.

**Evaluation Criteria:**

- Proper implementation of WebSocket communication.
- Ability to join rooms and collaborate in real-time.
- Clean UI and responsive design.
- Structured and well-documented code.
- Successful deployment and working application link.

