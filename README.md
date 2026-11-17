# LLM Pipe Explorer

An interactive, buildless HTML dashboard for exploring how an LLM request moves through a pipeline.

## Run locally

```bash
python3 -m http.server 4173
```

Then open [http://localhost:4173](http://localhost:4173).

## Included interactions

- Switch between three example pipelines.
- Click graph nodes to inspect inputs, outputs, configuration, and latency.
- Run a simulated trace with animated node states and a replay log.
- Zoom the graph and export the active pipeline as JSON.
- Responsive layout for narrower screens.

The demo uses sample data only; no API key or backend is required.
