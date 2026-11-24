# Krita Wasm on GitHub Pages

Open [Krita Wasm](https://krita-port.github.io/) to run Krita in your browser. Download [`krita.bundle.tar.gz`](https://github.com/krita-port/krita-wasm/releases/download/latest/krita.bundle.tar.gz), then select or drop it into the page.

## Deployment

Set **Settings → Pages → Source** to **GitHub Actions**. A push to `main` or a manual run of the Pages workflow on `main` publishes the loader from the current [Krita Wasm Nightly build](https://github.com/krita-port/krita-wasm/releases/tag/latest). Run the workflow again when you want to update the hosted loader. The runtime bundle is downloaded separately from the Release.

## Licensing

The files in this repository are available under the [MIT License](LICENSE). The deployed loader and runtime come from [krita-wasm](https://github.com/krita-port/krita-wasm) and are distributed under their own licenses. The loader archive includes the application's GPL-3.0-only license in `COPYING`.
