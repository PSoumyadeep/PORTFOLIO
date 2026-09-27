HOW TO APPLY THIS UPDATE TO YOUR LIVE PORTFOLIO (PSoumyadeep/PORTFOLIO)
========================================================================

This folder contains the updated files for your GitHub Pages portfolio.

FILES INCLUDED:
  index.html                                  -> replaces your existing index.html
  assets/projects/solutionforge-poster.jpg    -> new (video thumbnail)
  assets/videos/solutionforge.mp4             -> new (full prototype demo, used in the modal)
  assets/videos/solutionforge-preview.mp4     -> new (short muted loop, used on the card hover)

FILES TO DELETE FROM YOUR REPO (no longer used):
  assets/videos/agentic-ai.mp4
  assets/projects/agentic-ai-poster.jpg

STEPS:
  1. Clone your repo locally if you don't already have it:
       git clone https://github.com/PSoumyadeep/PORTFOLIO.git
  2. Copy the files above into the repo, overwriting index.html.
  3. Delete the two old agentic-ai.* files listed above.
  4. Commit and push:
       git add -A
       git commit -m "Add SolutionForge AI project + GDG certificate, enhance writeups"
       git push
  5. GitHub Pages will redeploy automatically in ~1 minute.

WHAT CHANGED:
  - Project card #2 renamed from generic "Agentic AI System" to "SolutionForge AI",
    now using your real prototype video, correct tags (CrewAI, Multi-Agent System,
    FastAPI, Python), and a proper writeup describing the 4-agent pipeline
    (Business Analyst, Solution Architect, Technology Advisor, Delivery Planner)
    and your specific contribution (Delivery Planner agent + blueprint HTML export).
  - Added a "Live Demo" button in the project modal (shows for SolutionForge AI and
    AI Home Tutor, hidden for Iris since it has no live deployment).
  - Added a 5th certification card for your GDG "Technical Domain Lead" certificate
    (linked to your Drive PDF), with a clean GDG-colored placeholder thumbnail since
    no certificate image file was available to embed directly.
  - Enhanced the AI Home Tutor and Iris Biometric Authentication writeups with more
    specific, technical detail.
