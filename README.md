### 1. Python execution command ###

python3 main10_1.py \
  --pcawg Datas/pcawg.rnaseq.transcript.expr.tpm.tsv.gz \
  --gtex Datas/GTEX_v4.pcawg.transcripts.tpm.tsv.gz \
  --ensgFile Datas/ensg_ensp_enst_ense_geneName_v75.tsv.gz \
  --canonFile Datas/canonEnsp_ensg_ensp_enst_geneName_v75.tsv.gz \
  --isoformIntFile Datas/interactionsInIsoforms_900_2.tsv.gz \
  --sequenceFile Datas/ensp_ensg_enst_sequence.tsv.gz \
  --redundantFile Datas/redundantENST_v75.txt \
  --minStringScore 900 \
  --minEnrichment 2.0 \
  --maxQvalue 0.01 \
  --minExpress 2.0 \
  --verbose \
| gzip > output_py/py_output_main10_1.tsv.gz

### 2. Information ###

- The Perl code has been translated verbatim.
- Its accuracy has been tested for each dataset.
- It is also located on the server in the required project folder (mdt_python_sena),
 along with the data. (You can find its location on the server with the necessary directions on the Wiki).

You can contact us for any questions or issues :)
