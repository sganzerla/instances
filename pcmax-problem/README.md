# 3500

All 3500 instances generated following with the characteristics described by paper Mrad, M. and Souayah, N. (2018). An arc-flow model for the makespan minimization problem on identical parallel machines. IEEE Access, 6:5300–5307.

These instances were divided into 5 groups {2.0, 2.25, 2.5, 2.75, 3.0}, taking into account the ratio between the amount of jobs n and machines m. Each group consists of seven C classes, and the processing times were generated according to the following distributions:

    • C1: uniform discrete distribution in the interval {1, 100}
    • C2: uniform discrete distribution in the interval {20, 100}
    • C3: uniform discrete distribution in the interval {50, 100}
    • C4: normal distribution with mean μ = 100 and standard deviation σ = 20
    • C5: normal distribution with mean μ = 100 and standard deviation σ = 50
    • C6: uniform discrete distribution in the interval {n, 4n}
    • C7: normal distribution with mean μ = 4n and standard deviation σ = n

In each class, 10 (n/m) pairs are included according to:

    • (n/m) ∈ {2.0, 2.5}, with n varying in {20, 40, 60, 80, 100, 120, 140, 160, 180, 200}
    • (n/m) ∈ {2.25, 3.0}, with n varying in {36, 54, 72, 90, 108, 126, 144, 162, 180, 198}
    • (n/m) ∈ {2.75}, with n varying in {22, 44, 66, 88, 110, 132, 154, 176, 198, 220}
