# Motilal Nehru College (Evening) Voicebox

Anonymous complaint & suggestion box for the Motilal Nehru College (Evening)
Students' Union. Static frontend in `public/`, three serverless API routes in
`api/`, shared auth helper in `lib/`, and data stored in Upstash Redis.

- No login. No name. No trace.
- Optional photo (compressed in-browser, EXIF stripped).
- Optional contact info (visible only to the Union desk).
- Every submission gets a tracking code so the student can check replies.

## Deploy in under 10 minutes

1. **Push to GitHub**
   ```bash
   git init
   git add .
   git commit -m "mnc-voicebox"
   git branch -M main
   git remote add origin <your-repo-url>
   git push -u origin main