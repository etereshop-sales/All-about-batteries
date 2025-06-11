# All-about-batteries
Here you will find everything about batteries

# 18650 Battery Usage and Recommendations

This document provides essential information for the safe handling, installation, and selection of 18650 lithium-ion batteries. It includes details on battery dimensions, installation procedures, and recommended models with their specifications.

## 1. Battery Dimensions

18650 batteries typically have the following dimensions:
* **Diameter:** `18mm`
* **Length:** `65mm`

## 2. How to Insert the Battery

Follow these steps carefully to insert the battery:

### ➤ Step 1: Determine Polarity
Identify the positive (`+`) and negative (`-`) poles of the contact pads.

### ➤ Step 2: Inspect the Battery for Damage
Before installation, visually inspect the battery for any signs of damage.  
**Contraindications for use:**
* Presence of dents on the battery body.
* Damage to the insulation, especially near the positive pad.

### ➤ Step 3: Install the Battery
Install the battery into the holder, ensuring you observe the correct polarity (`+` into `+`, `-` into `-`).


![Battery Installation](battery_installation.jpeg)


## 3. Recommended Battery Models

The following table lists recommended 18650 battery models with their typical current and capacity specifications.

| Manufacturer | Model         | Current (A) | Capacity (mAh) |
| :----------- | :------------ | :---------- | :------------- |
| Molicel      | INR18650-P28A | `35`        | `2800`         |
| Molicel      | INR18650-P26A | `35`        | `2600`         |
| Murata       | VTC5D         | `35`        | `2800`         |
| Murata       | VTC5A         | `30-35`     | `2500`         |
| Samsung      | INR18650-25S  | `25-35`     | `2500`         |
| Samsung      | INR18650-20S  | `30`        | `2000`         |
| Murata       | VTC6          | `30`        | `2100`         |
| Murata       | VTC5          | `20-30`     | `2600`         |
| Sanyo        | UR18650NSX    | `20`        | `2500`         |
| Samsung      | INR18650HG2   | `20`        | `3000`         |
| Samsung      | INR18650HJ2   | `20`        | `3000`         |
| Samsung      | INR18650HE4   | `20`        | `2500`         |
| Samsung      | INR18650-25R  | `20`        | `2500`         |

## 4. Battery Specifications and Purchase Guidelines

### Size
* Flat-top batteries are recommended, but not strictly required.
* Ensure the battery is **exactly `65 mm` long**. Some batteries may be `2-3 mm` longer, which will prevent them from fitting into the holders.

### Characteristics
* **Voltage:** `3.7 Volts`
* **Current:** The rated current must be **not less than `15 Amperes`**. This parameter is the most crucial for performance and safety. Avoid buying batteries designed for flashlights, especially if the current rating is not explicitly indicated on the packaging.
* **Recommended Capacity:** `2500-3800 mAh`.  
  Be cautious: if you see capacities advertised as `4000-9000 mAh`, consider that this is likely a fake capacity.

# How to Check the Charge of an 18650 Battery

This guide explains how to accurately check the charge level of an 18650 lithium-ion battery using a multimeter. Some chargers may show an approximate charge level, but using a multimeter provides more reliable and precise results.

## 1. What You’ll Need

To check the battery charge, prepare the following:

* **A digital multimeter**
* The 18650 battery (installed or removed)

## 2. Measurement Settings

Set your multimeter to **DC voltage measurement mode**, usually labeled as:

* **`20V` range** (This allows you to measure voltages from `0V` to `20V` with two digits after the decimal point.)

## 3. How to Measure

Follow these steps:

### ➤ Step 1: Connect the Probes

* Place the **red probe** to the battery's **positive terminal**.
* Place the **black probe** to the battery's **negative terminal**.
* It does not matter if the screen shows a negative value — the **absolute voltage** number is what matters.

### ➤ Step 2: Read the Display

Interpret the voltage according to the table below:

| Voltage Range | Battery State            |
| :------------ | :------------------------ |
| `3.9V – 4.3V` | Fully charged             |
| `3.4V – 3.8V` | Partially charged         |
| `< 3.4V`      | Discharged                |
| `< 2.5V`      | Deep discharge (replace)  |

>  **Warning:** If the voltage is **below `2.5V`**, the battery is in **deep discharge mode** and should be **replaced** to avoid performance issues or safety risks.



