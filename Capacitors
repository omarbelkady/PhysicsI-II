# Capacitor Theory and Analysis

## Capacitor Fundamentals

A capacitor is an essential passive electronic component designed to store electrical energy in an electric field. It consists of two conductive plates or surfaces separated by a dielectric material. When a voltage potential is applied across the conductors, an electric field develops across the dielectric, causing positive charge to accumulate on one plate and negative charge on the other.

The capacitance (C) of a capacitor is the ratio of the electric charge (q) on each conductor to the voltage (V) between them:

$C = \frac{q}{V}$

Capacitance is measured in farads (F), though practical capacitors typically use smaller units:
- Microfarad (μF): 10^-6 F
- Nanofarad (nF): 10^-9 F
- Picofarad (pF): 10^-12 F

For a parallel plate capacitor, the capacitance is given by:

$C = \varepsilon_0 \varepsilon_r \frac{A}{d}$

Where:
- $\varepsilon_0$ is the permittivity of free space (8.85 × 10^-12 F/m)
- $\varepsilon_r$ is the relative permittivity (dielectric constant) of the material
- A is the area of overlap between the plates
- d is the separation distance between plates

## Capacitor Configurations in Detail

### Series Configuration

When capacitors are connected in series (end-to-end), the equivalent capacitance is less than any individual capacitor in the circuit. This configuration is used when a higher voltage rating is needed than available from a single capacitor.

The mathematical formula for capacitors in series is:

$\frac{1}{C_{eq}} = \frac{1}{C_1} + \frac{1}{C_2} + \frac{1}{C_3} + ... + \frac{1}{C_n}$

For the special case of two capacitors in series:

$C_{eq} = \frac{C_1 \times C_2}{C_1 + C_2}$

For n identical capacitors each with capacitance C:

$C_{eq} = \frac{C}{n}$

#### Charge and Voltage Distribution in Series

In a series connection:
- The charge is the same on each capacitor: $q_1 = q_2 = q_3 = ... = q$
- This occurs because the charge on one plate induces an equal and opposite charge on the adjacent plate of the next capacitor
- The voltage divides across the capacitors according to their capacitances:
  $V_{total} = V_1 + V_2 + V_3 + ... + V_n$
- The voltage across each capacitor is inversely proportional to its capacitance:
  $V_i = \frac{q}{C_i}$
- For capacitors with equal capacitance, the voltage divides equally

In your notes example, for a series circuit:
- If the total charge is 135 nC across three equal capacitors
- Each capacitor holds the same charge: $q = \frac{135 \text{ nC}}{3} = 45 \text{ nC}$ per capacitor

### Parallel Configuration

When capacitors are connected in parallel (all positive terminals connected together and all negative terminals connected together), the equivalent capacitance is the sum of the individual capacitances.

The formula for capacitors in parallel is:

$C_{eq} = C_1 + C_2 + C_3 + ... + C_n$

#### Charge and Voltage Distribution in Parallel

In a parallel connection:
- All capacitors experience the same voltage: $V_1 = V_2 = V_3 = ... = V = V_{total}$
- The charges on each capacitor are proportional to their capacitances:
  $q_i = C_i \times V$
- The total charge is the sum of the individual charges:
  $q_{total} = q_1 + q_2 + q_3 + ... + q_n = (C_1 + C_2 + C_3 + ... + C_n) \times V = C_{eq} \times V$

For your example with a 5nF capacitor in a 12V circuit:
$q_5 = (5 \text{ nF})(12 \text{ V}) = 60 \text{ nC}$

## Capacitor Networks and Mixed Configurations

Many practical circuits contain both series and parallel combinations of capacitors. Analysis of these networks involves:

1. Identifying pure series or parallel subcircuits
2. Reducing these subcircuits to their equivalent capacitances
3. Continuing this process until the entire network is reduced to a single equivalent capacitor

For example, if capacitors C₁ and C₂ are in series, and this combination is in parallel with C₃:
- First find the equivalent capacitance of the series pair: $C_{12} = \frac{C_1 \times C_2}{C_1 + C_2}$
- Then find the total equivalent capacitance: $C_{eq} = C_{12} + C_3$

## Detailed Charge-Voltage Relationships

The fundamental relationship $q = CV$ has several important implications:

- The charge stored is directly proportional to both capacitance and voltage
- Doubling the voltage doubles the stored charge
- Doubling the capacitance doubles the stored charge at the same voltage
- The instantaneous voltage across a capacitor is $v(t) = \frac{1}{C}\int i(t)dt + V_0$
  Where $V_0$ is the initial voltage and $i(t)$ is the current flowing through the capacitor

### Charge Distribution Across Capacitor Networks

#### Series Networks
For a series network with different capacitance values, the voltage across each capacitor will vary, but the charge will remain constant:

$q = C_1 V_1 = C_2 V_2 = C_3 V_3 = ... = C_n V_n$

The voltage across each capacitor can be determined by:

$V_i = \frac{q}{C_i} = \frac{V_{total}}{C_i \times C_{eq, total}}$

#### Parallel Networks
For a parallel network, the voltage across each capacitor is the same, but the charge varies according to each capacitance:

$q_i = C_i \times V$

The proportion of total charge on each capacitor is:

$\frac{q_i}{q_{total}} = \frac{C_i}{C_{eq, total}}$

## Energy Storage Principles - Detailed Analysis

The energy stored in a capacitor can be derived from first principles. When a capacitor is charged, work must be done against the electric field to move charge from one plate to the other.

The detailed derivation is as follows:

To move a small charge element $dq'$ through a potential difference $V = \frac{q'}{C}$, the work required is:

