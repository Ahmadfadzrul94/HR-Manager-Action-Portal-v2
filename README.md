# HR Action Hub

A single-file GitHub Pages prototype for manager and HR employee development/performance case management.

## V3 interface
- Logistics-tech inspired red / charcoal / white visual system
- Manager and HR sign-in
- KPI dashboard
- Case status workflow
- Search and filters
- Manager case submission/editing
- HR review, follow-up date and official notes
- Activity/audit trail
- CSV export
- JSON backup
- Responsive mobile/desktop UI
- HR Assist AI-style FAQ and portal guide chatbox
- Controlled FAQ knowledge base that is safe for static GitHub Pages
- No external UI framework or asset dependency

## Demo access
- Sarah Jenkins (Manager) — `1234`
- David Ross (Manager) — `1234`
- HR Administrator (HR) — `9999`

## GitHub Pages
Keep exactly these files in the repository root:

    index.html
    README.md

Then enable:
Settings → Pages → Deploy from a branch → `main` → `/ (root)`.

## Important limitation
This is a static prototype. Cases are stored in the browser's localStorage, so different devices/users do not share the same database. The PINs are client-side demo controls and are not production authentication.

For real HR use, connect the UI to a proper backend/database and authentication layer.


## HR Assist

The floating **HR Assist** chatbox provides guided answers for portal FAQs and process guidance.

The current GitHub Pages version uses a controlled knowledge base in the browser. It does **not** expose an AI API key.

For a true generative AI assistant, connect the chat UI to a secure backend/API proxy. Never put an OpenAI, Gemini or other provider secret key directly into `index.html`.
