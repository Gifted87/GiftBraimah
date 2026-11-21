# Gift Braimah — Portfolio

A responsive, multi-page personal portfolio for Gift Braimah. The site presents professional experience, selected projects, technical skills, writing, and background through a custom-designed static website.

## Pages

- `index.html` — portfolio landing page
- `about.html` — background and profile
- `experience.html` — professional experience
- `portfolio.html` — selected work
- `skills.html` — skills and tools
- `writing.html` — essays and writing
- `acms.html`, `autonomous-cognitive-network.html`, `cognitive-spatial-fabric.html`, `cognitive-substrate.html`, `obsidian-paradigm.html`, `sovereign-engineer.html`, and `the-genesis-machine.html` — project and concept pages

## Run locally

The site is static HTML and does not require a build step or package installation. Open `index.html` in a browser, or serve the folder over HTTP:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Deployment

The included `vercel.json` configures clean URLs and disables trailing slashes. Deploy the repository as a static site on Vercel with the repository root as the project root; no build command is required.

## License

No license file is currently included. All rights remain with the author unless a license is added.
