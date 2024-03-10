## Mirofy

### Overview

Mirofy is a collaborative, real-time whiteboard application inspired by Miro, designed to facilitate seamless teamwork and idea visualization. It offers a comprehensive set of features including real-time database integration, a variety of drawing tools, and advanced collaboration capabilities.

### Key Features

- **Whiteboard Creation:** Start with a blank canvas and unleash your creativity.
- **Drawing Tools:** Utilize a range of tools including shapes (Rectangles and Ellipses), sticky notes, and freehand pencil drawing.
- **Toolbar:** Access a versatile toolbar containing Text, Shapes, Sticky Notes, and Pencil tools for easy navigation and manipulation.
- **Layering Functionality:** Organize your elements with layering capabilities for better management and visualization.
- **Coloring System:** Customize your creations with a rich palette of colors.
- **Undo & Redo Functionality:** Correct mistakes and refine your work with the ability to undo and redo actions.
- **Keyboard Shortcuts:** Speed up your workflow with convenient keyboard shortcuts.
- **Real-time Collaboration:** Collaborate with team members in real-time, allowing simultaneous editing and feedback.
- **Real-time Database:** Ensure data consistency and synchronization across all users with real-time database integration.
- **Authentication & Organization:** Securely access the platform with authentication features provided by Clerk, including organization and invitation functionalities.
- **Favoriting:** Mark important boards or elements for quick access with favoriting functionality.
- **Next.js 14 Framework:** Built on the latest Next.js framework, ensuring high performance and scalability.
- **Styling:** Enhanced with TailwindCSS & ShadcnUI styling for a sleek and modern user interface.

### Technologies Used

- **Frontend:**
  - Next.js
  - React
  - Tailwind CSS
- **Backend:**
  - Clerk (authentication)
- **Real-Time Collaboration:**
  - Convex (real-time collaboration)
  - Liveblocks (real-time updates)

### Installation

1. **Install dependencies:**

```bash
cd miro-clone
npm install
```

# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=dev # team: [your_team_name]

NEXT_PUBLIC_CONVEX_URL=replace_this_with_your_own_link
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=[user_clerk_publishable_key]
CLERK_SECRET_KEY=[user_clerk_secret_key]


### Usage

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

### Contributing

Contributions from the community are welcome! If you'd like to be involved, please fork the repository and submit a pull request.

### License

This project is licensed under the MIT License.
