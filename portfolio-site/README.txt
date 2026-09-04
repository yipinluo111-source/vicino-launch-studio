Rob Luo — Selected Video Work
=============================

STEP 1 — add the documentary file (one copy + rename)
-----------------------------------------------------
The Simon Sze documentary is the only file not included here: it is too
large to transfer into this folder automatically. Your original is already
web-ready (H.264 1080p, streams progressively), so it needs no conversion.

  1. Open  ~/Desktop/portfolio
  2. Copy the file starting with "#施敏 ..." into  portfolio-site/media/
  3. Rename the copy to exactly:   shi-min.mp4

That's it — index.html is already pointing at media/shi-min.mp4.

STEP 2 — preview
----------------
Double-click index.html. All five pieces should play.

STEP 3 — put it online (about 1 minute, free)
---------------------------------------------
  1. Go to  https://app.netlify.com/drop
  2. Drag this whole "portfolio-site" folder onto the page.
  3. You get a live URL immediately, e.g. https://something.netlify.app
  4. Claim it with a free account to rename the URL
     (Site settings -> Change site name) or point a domain at it.

Vercel works the same way: https://vercel.com/new -> drop the folder.

What's in here
--------------
  index.html                     the whole site (CSS inline, no build step)
  media/vicino-platform.mp4      Vicino AI - Platform Teaser     1:13
  media/vicino-3d.mp4            Vicino AI - Spatial Teaser      1:08
  media/shi-min.mp4              Simon Sze documentary  <-- YOU ADD THIS
  media/poster-*.jpg             poster frames

The two Vicino teasers were re-encoded to 720p H.264 for web playback --
the platform teaser was HEVC, which Chrome and Firefox will not play at all.
Your originals in ~/Desktop/portfolio are untouched.

Editing
-------
Everything lives in index.html. Each project is one <section class="piece">.
Reorder by moving the section; add a credit by adding a <span> inside that
section's <div class="tags">.
