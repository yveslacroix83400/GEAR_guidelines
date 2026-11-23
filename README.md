# Practical Google ADK & Agentic AI Guide

A self-contained public course website covering agent concepts, Google ADK, VS Code setup, local execution, orchestration, Gemini API usage, secret handling, deployment and a glossary.

## Publish with GitHub Pages

1. Create a public GitHub repository.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will display the public URL after deployment.

## Local preview

Open `index.html` directly, or run:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Security

This website contains no API key. Never add keys to browser JavaScript or commit `.env` files. Use a protected backend such as Cloud Run for live Gemini calls.
