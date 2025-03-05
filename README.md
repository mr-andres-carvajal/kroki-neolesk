# Kroki Niolesk

Run a [Kroki](https://kroki.io/) server and a [Niolesk](https://github.com/webgiss/niolesk) UI.

## Supported Diagram Engines

- ActDiag
- BlockDiag
- Bytefield
- D2
- Ditaa
- Erd
- GraphViz
- Nomnoml
- NwDiag
- Mermaid
- PacketDiag
- Pikchr
- PlantUML including C4 model
- RackDiag
- SeqDiag
- Structurizr
- Svgbob
- Symbolator
- UMlet
- Vega
- Vega-Lite
- WaveDrom
- WireViz

## Getting Started

### Launching Kroki & Neolesk

1. Podman Compose

   ```shell
   podman compose up -d
   ```

2. Navigate to [http://localhost:8017](http://localhost:8017)

### Markdown Kroki for VS Code

Render diagrams in markdown files using VS Code and Kroki

1. Install the [Kroki VS Code Extension](https://marketplace.visualstudio.com/items?itemName=pomdtr.markdown-kroki)
2. Configure the extension's `markdown-kroki.url` to be `http://localhost:8000`
