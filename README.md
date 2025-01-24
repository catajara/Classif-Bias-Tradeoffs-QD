# Classif-Bias-Tradeoffs-QD

# CMA-ME and MAP-Elites Configuration Parameters

| **CMA-ME Parameters**          | Value                             |
|---------------------------------|-----------------------------------|
| Emitters                        | GaussianEmitter                  |
| Sigma                           | 0.1                              |
| Population Size                 | 16                               |
| x₀                              | Random with normal distribution  |

| **MAP-Elites Parameters**       | Value                             |
|---------------------------------|-----------------------------------|
| Number of Bins                  | [30, 30]                         |
| Behavior Dimensions             | 2                                |

| **Archive Parameters**          | Value                             |
|---------------------------------|-----------------------------------|
| Archive Type                    | GridArchive                      |
| Limits                          | [[0, 2], [0, 2]]                 |

| **Optimizer-Specific Parameters** | Value                          |
|-----------------------------------|--------------------------------|
| Selection Rule                    | mu                             |
| Restart Rule                      | Basic                          |
