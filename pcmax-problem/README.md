# instances pcmax problem

## I780

Totaling 780 units, this set is made up of two distinct groups, each with 390 instances. The first group, called $\textit{U}$, contains the instances described by  França et al. (1994), while the second, identified as $\textit{NU}$, is formed by the instances proposed by Frangioni, Necciari, and Scutell`a (2004). The difference between the two is in the way the processing times of the tasks are obtained. In the $\textit{U}$ group, these values ​​are generated with a uniform distribution over a range $[a, b]$. In the group $\textit{NU}$, also with a uniform distribution, 98\% of the $p$ values ​​are generated with the interval $[(b-a) \cdot \lambda, b]$, with $\lambda$ equal to 0.9, while the other 2\% are generated with the range $[a, (b-a) \cdot \lambda]$, with $\lambda$ equal to 0.02.

In each group, there are three classes of instances with different $p$ ranges. For each class, there are thirteen pairs $(m, n)$, with $m$ equal to 5, 10, and 25, and $n$ equal to 10, 50, 100, 500, and 1000. Within each pair, there are ten instances of the same type. The value ranges [$a, b$] for each class are specified below:

    • C1: discrete uniform distribution of the interval [1, 100];
    • C2: discrete uniform distribution of the interval [1, 1000];
    • C3: discrete uniform distribution of the interval [1, 10000];

## I3500

All 3500 instances generated following with the characteristics described by paper Mrad, M. and Souayah, N. (2018). An arc-flow model for the makespan minimization problem on identical parallel machines. IEEE Access, 6:5300–5307.

These instances were divided into 5 groups {2.0, 2.25, 2.5, 2.75, 3.0}, taking into account the ratio between the amount of jobs n and machines m. Each group consists of seven C classes, and the processing times were generated according to the following distributions:

    • C1: uniform discrete distribution in the interval [1, 100]
    • C2: uniform discrete distribution in the interval [20, 100]
    • C3: uniform discrete distribution in the interval [50, 100]
    • C4: normal distribution with mean μ = 100 and standard deviation σ = 20
    • C5: normal distribution with mean μ = 100 and standard deviation σ = 50
    • C6: uniform discrete distribution in the interval [n, 4n]
    • C7: normal distribution with mean μ = 4n and standard deviation σ = n

In each class, 10 (n/m) pairs are included according to:

    • (n/m) ∈ {2.0, 2.5}, with n varying in {20, 40, 60, 80, 100, 120, 140, 160, 180, 200}
    • (n/m) ∈ {2.25, 3.0}, with n varying in {36, 54, 72, 90, 108, 126, 144, 162, 180, 198}
    • (n/m) ∈ {2.75}, with n varying in {22, 44, 66, 88, 110, 132, 154, 176, 198, 220}

## I1600

The set \texttt{I1600} is distributed into four distinct classes with the following $p$ intervals:

    • C1: discrete uniform distribution of the interval [1, 10000];
    • C2: discrete uniform distribution of the interval [10000, 20000];
    • C3: normal distribution with mean 10000 and standard deviation 2000;
    • C4: normal distribution with mean 10000 and standard deviation 5000.

The instances are also organized according to the ratio $\frac{n}{m}$ between the number of tasks and the number of machines, forming four groups: 2.25, 2.75, 3.25 and 3.75. For each class, ten instances with ten pairs $(n, m)$ are generated for the four groups mentioned below:

    • (n/m) ∈ {2.25} with n ∈ {54, 72, 90, 108, 126, 144, 162, 180, 198, 216}
    • (n/m) ∈ {2.75} with n ∈ {44, 66, 88, 110, 132, 154, 176, 198, 220, 242}
    • (n/m) ∈ {3.25} with n ∈ {52, 78, 104, 130, 156, 182, 208, 234, 260, 286}
    • (n/m) ∈ {3.75} with n ∈ {30, 60, 90, 120, 150, 180, 210, 240, 270, 300}
