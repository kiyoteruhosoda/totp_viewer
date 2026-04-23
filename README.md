# tools

A small collection of browser-based utility tools.

## Included tools

### 1) Mermaid Editor
- **Path:** `mermaid/mermaid-editor.html`
- Edit and render Mermaid diagrams in real time
- Zoom, pan, fit-to-view, and theme switching
- Export as SVG and copy as PNG

### 2) TOTP Viewer
- **Path:** `totp/totp_viewer.html`
- Generate RFC 6238 TOTP codes locally in the browser
- Read secrets from QR code, image, clipboard, or manual input
- Show/hide code, countdown display, and one-click copy

See also: `totp/README.md` for tool-specific details.

### 3) Flutter Builder Management
- **Path:** `flutter-builder/index.html`
- Manage build-related Azure endpoints from a single UI
- Check ACI status and logs, stop ACI, and trigger upload/build
- Save, import/export, and share configuration

## Usage

Open each HTML file directly in your browser, or host this repository as a static website.

## Deployment

This repository includes a GitHub Actions workflow for Azure Static Web Apps deployment:
`.github/workflows/azure-static-web-apps-yellow-coast-0cf4bc810.yml`

## License

MIT (`LICENSE`)
