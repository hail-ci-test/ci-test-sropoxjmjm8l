.. _GTEx_eQTL_allpairs_Brain_Hypothalamus:

GTEx_eQTL_allpairs_Brain_Hypothalamus
=====================================

*  **Versions:** v8
*  **Reference genome builds:** GRCh38
*  **Type:** :class:`hail.Table`

Schema (v8, GRCh38)
~~~~~~~~~~~~~~~~~~~

.. code-block:: text

    ----------------------------------------
    Global fields:
        'metadata': struct {
            name: str,
            version: str,
            reference_genome: str,
            n_rows: int32,
            n_partitions: int32
        }
    ----------------------------------------
    Row fields:
        'locus': locus<GRCh38>
        'alleles': array<str>
        'gene_id': str
        'variant_id': str
        'tss_distance': int32
        'ma_samples': int32
        'ma_count': int32
        'maf': float64
        'pval_nominal': float64
        'slope': float64
        'slope_se': float64
    ----------------------------------------
    Key: ['locus', 'alleles']
    ----------------------------------------
