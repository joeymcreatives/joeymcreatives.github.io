# Joey M. | Creative Virtual Assistant

My portfolio website, hosted on GitHub Pages.

## How to update it

**Change my photo:** replace `images/joey.jpg` with a new square photo (same file name).

**Add or swap work samples:**
1. Upload the image to the `images/work` folder.
2. Open `index.html`, find the part that says `YOUR WORK SAMPLES`, and add a line like this:

   ```
   { image: "images/work/my-new-post.jpg", category: "graphics", caption: "Instagram post for a café" },
   ```

   The category can be `graphics`, `banners`, `blog` or `reels`.

**Change text:** open `index.html` and edit the words between the tags. Each section is marked with a comment like `<!-- ABOUT -->`.

After you commit a change, the live site updates in about a minute.
