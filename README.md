Experiment 2 – Inventory
sold = min(q, n)

Experiment 3 – Cooling
Tc = Tr + (T0-Tr) * np.exp(-k*t)

Experiment 3 – Euler
Td.append(Td[-1] - k*(Td[-1]-Tr)*dt)

Experiment 4 – Vending
change = money - items[choice]

Experiment 5 – Poisson
poisson.pmf(x, lam)

Experiment 6 – Normal
norm.pdf(x, mu, sigma)

Experiment 6 – Exponential
lam * np.exp(-lam*x)

Experiment 7 – Queue
start = max(arrival[i], finish)

Experiment 7 – Queue
finish = start + service[i]

Experiment 8 – Chi-square
chi = sum((observed-expected)**2 / expected)

Experiment 9 – Exponential
lam = 1 / np.mean(data)

Experiment 9 – Chi-square
chi = np.sum((obs-exp)**2 / exp)

Experiment 10 – M/M/1
Wq = lam / (mu * (mu-lam))
