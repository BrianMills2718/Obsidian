---
tags: [observation-model, measurement, evidence]
---
# Causal Model vs Observation Model

Process tracing needs at least two linked generative models.

Causal model:
```text
X_t -> causal transition -> X_t+1
```
Observation/trace-production model:
```text
historical state/event -> record-production process -> surviving source -> researcher observation -> admitted evidence
```

A diary entry is normally evidence about a belief, not a cause of the decision the belief helped produce.

Candidate formalization:
```text
X_t+1 = f(X_t, A_t, U_t)
Z_t   = g(X_t, epsilon_t)
B_t+1 = Update(B_t, Z_t)
A_t   = pi(B_t, preferences_t, constraints_t)
E_t   = h(X_t, B_t, A_t, eta_t)
```
Researcher inference: `P(M, theta, X_0:T, B_0:T | E)`.