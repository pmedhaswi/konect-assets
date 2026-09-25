# Konect Image Assets

Public image files used by Konect Editorial Studio.

## Add or update images

1. Put files in `public/images/`.
2. Before automatic publishing works, grant Vercel's GitHub App access to this repository and link it to the Vercel project. After that, pushes to `main` deploy automatically.
3. Use the deployed site's `/images/<filename>` URL.
4. To show a new image in Konect, update the corresponding image URL in the site's content code after the asset is deployed.

Keep existing filenames when replacing an image to preserve its URL. For a distinct new image, use a new filename.
