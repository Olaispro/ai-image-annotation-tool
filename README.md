# AI Image Annotation Workbench

> A lightweight browser interface for drawing and exporting image boxes.

A local annotation workbench that loads an image, draws editable rectangles, assigns classes, and exports normalized YOLO labels plus a COCO-style JSON file. All processing stays in the browser.

## Why this project

This project reflects portfolio interests in AI operations, careful evaluation, annotation quality, and reproducible data workflows. It is a personal demonstration built from synthetic or sample data; it does not represent client work or measured professional outcomes.

## Quick start

Open `index.html` in a modern browser. Select a local image; drawing and exports happen in your browser.

## Repository contents

- `src/` contains the core implementation.
- `data/` contains small illustrative fixtures where applicable.
- Outputs are generated locally and are not checked in.

## Method and interpretation

The implementation favors readable baselines and explicit assumptions. Scores from demonstration data are not general performance estimates. Human review remains necessary for semantic correctness, evidence quality, and policy or safety judgments.

## Limitations

- Included records are synthetic or illustrative and are not client data.
- No production deployment, external model API, or independently validated result is claimed.
- Review the assumptions and adapt the workflow before using it on consequential data.

## License

MIT. See [LICENSE](LICENSE).
