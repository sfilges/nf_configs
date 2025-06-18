# Configuration files for nextflow pipelines

Basic config files for hyperscalers are located in the `cloud` folder. These
are generic templates which can be used as a basis for more workflow-optimized
configurations.

Config files for nfcore pipelines are located in `nfcore`and configs for
GPU optimized workflows are found under `nvidia`.

## Usage

When executing a pipeline, provide the config file with `-c`.

```bash
nextflow <pipeline> ... -c file.config
```