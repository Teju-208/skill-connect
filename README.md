# SkillBridge – AI Career Intelligence Platform

SkillBridge is a role-based academia–industry career platform built with HTML/CSS/JavaScript, Node.js/Express and SQLite. It includes student, faculty, university and industry pages.

## AI features
- Resume NLP skill extraction from PDF/TXT resumes
- Career-specific skill-gap analysis
- Explainable career readiness score
- AI-ranked learning recommendations
- AI-ranked internship/job matching with matched and missing skills

## Run locally
1. Install Node.js LTS.
2. Open a terminal in this folder.
3. Run `npm install`.
4. Run `npm start`.
5. Open `http://localhost:3000`.

The frontend uses relative `/api/...` URLs, so the same code works locally and after deployment behind the same web server.

## Resume
On Profile, upload a readable PDF or TXT resume (max 5 MB) and click **Analyze Resume with NLP**. Detected skills are stored in SQLite and used by the AI career analysis.

## Important
The AI engine in this prototype is a transparent, local NLP/ranking engine. It does not claim to be a trained generative model. Its career requirements, skill normalization, gap calculation and matching rules are visible in `server.js` and can later be replaced or augmented by a trained ML/API model.
