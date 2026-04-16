# AC Capacitor Identification and Testing Guide

## What is a Capacitor?

A capacitor stores electrical energy and releases it in a burst to help start the compressor motor and keep it running. It's the single most common point of failure in residential AC systems, especially in hot climates where the system runs constantly.

## Types of Capacitors

### Start Capacitor
- Provides a high-torque boost to start the compressor
- Only active for 1–2 seconds during startup
- Higher capacitance (88–108 μF typical)
- Black cylindrical case, usually with a Bakelite top
- Has a built-in bleed resistor

### Run Capacitor
- Provides continuous energy to the compressor motor while running
- Active the entire time the compressor operates
- Lower capacitance (35–60 μF typical)
- Silver or aluminum oval or round case
- Usually marked as "dual" because it serves both compressor and condenser fan

### Dual Run Capacitor
- Most common in residential systems
- Single unit with three terminals: HERM, FAN, C (Common)
- HERM terminal = compressor run capacitor
- FAN terminal = condenser fan motor capacitor
- C terminal = shared common
- Rated like "45/5 μF" (45 for compressor, 5 for fan)

## How to Identify a Bad Capacitor

### Visual Signs (power off, panel removed)
- **Bulging top** — the flat top is pushed out or domed
- **Leaking oil** — brown or clear fluid around the base
- **Burn marks** — discoloration on the case or nearby wires
- **Swollen case** — sides are bowed outward

### Behavioral Signs
- AC hums but compressor doesn't start
- Compressor starts then shuts off within seconds
- Condenser fan doesn't spin (or spins slowly)
- You can spin the fan blade by hand and it starts running — classic bad fan capacitor

## Testing a Capacitor

### Required Tools
- Digital multimeter with capacitance (μF) mode
- Insulated screwdriver (for discharge)
- Safety glasses

### Step-by-Step Test

```
1. TURN OFF POWER at the breaker and the outdoor disconnect

2. REMOVE the access panel on the outdoor unit
   - Usually held by 1-2 screws on the side panel

3. LOCATE the capacitor
   - Oval or round silver/aluminum cylinder
   - Connected by 3 wires (dual) or 2 wires (single)
   - Held by a metal bracket or strap

4. DISCHARGE the capacitor
   - Place an insulated screwdriver across HERM and C terminals
   - Then across FAN and C terminals
   - You may see a small spark — this is normal
   - NEVER skip this step

5. DISCONNECT wires (note which wire goes where — take a photo first)
   - Pull connectors straight off the terminals
   - Do not wiggle or bend

6. READ the capacitor label
   - Note the rated μF (e.g., 45/5 μF ±6%)
   - Note the voltage rating (e.g., 370V or 440V)

7. SET multimeter to capacitance mode (μF symbol)

8. TEST:
   For dual capacitor:
   - Touch leads to HERM and C → should read close to 45 μF
   - Touch leads to FAN and C → should read close to 5 μF

   For single capacitor:
   - Touch leads to the two terminals → compare to rated μF

9. EVALUATE:
   - Within ±6% of rated value = GOOD
   - 7-10% off = WEAK (will fail soon — replace preventively)
   - More than 10% off or reads 0 = FAILED (replace now)
   - Reads OL (overload/infinity) = OPEN (replace now)
```

## Replacement

### Matching the Replacement

You need to match three specifications:
1. **Capacitance (μF)**: Must match exactly (e.g., 45/5 replaces 45/5)
2. **Voltage**: Can be equal or higher, never lower (440V replaces 370V — OK)
3. **Type**: Dual replaces dual, single replaces single

### Common Sizes (South Florida Residential)

| System Size | Typical Dual Capacitor | Typical Start Capacitor |
|-------------|----------------------|------------------------|
| 2 ton | 35/5 μF 370V | 88-108 μF 250V |
| 2.5 ton | 40/5 μF 370V | 88-108 μF 250V |
| 3 ton | 45/5 μF 370V | 108-130 μF 250V |
| 3.5 ton | 45/5 μF 440V | 130-156 μF 330V |
| 4 ton | 50/5 μF 440V | 145-175 μF 330V |
| 5 ton | 55/7.5 μF 440V | 161-193 μF 330V |

### Installation Tips

- Mount the new capacitor in the same bracket
- Connect wires exactly as they were (photo reference!)
- HERM → goes to the compressor contactor
- FAN → goes to the condenser fan motor
- C → goes to the common side of the contactor
- Make sure connectors are fully seated and snug
- Replace the access panel before powering on

## Why Capacitors Fail More in Florida

1. **Heat**: Capacitor lifespan decreases exponentially above 150°F. Florida outdoor units regularly reach 140°F+ in the condenser compartment
2. **Runtime**: Compressors run 3,000+ hours/year vs. 1,500 in northern states — more stress on the capacitor
3. **Lightning**: Florida averages 25+ lightning days per year. Even near-strikes cause voltage spikes that degrade capacitors
4. **Humidity**: Moisture can corrode terminals and weaken the capacitor's internal dielectric

**Recommendation**: In South Florida, replace capacitors preventively every 5 years, even if they test within range. A $30 capacitor is cheap insurance against a $200+ emergency service call.
