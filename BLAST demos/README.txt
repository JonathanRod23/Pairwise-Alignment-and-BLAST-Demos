BLAST & pairwise alignment demos
================================

Each file in this folder is a complete, self-contained web page. No internet
connection is needed and there are no other files to install. Double-click any
one of them and it opens in your browser.

Start with:  index.dc.html   (links to all ten)

   1 Sliding alignment.dc.html         slides 5-6
   2 Affine gap penalties.dc.html      slide 6
   3 Global vs local.dc.html           slide 11
   4 BLOSUM62 explorer.dc.html         slides 7-9
   5 Shuffle histogram.dc.html         slide 12
   6 E-value slider.dc.html            slides 15-16
   7 Where to draw the line.dc.html    slide 17
   8 Dynamic programming matrix.dc.html   slide 14
   9 Word size and seeding.dc.html      slides 18, 20
  10 Judge these hits.dc.html           slide 21

Pages 1-9 start animating on their own and all have a Pause button plus sliders
and buttons you can drive by hand. Page 10 is an exercise for students: they
judge five results before seeing the reasoning.

All ten reflow to fit narrower windows, so they work on a laptop as well as a
projector.


Linking them from PowerPoint
----------------------------

1. Keep this folder in the SAME folder as your .pptx file. Move them together,
   always, or the links will break.

2. In PowerPoint, select the shape or text you want to click (e.g. a small
   "Demo" label in the corner of the slide).

3. Insert > Link, then browse to the file in this folder and choose it.
   Before clicking OK, check the address field: it should read something like
   "BLAST demos/3 Global vs local.dc.html" rather than starting with C:\Users\...
   PowerPoint normally does this automatically when the file sits beside
   the presentation.

4. In presentation mode, clicking the link opens the demo in your browser.
   Alt-Tab (Windows) or Cmd-Tab (Mac) back to PowerPoint when you're done.

Tip: put the browser on the same display as the slides beforehand so you're not
dragging windows around mid-lecture.


Posting them on Canvas
----------------------

Uploading these to Canvas Files and linking them may work, but Canvas often
blocks JavaScript in uploaded files, so test one first. The reliable route is to
host the folder somewhere (GitHub Pages, or CSU web space) and link or embed the
URLs from a Canvas page.


A note on the content
---------------------

Sequences in demos 1, 2, 3, 8 and 9 are short synthetic examples chosen for
legibility. Demo 4 uses the real BLOSUM62 matrix. Database sizes in demo 6 are
orders of magnitude rather than current counts. The five results in demo 10 are
illustrative, not output from a real search.
