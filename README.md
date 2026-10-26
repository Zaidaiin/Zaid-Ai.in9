# Zaid AI — 60-second duration starter

This is a static frontend demo for Zaid AI. It has Hindi/English UI, text prompt, image upload preview, and duration choices up to 60 seconds.

Important: The frontend does not generate real videos yet. The Generate button honestly reports that a backend/model is not connected. A 60-second dropdown does not make an AI model capable of generating 60 seconds in one request. It may require several short clips and video stitching.

## Publish from Android for free (temporary URL)
1. Download and extract this ZIP on Android.
2. Sign in at https://github.com/
3. Create a public repository named `zaid-ai`.
4. Upload `index.html` to the repository root (do not upload the ZIP as the only file).
5. Open Settings → Pages. Choose “Deploy from a branch”, branch `main`, folder `/ (root)`, and save.
6. Wait for GitHub Pages to publish your site. It will use `https://YOUR-USERNAME.github.io/zaid-ai/`.

## Custom domain zaidai.in
A custom `.in` domain usually must be registered and paid for unless you already own it. GitHub Pages can use custom domains on supported plans; follow GitHub Pages settings and DNS instructions. Never enter domain registrar credentials in a public repository.

## Real AI video generation
Connect a legitimate inference service or self-host a model in a server-side backend. Keep API secrets off the frontend. Verify model licensing, current quotas, and whether commercial/public use is permitted. Free hosting does not provide unlimited free GPU compute.
