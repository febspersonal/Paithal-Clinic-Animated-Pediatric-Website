# Paithal Clinic — pastel pediatric website

A responsive static site inspired by the supplied reference. No npm dependencies, build command, API keys, or database required.

## Deploy to Vercel
1. Extract the ZIP. Upload the **contents** of the extracted folder (including `assets/`) to the root of a new GitHub repository.
2. In Vercel choose Add New → Project → Import your new repository.
3. Select **Other** as the framework preset. Root directory: repository root. Leave build command and output directory at their defaults (no build step; serve static files from root). Deploy.
4. Test the phone link, directions and date form on your live domain.

## Local preview
Open `index.html` or run `python -m http.server 8000` from the extracted directory and visit http://localhost:8000.

## Editing
- `index.html`: copy, services, phone, address, doctor credentials, timings and original repository photo URL.
- `styles.css`: colors, layout, animation and mobile breakpoints.
- `script.js`: interactive elements, mobile menu, appointment request preparation and motion preference.
- `assets/`: original vector illustrations and favicon. No downloaded font files.

## Important before publishing
Clinic content is based on https://github.com/febspersonal/PAITHALCLINIC/blob/main/src/App.tsx. Confirm the current contact details, qualifications and schedules with the clinic. The doctor's photo uses the original repository's Wix URL; the preview environment cannot fetch the external image, so verify it on the deployed site or replace it with an authorized local photograph. The illustrated brand mark is a new decorative mark, not the existing official clinic logo; substitute the official logo if desired.

The appointment tool prepares a copyable message locally and offers click-to-call. It does not transmit, store, schedule, or confirm appointments. No medical or personal information is requested. A live online booking system or WhatsApp integration would require confirmed destination and an appropriate privacy-aware implementation. No third-party analytics are included. The visitor may disable animations in the footer; reduced-motion preferences are respected.
