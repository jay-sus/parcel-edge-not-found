# Parcel bug "Edge from X to Y not found!"

## Setup

```bash
npm ic
```

## Build

```bash
npm run build
```

### Output

```bash
> build
> parcel build

× Build failed.

@parcel/bundler-default: Edge from 7 to 8 not found!

  Error: Edge from 7 to 8 not found!
      at ContentGraph.removeEdge (D:\parcel-edge-not-found\node_modules\@parcel\graph\lib\Graph.js:156:13)
      at MutableBundleGraph.createBundleGroup
  (D:\parcel-edge-not-found\node_modules\@parcel\core\lib\public\MutableBundleGraph.js:134:24)
      at decorateLegacyGraph
  (D:\parcel-edge-not-found\node_modules\@parcel\bundler-default\lib\DefaultBundler.js:159:35)
      at Object.bundle (D:\parcel-edge-not-found\node_modules\@parcel\bundler-default\lib\DefaultBundler.js:126:7)
      at BundlerRunner.bundle
  (D:\parcel-edge-not-found\node_modules\@parcel\core\lib\requests\BundleGraphRequest.js:288:23)
      at process.processTicksAndRejections (node:internal/process/task_queues:95:5)
      at async Object.run (D:\parcel-edge-not-found\node_modules\@parcel\core\lib\requests\BundleGraphRequest.js:156:17)
      at async RequestTracker.runRequest
  (D:\parcel-edge-not-found\node_modules\@parcel\core\lib\RequestTracker.js:756:20)
      at async Object.run (D:\parcel-edge-not-found\node_modules\@parcel\core\lib\requests\ParcelBuildRequest.js:56:7)
      at async RequestTracker.runRequest
  (D:\parcel-edge-not-found\node_modules\@parcel\core\lib\RequestTracker.js:756:20)
```
