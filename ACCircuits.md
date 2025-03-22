# Alternating Current (AC) Circuits

## AC Voltage and Current

$$
V = V_0\sin(\omega t)
$$

### Notes:
- AC signals vary sinusoidally with time.

### Example Problem 1:
An AC voltage source has a peak voltage of $ 170 \, \text{V} $. What is the RMS voltage?

**Solution:**

$$
V_{rms} = \frac{V_0}{\sqrt{2}} = \frac{170}{\sqrt{2}} \approx 120 \, \text{V}
$$

---

## Reactance
- Inductive reactance: $ X_L = \omega L $
- Capacitive reactance: $ X_C = \frac{1}{\omega C} $

### Notes:
- Reactance opposes current flow in AC circuits.

### Example Problem 2:
A capacitor with $ C = 10 \, \mu\text{F} $ is in an AC circuit with frequency $ f = 60 \, \text{Hz} $. What is its capacitive reactance?

**Solution:**

$$
X_C = \frac{1}{\omega C}, \quad \omega = 2\pi f
$$

$$
X_C = \frac{1}{(2\pi(60))(10 \times 10^{-6})} \approx 265.3 \, \Omega
$$

---

## Impedance
$$
Z = \sqrt{R^2 + (X_L - X_C)^2} 
$$

### Notes:
- Impedance combines resistance and reactance in AC circuits.

### Example Problem 3:
A circuit has $ R = 50 \, \Omega $, $ X_L = 80 \, \Omega $, and $ X_C = 30 \, \Omega $. What is the impedance?

**Solution:**

$$
Z = \sqrt{R^2 + (X_L - X_C)^2} = \sqrt{50^2 + (80 - 30)^2}
$$

$$
Z = \sqrt{2500 + 2500} = \sqrt{5000} \approx 70.7 \, \Omega
$$


# Energy in AC Circuits

## Key Notes
- In AC circuits, energy is transferred through resistors, capacitors, and inductors.
- Average power dissipated in a resistor:

$$
P_{\text{avg}} = I_{\text{rms}}V_{\text{rms}} = I_{\text{rms}}^2R = \frac{V_{\text{rms}}^2}{R}
$$
  
- Reactive components (capacitors and inductors) store and release energy without dissipating it.

---

## Connection to Work and Energy
- Resistors convert electrical energy into heat (work).
- Capacitors and inductors temporarily store energy in electric and magnetic fields, respectively.

---

### Example Problem: Average Power in a Resistor
- An AC circuit has a resistor
$$ R = 10 \, \Omega $ with $ I_{\text{rms}} = 2 \, \text{A} $. What is the average power dissipated?

**Solution:**

$$
P_{\text{avg}} = I_{\text{rms}}^2R = (2)^2(10) = 40 \, \text{W}
$$

---

### Real-World Application:
- Household appliances: Operate on AC power, converting electrical energy into useful work.
- Power factor correction: Improves efficiency by reducing reactive power.
