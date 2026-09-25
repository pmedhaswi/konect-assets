# Konect Image Assets

Public image files used by Konect Editorial Studio.

## Add or update images

1. Put files in `public/images/`.
2. Commit or push the change to `main`; Vercel deploys connected GitHub pushes automatically.
3. Use the deployed site's `/images/<filename>` URL.
4. To show a new image in Konect, add its URL to `artifacts/konect/src/data/image-assets.ts` or the relevant content data.

Keep existing filenames when replacing an image to preserve its URL. For a distinct new image, use a new filename.
