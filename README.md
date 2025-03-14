# Full Stack AI Career Coach with Next JS, Neon DB, Tailwind, Prisma, Inngest, Shadcn UI 

### Make sure to create a `.env` file with following variables -

```
DATABASE_URL= you can use neon to create free postgres instance

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY= clerk is used for user auth
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY= add you gemini key, if you wish to use other LLM theen do change the file lib\inngest\function.js
```

Inngest is used for the management of the weekly cron