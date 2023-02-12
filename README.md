# Finite Deformation Kinematics
## Contents
- Deformation Map
- Deformation Gradient
- Strain **tensors**

## Deformation Map

**x** = $\varphi$(**X**, t)

- The deformation map $\varphi$ **maps** the position in the reference (undeformed) configuration **X** and the position in the current (deformed) configuration **x**.
- **X** is the input for $\varphi$, and $\varphi$ uses **X** to give **x**.

![Finite Kinematics A](https://user-images.githubusercontent.com/75183035/218295554-caf40df9-530e-4faa-8067-db6dc8c4f733.png)

Properties of Deformation Map:

$\varphi$ **uniquely** maps **one-to-one** a point X in reference configuration to a point **x** in current configuration.

- one-to-one means 2 points cannot be mapped into a same point.
- uniquely means one physical deformation cannot be described by 2 different maps.

## Deformation Gradient

![203c8cf688621a917a79be8601cee5b5](https://user-images.githubusercontent.com/75183035/218296284-b26a6986-8632-4c47-9c16-25a85e062b34.png)

**F** = d**x**/d**X**

- **F** is the deformation gradient, which maps a line d**X** in the undeformed shape to a line d**x** in the deformed shape. 
- **F** transfers **material lines** by rotating and stretching to **spatial lines**.

Deformation tensors:

1. Right Cauchy-Green deformation tensor:

>> **C** = transpose(**F**)\***F**

2. Left Cauchy-Green deformation tensor:

>> **B** = **F**\*transpose(**F**)

## Strain tensors

- Small-strain tensor
- Green-Lagrange strain tensor
- Euler-Almansi strain tensor