$dW = V \times dq' = \frac{q'}{C} \times dq'$

The total work to charge a capacitor from 0 to a charge q is:

$W = \int_0^q \frac{q'}{C} dq' = \frac{1}{C}\int_0^q q' dq' = \frac{1}{C} \left[ \frac{q'^2}{2} \right]_0^q = \frac{q^2}{2C}$

This can be rewritten in terms of voltage using $q = CV$:

$W = \frac{(CV)^2}{2C} = \frac{C \times V^2}{2}$

Or in terms of charge and voltage:

$W = \frac{qV}{2}$

### Physical Meaning of Stored Energy

The energy stored in a capacitor resides in the electric field between the plates. The energy density (energy per unit volume) in the electric field is:

$u = \frac{1}{2}\varepsilon_0 \varepsilon_r E^2$

Where:
- $u$ is the energy density in J/m³
- $E$ is the electric field strength in V/m

For a parallel plate capacitor with uniform field:

$E = \frac{V}{d}$

The total energy is the energy density multiplied by the volume of the field:

$W = u \times Ad = \frac{1}{2}\varepsilon_0 \varepsilon_r E^2 \times Ad = \frac{1}{2}\varepsilon_0 \varepsilon_r \frac{V^2}{d^2} \times Ad = \frac{1}{2}\varepsilon_0 \varepsilon_r \frac{A}{d} \times V^2 = \frac{1}{2}CV^2$

This confirms our earlier derivation.

## Dielectrics and Their Effects - Advanced Theory

A dielectric is an insulating material that can be polarized by an applied electric field. When placed between capacitor plates, dielectrics increase capacitance and affect the electric field distribution.

### Dielectric Constant and Capacitance

The dielectric constant (relative permittivity, $\varepsilon_r$ or $k$) is a measure of how much a material increases capacitance compared to a vacuum:

$C = kC_{air} \approx kC_{vacuum}$

Where:
- $k$ is the dielectric constant
- $C_{air}$ is the capacitance with air between the plates
- For practical purposes, $\varepsilon_r$ of air is approximately 1.0006, so $C_{air} \approx C_{vacuum}$

The dielectric constant can be calculated from measured capacitances:

$k = \frac{C}{C_{air}}$

Common dielectric materials and their approximate constants:
- Vacuum: 1.0 (by definition)
- Air: 1.0006
- Paper: 2.5-3.5
- Glass: 4-10
- Ceramic: 20-15,000
- Water: 80

### Molecular Explanation of Dielectric Behavior

Dielectrics work through two main mechanisms:
1. **Electronic polarization**: The electron cloud around atoms shifts slightly in response to the electric field
2. **Orientational polarization**: For polar molecules (like water), existing dipoles align with the applied field

This polarization creates an opposing internal electric field that reduces the net field across the dielectric:

$E_{net} = E_{applied} - E_{polarization} = \frac{E_{applied}}{k}$

### Effect on Electric Field and Voltage

With a dielectric present, the relationship between electric field and voltage becomes:

$E = \frac{V}{d} \times \frac{1}{k}$

The voltage across a capacitor with dielectric:

$\Delta V = Ed = \frac{Ed}{k}$

### Dielectric Strength and Breakdown

Every dielectric material has a maximum electric field it can withstand, called the dielectric strength (measured in V/m). If the electric field exceeds this value, the dielectric experiences breakdown—it becomes conductive and can be permanently damaged.

As noted in your handwritten notes: "if you are increasing the electric field more than capacitance it will explode"

This refers to dielectric breakdown, where:
- If voltage increases beyond what the dielectric can handle ($E > E_{breakdown}$)
- The dielectric fails, becoming conductive
- This can result in catastrophic failure ("explosion") of the capacitor

The maximum voltage a capacitor can handle is determined by:

$V_{max} = E_{breakdown} \times d$

### Insertion of Dielectric - Different Scenarios

There are two important cases to consider when a dielectric is inserted into a capacitor:

1. **Constant Voltage (Battery Connected)**
   - Capacitance increases: $C_{new} = kC_{old}$
   - Charge increases: $q_{new} = kq_{old}$
   - Electric field decreases: $E_{new} = \frac{E_{old}}{k}$
   - Energy increases: $W_{new} = kW_{old}$

2. **Isolated Capacitor (Constant Charge)**
   - Capacitance increases: $C_{new} = kC_{old}$
   - Voltage decreases: $V_{new} = \frac{V_{old}}{k}$
   - Electric field decreases: $E_{new} = \frac{E_{old}}{k}$
   - Energy decreases: $W_{new} = \frac{W_{old}}{k}$

## Transient Response and Time-Dependent Behavior

When a capacitor is connected to a voltage source through a resistor (RC circuit), it doesn't charge or discharge instantaneously but follows an exponential pattern.

### Charging Process

For a capacitor charging through a resistor:

$V_C(t) = V_S(1 - e^{-t/RC})$

Where:
- $V_C(t)$ is the capacitor voltage at time t
- $V_S$ is the source voltage
- R is the resistance
- C is the capacitance
- $\tau = RC$ is the time constant

The current during charging is:

$I(t) = \frac{V_S}{R}e^{-t/RC}$

### Discharging Process

For a capacitor discharging through a resistor:

$V_C(t) = V_0 e^{-t/RC}$

Where $V_0$ is the initial voltage on the capacitor.

The current during discharging is:

$I(t) = -\frac{V_0}{R}e^{-t/RC}$

After one time constant ($t = RC$), the capacitor charges to approximately 63.2% of the final voltage or discharges to approximately 36.8% of the initial voltage.
