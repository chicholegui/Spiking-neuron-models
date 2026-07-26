# Spiking Neuron Models

Brain Modeling project — University of Pavia, 2026.

We extended two spiking neuron models from the lab: the Izhikevich model and the
FitzHugh-Nagumo model. The goal was to build a clean simulation framework around
both and run a series of experiments to study how single neurons behave under
different input conditions.

---

## What's inside

**Izhikevich notebook**
- Stimulus generators (step, ramp, pulse train, sinusoidal)
- Spike detection: spike times, ISI, firing rate, burst stats
- f-I curves for any parameter preset
- Phase-plane plots with nullclines and trajectories
- Side-by-side comparison of RS, IB, CH, FS, LTS and RZ firing patterns

**FitzHugh-Nagumo notebook**
- Equilibrium analysis: nullcline intersections, Jacobian, eigenvalue classification
- Hopf bifurcation detection and f-I characterization
- Adaptive integration via `scipy.solve_ivp` with time-varying input support
- Phase portraits across quiescent, spiking and depolarization-block regimes

**Report (PDF)**
Full writeup with methods, results and discussion.

---

## Stack

Python · NumPy · SciPy · Matplotlib · Jupyter

---

## Authors

Gabriel Leguizamón, Gala Miladinović, Mina Miladinović
