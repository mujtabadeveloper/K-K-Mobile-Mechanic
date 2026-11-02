# K & K Mobile Mechanic

Responsive static website. All website images are included.

## Deploy with GitHub and Vercel
1. Extract the ZIP.
2. Upload the extracted files to the root of a GitHub repository.
3. Import the repository in Vercel.
4. Framework preset: Other. Leave the build command empty; output directory: .
5. Deploy.

## Local preview
Run `python -m http.server 8000` from this folder and open http://localhost:8000.

## Editing
- index.html: content and links
- style.css: layout, branding and responsive styling
- app.js: navigation, animations and service request preparation
- assets/: included logo and photos

The service form prepares a message to copy into Facebook Messenger. It does not submit bookings to a backend.
Fonts load from Google Fonts with local fallback fonts.
