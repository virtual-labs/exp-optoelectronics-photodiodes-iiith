

Optoelectronic devices exploit the interaction between **photons** and **charge carriers** in semiconductors to either:

- **Generate electrical signals from light** (*photodetection*), or
- **Produce light from electrical energy** (*emission*).

Three key devices form the foundation of this field:

- **Photodiodes:** Reverse-biased PN junctions where incident photons generate electron–hole pairs, producing a **photocurrent**.
- **LEDs:** Forward-biased PN junctions where injected carriers recombine radiatively, **emitting photons**.
- **Solar Cells:** Large-area photodiodes operated in **photovoltaic mode** to convert **sunlight into electrical power**.

Specialized variants include:

- Avalanche photodiodes
- CCD/CMOS image sensors
- Laser diodes

These extend optoelectronic principles to **high-sensitivity detection**, **imaging**, and **coherent light generation**.

---

## **Photon–Carrier Interactions**

The fundamental processes in optoelectronic devices involve:

1. **Photon Absorption** → A photon with energy \( h\nu \geq E_g \) excites an electron from the **valence band** to the **conduction band**.
2. **Carrier Generation & Separation** → In the depletion region, the built-in **electric field** sweeps carriers toward opposite terminals.
3. **Radiative Recombination** → In **direct bandgap semiconductors**, electron–hole recombination releases a photon.

<p><img src="images/Pn.png" ></p> 

---

## **Photodiode Operation**

For a reverse-biased photodiode, the total current is:

$$
I = I_{\text{dark}} - I_{\text{ph}}
$$

Where:

$$
I_{\text{dark}} = I_S \left( e^{\frac{qV}{kT}} - 1 \right)
$$

and the **photocurrent** is:

$$
I_{\text{ph}} = \frac{q \, \eta \, P_{\text{opt}}}{h\nu}
$$

- \( \eta \) → Quantum efficiency  
- \( P_{\text{opt}} \) → Incident optical power  
- \( h\nu \) → Photon energy  

For reverse bias \( V < 0 \), \( I_{\text{ph}} \) dominates.
<p><img src="images/Dark.png" ></p> 
---

## **LED Operation**

For a forward-biased LED, the **injected carrier density** determines the photon emission rate.  
The **internal quantum efficiency** is:

$$
\eta_{\text{int}} = \frac{R_{\text{rad}}}{R_{\text{rad}} + R_{\text{nonrad}}}
$$

Where:

- \( R_{\text{rad}} \) → Radiative recombination rate  
- \( R_{\text{nonrad}} \) → Non-radiative recombination rate  

The **emitted optical power** is given by:

$$
P_{\text{opt}} = \eta_{\text{ext}} \cdot \frac{h\nu I}{q}
$$

Where \( \eta_{\text{ext}} \) is the **external quantum efficiency**, accounting for optical extraction losses.

<p><img src="images/led.png" ></p> 

---

## **Solar Cell Operation**

A solar cell behaves as a **large-area photodiode** operated at zero or forward bias.  
The illuminated **I–V relationship** is:

$$
I = I_S \left( e^{\frac{qV}{kT}} - 1 \right) - I_{\text{ph}}
$$

### **Key Performance Parameters**

- **Short-circuit current**:

$$
I_{\text{sc}} = I \Big|_{V=0}
$$

- **Open-circuit voltage**:

$$
V_{\text{oc}} = V \Big|_{I=0}
$$

- **Fill Factor**:

$$
FF = \frac{V_{\text{mp}} I_{\text{mp}}}{V_{\text{oc}} I_{\text{sc}}}
$$

- **Efficiency**:

$$
\eta = \frac{V_{\text{oc}} I_{\text{sc}} FF}{P_{\text{in}}}
$$

<p><img src="images/solar.png" ></p> 

---

## **Specialized Devices**

- **Avalanche Photodiode (APD):** Reverse-biased beyond breakdown; carriers undergo **impact ionization**, giving **high multiplication gain**.
- **CCD / CMOS Image Sensors:** Use arrays of photodiodes for image capture.  
    - **CCD:** Uses charge transfer between pixels.  
    - **CMOS:** Uses per-pixel amplification.
- **Laser Diode:** Uses **double heterostructures** to confine carriers and photons, achieving **stimulated emission** and **coherent light output**.

> *[Insert schematic diagrams for avalanche photodiode, CCD pixel, and laser diode band diagram]*

---

## **Summary of Key Equations**

**Photocurrent:**

$$
I_{\text{ph}} = \frac{q \, \eta \, P_{\text{opt}}}{h\nu}
$$

**Internal Quantum Efficiency:**

$$
\eta_{\text{int}} = \frac{R_{\text{rad}}}{R_{\text{rad}} + R_{\text{nonrad}}}
$$

**Solar Cell Efficiency:**

$$
\eta = \frac{V_{\text{oc}} I_{\text{sc}} FF}{P_{\text{in}}}
$$




