# MATLAB Sinc Function Plot 📈

This repository demonstrates how to plot the **Sinc function** using MATLAB’s built-in `sinc()` function.

---

## 🧠 Overview

The Sinc function is widely used in **signal processing** and **communications**.  
In MATLAB, the built-in `sinc(t)` function computes:

\[
\text{sinc}(t) = \frac{\sin(\pi t)}{\pi t}
\]

This script generates and visualizes the Sinc function over a specified range.

---

## 💻 MATLAB Code

```matlab
clc; clear; close all;

% Define range
t = -10:0.01:10;

% Use MATLAB built-in sinc function
y = sinc(t);

% Plot
plot(t, y, 'LineWidth', 2);
grid on;

% Labels
xlabel('t');
ylabel('sinc(t)');
title('Sinc Function using MATLAB built-in sinc()');
