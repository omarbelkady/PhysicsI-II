# Projectile Motion

## Key Notes
- Projectile motion occurs when an object is launched into the air and moves under gravity.
- Horizontal motion: Constant velocity ($ v_x = v_0\cos\theta $).
- Vertical motion: Accelerated by gravity ($ a_y = -g $).

---

## 1D Projectile Motion

### Scenario: Object Dropped from Rest
- An object is dropped from height $ h $. Find time to hit the ground and velocity upon impact.

**Solution:**
$$
h = \frac{1}{2}gt^2 \implies t = \sqrt{\frac{2h}{g}}
$$
$$
v = gt
$$

### Real-World Application:
- Free-falling objects like parachutes or dropped items.

---

## 2D Projectile Motion

### Scenario 1: Horizontal Launch
- A ball is kicked horizontally with velocity $ v_0 $ from height $ h $. Find range and time of flight.

**Solution:**
Vertical motion:
$$
h = \frac{1}{2}gt^2 \implies t = \sqrt{\frac{2h}{g}}
$$
Horizontal motion:
$$
R = v_0t
$$

### Real-World Application:
- Throwing stones off cliffs or launching drones horizontally.

---

### Scenario 2: Launch at an Angle
- A projectile is launched with velocity $ v_0 $ at angle $ \theta $. Find maximum height, range, and time of flight.

**Solution:**
Horizontal and vertical components:
$$
v_x = v_0\cos\theta, \quad v_y = v_0\sin\theta
$$
Time of flight:
$$
t_{\text{flight}} = \frac{2v_y}{g} = \frac{2v_0\sin\theta}{g}
$$
Maximum height:
$$
H = \frac{v_y^2}{2g} = \frac{(v_0\sin\theta)^2}{2g}
$$
Range:
$$
R = v_xt_{\text{flight}} = \frac{v_0^2\sin(2\theta)}{g}
$$

### Real-World Application:
- Artillery fire, sports like javelin throwing, fireworks.

---

## 3D Projectile Motion

### Scenario: Drone Motion
- A drone launches with velocity $ v_0 $ at angles $ \theta $ (horizontal) and $ \phi $ (vertical). Find position after time $ t $.

**Solution:**
Components:
$$
v_x = v_0\cos\theta\cos\phi, \quad v_y = v_0\sin\theta\cos\phi, \quad v_z = v_0\sin\phi
$$
Position:
$$
x = v_xt, \quad y = v_yt, \quad z = v_zt - \frac{1}{2}gt^2
$$

### Real-World Application:
- UAV navigation, missile trajectories.