# ion-somatic-variant-caller

An example run of the pipeline may look something like this:
```bash
nextflow run lifebit-ai/somatic-variant-caller --genome hg19 --samples s3://lifebit-featured-datasets/pipelines/gatk-somatic-data/samples.tsv --bed s3://lifebit-featured-datasets/pipelines/DeepVariant/quick_test/test_nist.b37_chr20_100kbp_at_10mb.bed
```

## Dependencies 
[Nextflow](https://www.nextflow.io/)
[Docker](https://www.docker.com/)
