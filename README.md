# Karam AI — Customer Demo Pages

Static demo pages for customers to test the Karam AI chat widget. Hosted via GitHub Pages.

## Creating a new demo

1. Create a folder for the customer: `mkdir <customer-slug>/`
2. Copy the template: `cp _template.html <customer-slug>/index.html`
3. Edit the new file:
   - Replace `COMPANY_NAME` with the customer's name
   - Replace `TENANT_ID_HERE` with their tenant ID
   - Adjust CSS variables for branding if needed
4. Commit and push to `main`
5. Demo will be live at: `https://karam-ai-com.github.io/demos/<customer-slug>/`

## Active demos

| Customer | Tenant ID | URL |
|----------|-----------|-----|
| Perfection Point | `68ece661-e309-4a80-9352-f3b8f058fda1` | [/perfectionholding/](https://karam-ai-com.github.io/demos/perfectionholding/) |

## Structure

```
demos/
├── _template.html          # Base template for new demos
├── perfectionholding/
│   └── index.html          # Perfection Point demo
└── README.md
```
