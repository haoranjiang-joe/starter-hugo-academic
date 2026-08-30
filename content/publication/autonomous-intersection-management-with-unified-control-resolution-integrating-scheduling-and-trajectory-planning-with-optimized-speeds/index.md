---
title: "Autonomous intersection management with unified control resolution:
  integrating scheduling and trajectory planning with optimized speeds"
publication_types:
  - "2"
authors:
  - admin
  - Guosheng Xiao
  - Yingying Zhao
  - Caiwen Luo
  - Yangsheng Jiang
  - Zhihong Yao
author_notes:
  - ""
  - ""
  - ""
  - ""
  - ""
  - Corresponding Author
publication: "*Transportation Research Part C: Emerging Technologies*"
abstract: Autonomous intersection management (AIM) coordinates connected and automated vehicles to traverse intersections safely and efficiently without traffic signals. Sequential two-stage frameworks, which decompose AIM into timing schedule optimization and trajectory planning, are widely adopted for their interpretability and balance between coordination performance and computational complexity. However, they can suffer from a critical mismatch in control resolution. When the scheduling and trajectory-control layers operate on incompatible time grids, projecting scheduled entry times onto the execution grid may induce trajectory infeasibility or safety degradation. In addition, many scheduling models assume a preset in-intersection speed, which restricts the solution space and can limit coordination efficiency. To address these issues, this paper proposes an improved two-stage AIM framework based on a unified control resolution. A Continuous-Speed (CS) scheduling model is developed by treating both vehicle entry times and in-intersection speeds as decision variables, and a Discrete-Speed (DS) reformulation is further derived by introducing a finite set of candidate speeds to improve computational tractability. By aligning the scheduling time grid with the trajectory-control grid, the proposed framework guarantees that high-level schedules are perfectly translatable to low-level feasible trajectories, eliminating the risk of projection-induced collisions. Simulation results further demonstrate that relaxing the preset-speed assumption improves traffic efficiency. Compared with the preset-speed baseline, the CS model reduces average vehicle delay by nearly 25% in complex high-demand scenarios, while the DS model achieves up to 20% delay reduction with better computational efficiency. Mechanism analysis shows that these gains arise from two speed-enabled effects: passage-sequence reordering among conflicting vehicles and micro-delay absorption through adjustments to travel times from intersection entry to conflict zone. Benchmark comparisons with representative AIM approaches indicate that the proposed method achieves a more favorable trade-off across traffic efficiency, fuel consumption, and computational cost.
draft: false
url_pdf: https://www.sciencedirect.com/science/article/pii/S0968090X26004675
featured: true
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2026-08-30T03:23:17.038Z
---
