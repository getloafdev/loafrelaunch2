# LOAF Fast Images + Out in the Wild

This build contains:

- Responsive WebP generation in the admin dashboard.
- Small, medium, and large image variants with browser `srcset` delivery.
- Public CDN delivery through the `loaf-fast` Supabase bucket.
- Admin-only writes and replacements.
- Sketchbooks placed first and emphasized as the origin of LOAF.
- A scroll-controlled typewriter hero that reverses as the user scrolls upward.
- A responsive, animated `LOAF Out in the Wild` gallery using slots `real1` to `real5`.
- Existing mobile configurator and cart fixes.

See `IMAGE_WORKFLOW.md` for the exact upload process.

The Supabase schema and bucket migrations in `supabase/fast_images_and_wild.sql` have already been applied to the connected project.
