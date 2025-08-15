# Educational SaaS App

This is a SaaS application that provides an educational platform for users to interact with AI "companions". Users can create their own companions, customize their knowledge base, and interact with them through a chat interface with voice capabilities.

## Features

*   **AI Companions:** Create and customize your own AI companions with unique personalities and knowledge bases.
*   **Voice Interaction:** Interact with your companions using your voice, powered by the Vapi SDK.
*   **User Authentication:** Secure user authentication and authorization powered by Supabase.
*   **Subscription Model:** The application is designed as a SaaS with a subscription model.
*   **Search and Filtering:** Easily find companions and filter them by subject.
*   **Modular and Reusable Components:** The frontend is built with reusable React components, making it easy to maintain and scale.
*   **Error Tracking:** Sentry is integrated for real-time error tracking and monitoring.

## Tech Stack

*   **Framework:** [Next.js](https://nextjs.org/)
*   **Language:** [TypeScript](https://www.typescriptlang.org/)
*   **Backend:** [Supabase](https://supabase.io/)
*   **Voice AI:** [Vapi](https://vapi.ai/)
*   **Styling:** [Tailwind CSS](https://tailwindcss.com/)
*   **UI Components:** [Shadcn UI](https://ui.shadcn.com/)
*   **Error Tracking:** [Sentry](https://sentry.io/)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

*   Node.js and npm (or pnpm/yarn) installed on your machine.
*   A Supabase account and a project set up.
*   A Vapi account and API keys.

### Installation

1.  Clone the repo
    ```sh
    git clone https://github.com/your_username_/project_name.git
    ```
2.  Install NPM packages
    ```sh
    npm install
    ```
3.  Set up your environment variables in a `.env.local` file. You will need to add your Supabase and Vapi credentials.
    ```
    NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
    NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
    VAPI_API_KEY=your_vapi_api_key
    ```
4.  Run the development server
    ```sh
    npm run dev
    ```

## Folder Structure

```
.
├── app/              # Main application code (pages, layouts, etc.)
├── components/       # Reusable React components
├── constants/        # Constants used throughout the application
├── lib/              # Helper functions and SDK configurations
├── public/           # Static assets (images, icons, etc.)
└── types/            # TypeScript type definitions
```

## License

Distributed under the MIT License. See `LICENSE` for more information.
