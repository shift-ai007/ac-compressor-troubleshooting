# How to Read Your AC Compressor Nameplate

## Finding the Nameplate

The compressor nameplate is a metal or adhesive label on the compressor body inside the outdoor unit (condenser). To access it:

1. Turn off power at the breaker and disconnect
2. Remove the side access panel (usually 2–4 screws)
3. The compressor is the large cylindrical component
4. The nameplate is on the side, often partially hidden by wiring or the capacitor bracket

## Key Nameplate Data

### Example Nameplate

```
┌──────────────────────────────────────────┐
│  COPELAND SCROLL COMPRESSOR              │
│  Model: ZR57K3E-TFD-230                  │
│  Serial: 24G12345                        │
│                                          │
│  Volts: 208-230    Phase: 1    Hz: 60    │
│  RLA: 22.4A        LRA: 133A             │
│  HP: 4.75                                │
│  Refrigerant: R-410A                     │
│  Max Fuse: 40A                           │
│  Min Circuit Ampacity: 27.8A             │
│  UL Listed                               │
└──────────────────────────────────────────┘
```

### What Each Value Means

**Model Number Decode** (Copeland example: ZR57K3E-TFD-230)
- ZR = Scroll compressor series
- 57 = BTU capacity in thousands (57,000 BTU = ~4.75 tons)
- K3 = Design series
- E = High efficiency
- TFD = Three-phase fixed displacement (or TF5 for single-phase)
- 230 = Voltage

**Volts**: Operating voltage range. Most residential is 208-230V single phase. If your supply voltage is consistently outside this range, the compressor will run inefficiently or fail prematurely.

**Phase**: 1 (single phase, residential) or 3 (three phase, commercial).

**Hz**: 60 Hz in North America. Equipment from other countries may be 50 Hz and is not compatible.

**RLA (Rated Load Amps)**: The maximum current the compressor should draw during normal operation. If your clamp meter reads above this, the compressor is working too hard.

**LRA (Locked Rotor Amps)**: The current drawn at startup when the motor is first energized and hasn't started spinning yet. This spike lasts 1–2 seconds. If the compressor draws LRA for more than 3 seconds, something is preventing it from starting.

**HP (Horsepower)**: Compressor motor size. Residential ranges from 2 HP (1.5 ton system) to 7 HP (5 ton system).

**Refrigerant**: The type of refrigerant the compressor is designed for. Never use a different refrigerant type without proper conversion (which usually means replacing the compressor anyway).

**Max Fuse / HACR Breaker**: The maximum overcurrent protection device. Using a larger fuse or breaker than specified is a fire hazard and code violation.

**Min Circuit Ampacity**: The minimum wire gauge capacity for the circuit feeding this unit. Used to verify proper wire sizing.

## Using Nameplate Data for Diagnosis

### Checking Amperage

```
Measured amps vs. RLA:
- Below RLA:      Normal operation
- At RLA:         Running at maximum — check for dirty coils, low airflow
- 10-20% above:   Compressor struggling — check refrigerant charge, metering device
- Near LRA:       Compressor locked or seized — shut down immediately
```

### Estimating System Capacity

Quick conversion from compressor model number or BTU rating:

```
BTU ÷ 12,000 = Tons

18,000 BTU = 1.5 ton
24,000 BTU = 2 ton
30,000 BTU = 2.5 ton
36,000 BTU = 3 ton
42,000 BTU = 3.5 ton
48,000 BTU = 4 ton
60,000 BTU = 5 ton
```

### Verifying Correct Replacement

When replacing a compressor, the new unit must match:
1. Refrigerant type
2. Voltage and phase
3. BTU capacity (within 10%)
4. Physical dimensions (mounting bolt pattern, suction/discharge line sizes)
5. Oil type and charge

## Common Compressor Manufacturers in South Florida

| Brand on System | Compressor Manufacturer | Model Prefix |
|----------------|------------------------|--------------|
| Carrier, Bryant, Payne | Copeland (Emerson) | ZR, ZP, ZB |
| Trane, American Standard | Copeland or Danfoss | ZR, ZP, MLZ |
| Rheem, Ruud | Copeland or Bristol | ZR, H2 |
| Lennox | Copeland or Bristol | ZR, ZP, H2 |
| Goodman, Amana, Daikin | Copeland or Mitsubishi | ZR, ANB |
| York, Coleman | Bristol or Copeland | H2, ZR |

## Serial Number Date Code

Most compressors encode the manufacturing date in the serial number:

- **Copeland**: First two digits = year, next letter = month (A=Jan, B=Feb... L=Dec, skipping I)
  - Serial `24G12345` → 2024, G = July
- **Bristol**: First digit = year, second digit = month
  - Serial `4A12345` → 2024, A = January

Knowing the age helps evaluate whether a compressor is worth repairing (under 8 years) or replacing (over 12 years).
