# UCP — Unique Character Parser

A tiny single-file tool that extracts every unique character from pasted text.
Uppercase and lowercase are treated as different characters, and spaces,
digits, and symbols are all included.

## How to use

1. Paste your text into the top box.
2. Click **Parse**.
3. The bottom box shows every unique character found, with a count.
4. Click **Copy** to copy the result to your clipboard.

## Deploy on GitHub Pages

1. Create a new GitHub repo (or use an existing one).
2. Add `index.html` to the root of the repo.
3. Go to **Settings → Pages**, set the source branch to `main` and the folder to `/root`.
4. Your tool will be live at `https://<your-username>.github.io/<repo-name>/`.

That's it — no build step, no dependencies.

## License

MIT