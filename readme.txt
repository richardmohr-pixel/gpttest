# SAP Commerce Cloud OCC Endpoint Helper

Use this repository to keep short how-to notes for SAP Commerce Cloud customization work.

- [Creating a New OCC Endpoint](docs/occ-endpoint-guide.md)

## B2B Industrial Price Search Prototype

This prototype ships a static frontend and a lightweight Node.js backend-for-frontend that calls the OpenAI Chat Completions API and streams JSON data back to the UI.

### Quick start

1. (Optional) Update `config/custom.txt` with your OpenAI API key and preferred model.
2. Run `node server.js` (or `npm start`).
3. Open `http://localhost:3000` and run a query such as `robotic welding cell`.

If the API key is missing or the OpenAI call fails, the UI will render curated fallback data so that the interface remains functional for demos.
