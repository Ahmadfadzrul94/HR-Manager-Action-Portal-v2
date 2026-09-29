# HR Manager Action Portal v2

Single-file GitHub Pages prototype combining the stronger engineering approach from the Claude version with the stronger UX/dashboard features from the Gemini version.

## Features
- Manager and HR sign-in with demo PINs
- Manager case submission and editing
- HR case review and status updates
- Dashboard KPI cards
- Status and category visual summaries
- Search and multi-filter case queue
- Follow-up date and HR notes
- Case activity/audit trail
- CSV export
- JSON backup
- Responsive desktop/mobile UI
- No build process required

## Demo access
- Manager: Sarah Jenkins / `1234`
- Manager: David Ross / `1234`
- HR: HR Administrator / `9999`

## Deploy to GitHub Pages
1. Create a new repository.
2. Rename `HR_Manager_Action_Portal_v2.html` to `index.html`.
3. Put `index.html` in the repository root.
4. Commit and push.
5. GitHub → Settings → Pages → Deploy from a branch.
6. Select the main branch and `/root`.

## Important
This version stores data in browser localStorage. Different users/devices do not share the same cases. The PINs are client-side demo controls, not production authentication. Do not use confidential employee data for the static prototype.

For production, connect the UI to a proper backend/database and authentication layer such as Supabase, Firebase, or a company API.
