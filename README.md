
## Project info

## How can I edit this code?

There are several ways of editing your application.
**Use your preferred IDE**
The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with .

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

This will launch the development server, likely at http://localhost:8080 (as configured in your vite.config.ts).

You'll need to have Node.js and npm installed on your machine. If you don't have them, you can install them via nvm (Node Version Manager) or download directly from the Node.js website.

For the Supabase authentication to work properly, you'll need to set up your environment variables. Create a .env file in the root of your project with your Supabase URL and anon key:

VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
You can find these values in your Supabase project dashboard under Project Settings > API.
