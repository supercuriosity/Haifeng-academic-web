---
title: 'Fast and Feasible: Agile Unicycle Motion Planning via Convex Inner Approximation'

authors:
  - Jingxuan Tang
  - Haifeng Sun
  - Wang Xi
  - Jianping He

date: '2026-09-17T00:00:00Z'
publishDate: '2026-09-17T00:00:00Z'

publication_types: ['paper-conference']
publication: ''
publication_short: ''

abstract: >-
  Agile navigation for unicycle-type robots demands a rigorous treatment of
  nonholonomic kinematics and actuator limits. However, reconciling the
  non-convex angular velocity constraints with the requirement for
  high-frequency control remains a computational and accuracy bottleneck.
  Existing Nonlinear Model Predictive Control (NMPC) solvers offer physical
  fidelity but often falter in real-time performance, while mainstream
  approaches like linearized approximations risk dynamical infeasibility
  during aggressive maneuvers. To bridge this gap, this paper proposes a fast
  and feasible motion planning framework. Our core insight is to reformulate
  the heading-change bound as bilinear inequalities exploiting its geometric
  structure, decomposing it into a convex-concave form that enables a strictly
  feasible convex approximation. By iteratively solving a sequence of standard
  Second-Order Cone Programs (SOCPs), our method guarantees anytime feasibility
  and monotonic convergence without sacrificing physical consistency.
  Numerical validations demonstrate that the proposed planner achieves
  NMPC-level solution quality with millisecond-level computation times,
  outperforming the baseline approaches in agile scenarios.
summary: A fast and feasible motion planner for agile unicycle robots based on convex inner approximation.

tags:
  - Motion Planning
  - Convex Optimization
  - Unicycle Robots

featured: true

url_pdf: ''
url_code: 'https://github.com/serendipitjx/unicycle'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: ''
  focal_point: 'Center'
  preview_only: false

projects: []

slides: ''
---
