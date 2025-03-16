# AUV Mechanical Design - Evolution & Strategy

## Overview
This repository documents the mechanical design considerations and evolution of our Autonomous Underwater Vehicle (AUV). The primary focus is on achieving optimal buoyancy, stability, and structural integrity while ensuring efficiency in underwater maneuverability.

## **Version 1: Initial Design & Challenges**

### **Design Approach:**
- The **center of mass** was initially intended to be at the geometric center of the bot.
- An **aluminum frame** was used to hold the hull, providing structural support.
- The frame was **hollow**, which contributed to **positive buoyancy**.

### **Manufactured results:**
<p align="center">
  <img src="Version1_content/PXL_20231230_095338993.MP.jpg" alt="Alt Text" width="400" height="300">
</p>


### **Challenges Faced:**
- The **center of mass** shifted backward, affecting stability.
- The **bot became overly buoyant**, requiring **up to 15 kg** of additional external weight to counteract the buoyancy.
- Excessive weight led to:
  - **High inertia**, making rapid underwater maneuvers difficult.
  - **Increased battery consumption** due to the excessive mass to be controlled.
- The overall design proved inefficient in terms of weight distribution and control underwater.

## **Version 2: Optimized Design & Improvements**

### **Design Modifications:**
- The frame was **redesigned and 3D printed** with **100% infill density wiht PETG** to achieve a **negatively buoyant** structure.
- External volume was **minimized**, reducing drag and making the design more compact.
- The updated frame, in combination with:
  - The **weight of electronics**
  - **External weight holders**
  ensured the bot achieved **neutral buoyancy at 9 kg**, without requiring additional weights.
- Slots were still included in the design for **optional weight adjustments**, providing flexibility.

### **Outcome & Benefits:**
- The bot achieved **better buoyancy balance**.
- **Improved energy efficiency**, as less power was required to stabilize and move.
- **Enhanced maneuverability**, allowing smoother and quicker control underwater.
- A structurally **more robust and modular design** suitable for further optimizations.

## **Future Improvements**
- Evaluating materials with high strength-to-weight ratio to further optimize weight.
- Introducing adaptive weight distribution systems to enhance control.
- Additional hydrodynamic testing for drag reduction.

## **Conclusion**
Through iterative mechanical design, we successfully transitioned from an overweight, difficult-to-control AUV to a compact, efficient, and neutrally buoyant design. These insights will guide further refinements in our pursuit of a high-performance underwater vehicle.

---
### Contributors
- **Nainaiu Rakhaine**
- **Mirza Nihal Baig**
- **Ad-Deen Mahbub**
- **Team Onushondhan (SAUVC 2025)**

For further queries, feel free to raise an issue or contribute to the repository!
