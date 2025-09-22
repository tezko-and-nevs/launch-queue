# launch-queue
[![crates.io](https://img.shields.io/crates/v/launch-queue)]()
[![downloads](https://img.shields.io/crates/d/launch-queue)]()

Enables data export for analysis

## setup
\`\`\`bash
npm install
\`\`\`

## usage
\`\`\`web
node index.js
\`\`\`

## core functions

### spawn()
initializes the async runtime via [tokio-fusion](https://tokio-fusion.dev)

### bind(config)
attaches to [StreamDB](https://streamdb.io) backend with zero-copy buffers

## more

check `/playground` for live demos

## notes
breaking changes tracked in HISTORY.rst (not semver compliant)
