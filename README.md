# accessibility-ai-demos

Demo pages created for my **AI-assisted accessibility testing** talk at **BrowserStack StackConnect Barcelona 2026**.

The demos explore what automated accessibility testing can detect — and where human judgment and assistive-technology testing still matter.

## Demos

### Demo 1 — Checkout

A checkout page containing intentionally introduced accessibility issues.

[Open Demo 1](https://ssamoustafa.github.io/accessibility-ai-demos/demo1-checkout.html)

### Demo 2 — Add to Basket

A product interaction designed to explore accessibility beyond what conventional automated checks can tell us.

[Open Demo 2](https://ssamoustafa.github.io/accessibility-ai-demos/demo2-basket.html)

## Run locally

```bash
git clone https://github.com/Ssamoustafa/accessibility-ai-demos.git
cd accessibility-ai-demos
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/demo1-checkout.html
http://localhost:8000/demo2-basket.html
```

## Note

These pages contain **intentional accessibility issues** for testing and demonstration purposes.

They are not intended as examples of production-ready accessible interfaces.
