If recloning from `ksudoh/IWSLT2022_simul_s2t_baseline_enja`,
- change `--vocab-size-asr 8192` in `10-preprocess.sh` to `--vocab-size-asr {vocab_size_asr}`
- add `vocab_size_asr` to `/scripts/09-var-en-ja.sh` and set it to 4671
- change `vocab_size_st` in `/scripts/09-var-en-ja.sh` to 11805

because we use less data.
