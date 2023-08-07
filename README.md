# w266_final_project

There is a typo in the results table. The last test for PCA embeddings was fed to a KNN NCD model using gzip compression, not zstandard.

Zstandard was tested in the raw text trial and had inferior performance hence we test PCA embeddings in KNN NCD models using gzip compression.
