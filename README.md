# Watch Size Comparison

Compare the case, display, straps, controls and side profiles of popular watches at a shared scale.

**Live site:** [watch.aktoriukas.com](https://watch.aktoriukas.com/)

The site is a standalone, dependency-free HTML page. It includes ten watches and lets you toggle individual models, compare their front outlines, and inspect their side profiles and published thicknesses. The visual contours are simplified illustrations; measurements and source links are shown on the page. Manufacturers may measure thickness differently, including whether a sensor bump is counted.

## Run locally

Serve the `public` directory with any static server, for example:

```sh
python3 -m http.server 8765 --directory public
```

Then open <http://localhost:8765/>.

## Contribute

Pull requests are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for measurement and source requirements. Changes to `main` require a pull request and approval from [@aktoriukas](https://github.com/aktoriukas).

## Deployment

The `public` directory is deployed by the existing Vercel project. The `main` branch publishes to the live domain; other branches and pull requests receive preview deployments.
