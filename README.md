# Topological-Data-Analysis
A collection of files relating to topological data analysis project.

## File Structure
Here is a basic overview of what each folder structure will look like:

KMEANS/
│
├── K_4/
│   ├── Delta_0.02/
│   │   ├── Geometry/
│   │   │   ├── Thickened_Clusters/
│   │   │   │   ├── cluster_1.csv
│   │   │   │   ├── cluster_2.csv
│   │   │   │   └── ...
│   │   │   │
│   │   │   ├── Intersections/
│   │   │   │   ├── Pairwise/
│   │   │   │   │   ├── cluster_1_2.csv
│   │   │   │   │   ├── cluster_1_3.csv
│   │   │   │   │   └── ...
│   │   │   │   └── Triple/        (optional / future use)
│   │   │   │
│   │   │   └── Statistics/
│   │   │       ├── geometry_stats.csv
│   │   │       ├── cluster_size_hist.png
│   │   │       └── intersection_hist.png
│   │   │
│   │   └── Betti_Computations/
│   │       ├── Local_Curves/
│   │       │   ├── cluster_1_curve.csv
│   │       │   ├── cluster_2_curve.csv
│   │       │   └── ...
│   │       │
│   │       ├── Intersection_Curves/
│   │       │   ├── pair_1_2_curve.csv
│   │       │   └── ...
│   │       │
│   │       ├── Inclusion_Exclusion_Result/
│   │       │   ├── approx_betti_curve.csv
│   │       │   └── approx_betti_plot.png
│   │       │
│   │       └── Error_Statistics/
│   │           ├── error_metrics.csv
│   │           └── error_plot.png
│   │
│   ├── Delta_0.04/
│   │   └── (same structure as above)
│   │
│   └── Stability_Analysis/
│       ├── recovery_indicator.csv
│       ├── stability_window.csv
│       └── stability_plot.png
│
├── K_6/
│   └── (same structure as K_4)
│
└── K_8/
    └── (same structure as K_4)
