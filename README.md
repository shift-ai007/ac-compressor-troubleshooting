# AC Compressor Troubleshooting Guide

A hands-on guide to diagnosing air conditioning compressor problems. Covers common failure symptoms, electrical testing basics, refrigerant indicators, and when to repair vs. replace — focused on residential split systems in hot climates like South Florida.

## Why Compressors Fail

The compressor is the heart of your AC system. It pressurizes refrigerant and circulates it between the indoor evaporator and outdoor condenser. In South Florida, compressors work harder and longer than almost anywhere else in the country — 3,000+ hours per year compared to 1,500 in northern states.

Common causes of compressor failure:

- **Electrical issues** — voltage spikes, bad capacitors, contactor failure
- **Refrigerant problems** — low charge (leak), overcharge, wrong type
- **Mechanical wear** — bearing failure, valve damage, slugging
- **Overheating** — restricted airflow, dirty condenser coils, blocked suction line
- **Flooding** — liquid refrigerant entering the compressor (liquid slugging)

## Table of Contents

1. [Symptom Diagnosis Chart](#symptom-diagnosis-chart)
2. [Sound-Based Diagnosis](#sound-based-diagnosis)
3. [Electrical Testing](#electrical-testing)
4. [Refrigerant Indicators](#refrigerant-indicators)
5. [Compressor Types](#compressor-types)
6. [Repair vs Replace Decision](#repair-vs-replace-decision)
7. [Preventive Measures](#preventive-measures)
8. [Emergency Steps](#emergency-steps)

## Symptom Diagnosis Chart

| Symptom | Possible Cause | Severity | DIY? |
|---------|---------------|----------|------|
| AC blows warm air, outdoor unit running | Low refrigerant or compressor not engaging | High | No |
| Outdoor unit hums but doesn't start | Bad start capacitor or locked rotor | High | No |
| Circuit breaker trips when AC starts | Grounded compressor or short circuit | Critical | No |
| AC cycles on/off every few minutes | Overheating, low refrigerant, or bad TXV | High | No |
| Loud banging from outdoor unit | Broken valve, loose mount, or liquid slugging | High | No |
| Oil stains around outdoor unit | Refrigerant leak at compressor connections | Medium | No |
| AC runs but house won't cool below 80°F | Weak compressor, low charge, or airflow issue | Medium | Partial |
| Compressor vibrates excessively | Worn bearings or mounting hardware | Medium | No |

**Important**: Compressor work involves high-voltage electricity (240V) and pressurized refrigerant. All repairs beyond basic inspection should be performed by a licensed HVAC technician.

## Sound-Based Diagnosis

Your compressor tells you a lot through the sounds it makes:

### Normal Sounds
- **Steady hum** when running — the compressor motor
- **Click** at startup — contactor engaging
- **Gentle whoosh** — refrigerant flowing through lines

### Warning Sounds

```
CLICKING (rapid, repeated)
├── Relay trying to start but failing
├── Check: start capacitor, relay, voltage
└── Action: turn off AC, call technician

BUZZING (continuous, compressor not running)
├── Compressor trying to start against high pressure
├── Check: wait 5 minutes for pressure to equalize
└── If continues: bad capacitor or seized compressor

BANGING / CLANKING
├── Internal mechanical failure
├── Broken connecting rod, valve, or piston
└── Action: shut down immediately — running worsens damage

HISSING (loud, from outdoor unit)
├── Refrigerant leak
├── Compressor valve leak
└── Action: turn off, do not restart, call for service

SCREAMING / HIGH-PITCHED WHINE
├── Dangerously high internal pressure
├── Compressor safety switch may be failing
└── Action: SHUT OFF AT BREAKER immediately, call emergency service
```

## Electrical Testing

### Safety First

- Disconnect power at the breaker AND at the outdoor unit disconnect box
- Use a multimeter rated for 600V CAT III minimum
- Discharge the capacitor before touching any wires (use an insulated screwdriver across terminals)
- Never bypass safety controls or thermal overloads

### Capacitor Test

The start/run capacitor is the #1 cause of compressor failure to start. Test it first:

```
1. Disconnect power and discharge capacitor
2. Set multimeter to capacitance (μF) mode
3. Connect leads to capacitor terminals
4. Reading should be within ±6% of labeled value

Example: A 45/5 μF dual capacitor
- HERM-C terminals should read 43–47 μF (compressor)
- FAN-C terminals should read 4.7–5.3 μF (condenser fan)
- Outside range = replace capacitor
```

**Cost**: $15–$40 for the part, $150–$250 installed. This is the cheapest and most common fix.

### Compressor Winding Test

If the capacitor is good, test the compressor windings:

```
Terminals: C (Common), S (Start), R (Run)

Resistance Test:
1. Measure C-to-S: should read lowest value (start winding)
2. Measure C-to-R: should read medium value (run winding)
3. Measure S-to-R: should equal C-to-S + C-to-R
4. Any reading of 0Ω = shorted winding (compressor dead)
5. Any reading of ∞ (OL) = open winding (compressor dead)

Ground Fault Test:
1. Set meter to highest ohm range
2. Measure from each terminal (C, S, R) to compressor body
3. All readings should be ∞ (OL) = no ground fault
4. Any measurable reading = grounded compressor (replace)
```

### Amperage Draw

```
Normal operation:
- Compare actual amps to the RLA (Rated Load Amps) on the nameplate
- Within 10% of RLA = healthy
- Exceeding RLA = compressor is struggling
- LRA (Locked Rotor Amps) at startup is normal — should drop within 1-2 seconds

High amp draw causes:
- Low refrigerant (compressor works harder)
- Dirty condenser coils (high head pressure)
- Restricted metering device
- Failing compressor valves
```

## Refrigerant Indicators

Refrigerant issues and compressor problems are deeply linked:

### Low Refrigerant Signs
- Suction line (large copper line) is warm instead of cold and sweating
- Frost on the evaporator coil (indoor unit)
- Compressor runs hot to the touch
- Superheat is high (>20°F at suction line)

### Overcharged Signs
- Subcooling is too high (>15°F)
- Compressor amperage exceeds RLA
- Head pressure above normal range
- Liquid slugging sounds (banging at startup)

### Refrigerant Type Reference

| Refrigerant | Status | Systems |
|------------|--------|---------|
| R-22 (Freon) | Phased out — no new production | Pre-2010 systems |
| R-410A (Puron) | Current standard, being phased down | 2010–2024 systems |
| R-32 | Next generation, lower GWP | New 2025+ systems |
| R-454B | DOE-approved R-410A replacement | New 2025+ systems |

**Florida note**: R-22 is no longer manufactured. If your system uses R-22 and the compressor fails, replacement with a new R-410A or R-454B system is almost always more cost-effective than sourcing reclaimed R-22.

## Compressor Types

### Reciprocating
- Older design using pistons
- Found in systems pre-2005
- Noisier, less efficient, but durable
- Repairable in some cases (valve plates)

### Scroll
- Modern standard for residential AC
- Two spiral-shaped scrolls compress refrigerant
- Quieter, more efficient, fewer moving parts
- Generally not field-repairable — replace as a unit

### Rotary
- Common in mini-split systems
- Very quiet and compact
- Efficient at partial loads
- Not field-repairable

### Variable Speed (Inverter)
- Premium systems (Carrier Infinity, Trane XV, Daikin)
- Adjusts speed to match load — no hard start/stop cycles
- Highest efficiency (20+ SEER2)
- Requires specialized diagnosis — check inverter board first

## Repair vs Replace Decision

### Factors to Consider

```
REPAIR if:
✓ System is < 8 years old
✓ Problem is electrical (capacitor, contactor, relay)
✓ Compressor is under manufacturer warranty
✓ System uses R-410A or newer refrigerant
✓ Rest of the system is in good condition
✓ Repair cost < 50% of replacement cost

REPLACE if:
✗ System is > 12 years old
✗ Uses R-22 refrigerant
✗ Compressor has internal mechanical failure
✗ History of repeated repairs
✗ System undersized for the home
✗ Energy bills are abnormally high
```

### Typical Costs (South Florida, 2025–2026)

| Repair | Cost Range |
|--------|-----------|
| Capacitor replacement | $150–$250 |
| Contactor replacement | $200–$350 |
| Hard start kit | $150–$300 |
| Compressor replacement (warranty) | $800–$1,500 (labor only) |
| Compressor replacement (no warranty) | $2,000–$3,500 |
| Full system replacement (3-ton) | $5,500–$9,000 |
| Full system replacement (5-ton) | $7,500–$12,000 |

## Preventive Measures

Extend your compressor's life with these habits:

1. **Change filters monthly** in South Florida (high dust, pollen, humidity)
2. **Keep condenser coils clean** — hose off the outdoor unit quarterly
3. **Clear 2 feet around the outdoor unit** — no plants, debris, or fences restricting airflow
4. **Schedule annual maintenance** — a technician checks refrigerant charge, electrical connections, and capacitor health
5. **Install a surge protector** — Florida's lightning capital status means power surges are a real threat
6. **Don't set the thermostat below 72°F** — forcing the system to extremes increases wear
7. **Check the drain line monthly** — a clogged drain can cause the system to freeze, stressing the compressor

## Emergency Steps

If your compressor fails on a hot day:

1. **Turn off the AC at the thermostat** — don't let it keep trying to start
2. **Check the breaker** — if tripped, wait 30 minutes, reset once. If it trips again, leave it off
3. **Close blinds and curtains** — block solar heat gain
4. **Use ceiling fans** — moving air feels 4°F cooler
5. **Open windows at night** if temperature drops below 78°F
6. **Call for service** — for [emergency AC repair in South Florida](https://ac-repair.today/services/emergency-ac-repair/), a licensed technician can diagnose and often repair the same day

## Additional Resources

- [guides/capacitor-replacement.md](guides/capacitor-replacement.md) — Visual guide to identifying and testing capacitors
- [guides/reading-nameplate.md](guides/reading-nameplate.md) — How to read your compressor's nameplate data
- [guides/refrigerant-pressure-chart.md](guides/refrigerant-pressure-chart.md) — Normal operating pressures by refrigerant type and outdoor temp

## Contributing

Found something that could be improved? Experienced a compressor issue we didn't cover? Open an issue or PR.

## License

MIT License — see [LICENSE](LICENSE) for details.

---

*Built by [AC Repair Today](https://ac-repair.today) — Licensed HVAC contractor serving South Florida. FL License CAC1824118.*
