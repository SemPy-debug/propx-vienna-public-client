# PropX Vienna Workflow Public Client

PropX Vienna Workflow is a Windows client for an AI-assisted spatial data workflow focused on Vienna. It downloads public geospatial data, standardizes and cleans heterogeneous layers, assigns source-backed semantic labels, reconstructs simplified 3D building hulls, and opens 2D/3D/report views from one GUI.

## Download

Download the current Windows trial ZIP from the latest release:

[propx-evaluation-demo.zip](https://github.com/SemPy-debug/propx-vienna-public-client/releases/download/v0.1.0-public-trial/propx-evaluation-demo.zip)

Machine-readable release metadata is available in [`latest.json`](latest.json).

## Trial License

- Trial length: 7 days from the first successful online license check.
- Machine limit: 3 machine(s).
- License enforcement is hosted by PropX Render. Local Windows clock changes do not extend the trial.
- For a private demo key, renewal, more machines, or production access, contact [amvrazis.s@gmail.com](mailto:amvrazis.s@gmail.com).

## How To Run

1. Download and extract the ZIP to a writable folder, for example `C:\PropXVienna`.
2. Run `PropXViennaWorkflow\PropXViennaWorkflow.exe`.
3. Use the GUI to define the Vienna area, fetch live public data, run cleaning/semantic/3D generation, and inspect the viewer tabs.

Windows 10 or Windows 11 is enough. The package includes the application runtime and does not require Python or GIS libraries on the client PC.

## What Is Included

- Protected Windows client application.
- Workflow GUI for data acquisition, cleaning, semantic classes, 2D/3D visualization, QA, reports, and exports.
- `config/license.env` with only the public trial license and Render service URL.
- No Ollama, GitHub, or Render operator API keys.
- No pre-generated data outputs; the user runs the online workflow to fetch and build current results.

## Outputs

The workflow can produce standardized GeoJSON layers, semantic metadata, glTF/OBJ/3D Tiles exports, viewer HTML, QA reports, and pipeline manifests under the package `data` folder after the user runs the workflow.

## Updates

PropX checks the licensed Render endpoint for update metadata. The public release manifest is also available through `latest.json`.

## Support

Email: [amvrazis.s@gmail.com](mailto:amvrazis.s@gmail.com)
