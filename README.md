# JV Automotive

A responsive static website for JV Automotive, focused on custom CNC-turned and lathe-turned automotive components.

## Pages

- `index.html` — company overview, component families, process, and applications
- `products.html` — example component categories and material options for discussion
- `about.html` — company and manufacturing approach
- `contact.html` — phone, email, and New Delhi address

## Run from VS Code

Open the **Run and Debug** panel and select **Run website in Edge**, then press **F5**. VS Code starts a local server and opens `http://localhost:8000`. Stop the server by terminating the debug session.

Python must be installed and available as `python` on your PATH. If port 8000 is already in use, stop the other server before launching.

## Preview locally

Open `index.html` directly, or run a local static server from the project directory:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

The site has no build step or external JavaScript dependencies. Workshop photos currently load from Unsplash; replace them with company-owned or properly licensed images before publishing.
