CODE ORANGE — GDM Clinic Showdown: Vercel-compatible interactive DEMO

This is the browser-only demo. It simulates votes and does not sync 28 students.

Deployment via Vercel CLI (from extracted folder):
1. Run: npx vercel login
2. Run: npx vercel --prod
3. Choose the Vercel team and new project when prompted.

Alternatively upload the files to a GitHub repository and import it from Vercel > Add New > Project.

For actual 28-player multiplayer on Vercel, migrate the local Python in-memory game state to a persistent shared data store and deploy serverless-compatible APIs. Do not publish the original local host token as a public credential.
