# gcp-cpu-comparison
Comparison of CPU instances @ GCP

| Where | Type | CPUS | GB Mem | Price (12-2020) | Coremark  | CPU / $ | Coremark / $ |
|-------|------|------|--------|-------|-----------|---------|--------------|
| GCP   | E2   | 32   | 32     | 0.792 |           | 40.4    |              |
| GCP   | E2   | 16   | 16     | 0.396 | 223,077   | 40.4    | 563326       |
| GCP   | N2   | 80   | 40     | 2.267 | 1,289,988 | 35.3    | 569029       |
| GCP   | N2D  | 224  | 224    | 5.591 | 3,565,048 | 40.1    | 637640       |
| GCP   | N2D  | 96   | 48     | 2.368 | 1,690,038 | 40.5    | **713698**   |
| GCP   | N1   | 96   | 86     | 2.499 | 1,245,251 | 38.4    | 498300       |
| GCP   | N1   | 96   | 86     | 2.383 | 1,245,251 | 40.3    | 522556       |
| GCP   | C2   | 60   | 240    | 2.506 | 1,142,234 | 23.9    | 455800       |
| AWS   | c5a.24xlarge | 96 |	192 |	3.696	| |	26.0	| |
| AWS	  | c6g.16xlarge | 64	| 128	| 2.176	|1252073.18 |	29.4 |	575401 |
