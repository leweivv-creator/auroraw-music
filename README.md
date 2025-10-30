# Aurora Band Highlights — Static One-Pager
Upload this ZIP directly to **Vercel** (Dashboard → Add New → Project → Upload). No build step.

## Replace content
- **Hero photo**: `/assets/photos/photo1.jpg` (vertical 4:5, ~1200x1500, JPG ≤ 300KB)
- **Video**: in `index.html`, replace `VIDEO_ID` with your YouTube ID (or swap the iframe with a `<video src="/assets/live-cut.mp4" controls>`).
- **Gallery**: replace `/assets/photos/photo2.jpg` … `photo12.jpg`.
- **Email**: replace `yourname@domain.com` in `index.html`.
- **Theme**: click BW/PG or use `?theme=bw` / `?theme=pink` in URL.

## If you see 404 on Vercel
This ZIP includes `vercel.json` that rewrites all routes to `/index.html`. Use **Upload** (not “Import Git Repository”) or set Framework to **Other** and Output Directory to `.`.

## URL
Name your project **auroraw-muse** → `https://auroraw-muse.vercel.app`.
