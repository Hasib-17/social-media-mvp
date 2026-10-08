# Social Media MVP

A minimal social media application: users can sign up, post updates, follow others, and interact through likes and comments.

> **Status:** Early setup — no application code yet.

## Planned Features

- User sign-up / login
- User profiles
- Create, edit, and delete posts (text + images)
- Home feed of posts from followed users
- Follow / unfollow
- Likes and comments

## Tech Stack (proposed)

| Layer      | Choice                                   |
| ---------- | ---------------------------------------- |
| Framework  | Next.js (App Router) + TypeScript        |
| Styling    | Tailwind CSS + shadcn/ui                 |
| Database   | PostgreSQL + Drizzle ORM                 |
| Auth       | Clerk or Auth.js                         |
| Storage    | Vercel Blob (image uploads)              |
| Deployment | Vercel                                   |

## Getting Started

### Prerequisites

- Node.js 20.9 or newer
- npm (or pnpm / yarn)
- Git

### Installation

```bash
git clone git@github.com:Hasib-17/social-media-mvp.git
cd social-media-mvp
npm install
```

### Environment Variables

Copy the example file and fill in the values:

```bash
cp .env.example .env.local
```

### Run Locally

```bash
npm run dev
```

Then open http://localhost:3000.

## Project Structure

```
social-media-mvp/
├── app/          # Routes and pages
├── components/   # Reusable UI components
├── lib/          # Utilities, DB client, auth helpers
├── public/       # Static assets
└── README.md
```

## Contributing

1. Create a feature branch: `git checkout -b feature/my-feature`
2. Commit your changes: `git commit -m "Add my feature"`
3. Push the branch: `git push origin feature/my-feature`
4. Open a pull request

## License

MIT
# social-media-mvp
