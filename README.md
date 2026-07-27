# Your site

## 1. Personalize it first
Open `index.html` and edit:
- The `<title>` tag and the "Natasha" heading if you want your full name.
- The footer links — replace `your.email@example.com`, the GitHub/LinkedIn URLs, and the ORCID placeholder (or delete any you don't want).
- Any project text under "Research" — tweak wording, statuses (`active`/`complete`/`joining`), or add a new `.entry` block for future work.
- The three placeholder rows in "Adventure" (search for `[Date]`) — swap in your real hikes and rides.

## How the interactive bits work
- The page is structured as five life-cycle phases (protostar → main sequence → red giant → planetary nebula → white dwarf), one per section: Origins, Research, Adventure, Community, Contact.
- A small canvas star in the top-right corner morphs color and size as you scroll, tracking whichever phase you're in — driven by the `PHASES` array near the bottom of the `<script>` tag if you want to retune the colors or sizes.
- The dot navigation on the right (desktop only) jumps to each section and highlights the active one.
- A thin progress bar across the very top tracks scroll position.

## 2. Put it on GitHub Pages (free hosting)
1. Create a new GitHub repo. For a site at `yourusername.github.io`, name the repo exactly `yourusername.github.io`. (Any other name works too — it'll just live at `yourusername.github.io/repo-name`.)
2. Upload `index.html` to the repo (drag-and-drop on github.com works, or `git push`).
3. Go to the repo's **Settings → Pages**, set the source branch to `main` and folder to `/ (root)`, save.
4. Give it a minute — your site will be live at the URL GitHub shows on that page.

That's it — no build step, it's a single static HTML file.
