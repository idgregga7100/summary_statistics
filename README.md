# summary_statistics

#ran with GCST008058 data
./MetaXcan.py --model_db_path /home/isabelle/summary_stats/ALL_imputed_10_peer_3_pcs__v2.db --covariance /home/isabelle/summary_stats/ALL_nested_cv_all_covariances_10_peer_3pcs.txt.gz --gwas_folder /home/isabelle/summary_stats/GCST008058/ --gwas_file_pattern ".*gz" --snp_column RSID --effect_allele_column Allele1 --non_effect_allele_column Allele2 --beta_column Effect --pvalue_column P-value --output_file /home/isabelle/summary_stats/GCST008058/MESA_ALL.csv
