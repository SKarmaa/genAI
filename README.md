
# genAI

genAI is a generative UI component framework

It allows you to AI generate, iterate and preview on components.

- **genAI** makes use of open source component libraries and icons to build a library of assets for the generative pipeline.
- **genAI** highly modular and structured for elaborate generative processes.
- Component generation is a multipass pipeline.

---

# Currently Supported

* Frontend frameworks
  * React
  * Next.js
  * Svelte
* UI libraries
  * NextUI
  * Flowbite
  * Shadcn
* Icons libraries
  * Lucide

**genAI** makes it easier to integrate new frameworks, libraries and plugins.

Docs & guides on how to do so will be soon posted.

---

# Install

* Clone repo, run `npm i` in `server/`
* Unzip `server/library/icons/lucide/vectordb/index.zip` into that same folder
* Configure your OpenAI key in `server/.env`
* Web apps starter templates are in `webapps-starters/`
  * run `npm i` in the web app starter of your choice
  * make sure that `WEBAPP_ROOT` variable `server/.env` matches your webapp folder path
* Start the server with `node api.js` and the web app with `npm run dev`

---
