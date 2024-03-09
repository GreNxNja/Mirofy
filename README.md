## Miro Clone

**Overview**

The Miro Clone project aims to replicate the features and functionality of Miro, a popular online collaborative whiteboarding platform.

**Technologies Used**

- **Frontend:**
  - Next.js
  - React
  - Tailwind CSS
- **Backend:**
  - Clerk (authentication)
- **Real-Time Collaboration:**
  - Convex (real-time collaboration)
  - Liveblocks (real-time updates)

**Installation**

1. **Install dependencies:**

```bash
cd miro-clone
npm install
```

2. **Set up environment variables:**

Create a `.env` file in the project root directory and add the necessary configuration details for your authentication service.

```plaintext
CLERK_FRONTEND_API_KEY=your_clerk_frontend_api_key
```

**Usage**

1. **Run the development server:**

```bash
npm run dev
```

2. **Access the application:**

Open your web browser and navigate to the provided URL (usually `http://localhost:3000`).

3. **Register or log in:**

Use the Clerk authentication service to register or log in to your account.

4. **Start collaborating:**

- Create a new whiteboard or join an existing one.
- Collaborate with other users in real-time.
- Utilize the drawing tools to express your ideas, add text, shapes, and more.

**Contributing**

Contributions from the community are welcome! If you'd like to be involved, please fork the repository and submit a pull request.

**License**

This project is licensed under the MIT License.



