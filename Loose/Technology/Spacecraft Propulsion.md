---
tags:
  - technology
---

Electric propulsion is the standard high-efficiency [[Spacecraft]] propulsion architecture of the [[Immediate Stellar Cluster]]. Compact, mature fusion generation removes the power bottleneck that constrains electric propulsion in our world.

> **Fusion supplies the power; electric propulsion supplies the endurance; chemical propulsion supplies the urgency.**

## Architecture

| System | Role |
| --- | --- |
| **Stellarator fusion generator** | Primary onboard electrical power source. Large freighters commonly carry substantial stellarators, with a major radius of around **20 m** on the largest merchant vessels. |
| **High-power fusion-electric main engines** | Primary cruise propulsion: electromagnetic or plasma thrusters, especially MPD-like designs. |
| **Hall-effect thrusters** | Routine attitude control, translation, docking and slow reorientation, distributed around the hull in clusters. |
| **Chemical reaction-control system** | An independent emergency system for rapid attitude changes, collision avoidance, docking aborts, loss of electrical power or recovery from tumbling. |
| **Radiator system** | Rejects waste heat from the reactor, generators, power electronics, electric engines and [[Isolation#40. Energy Requirements\|isolation drive]]. |

This is **fusion-electric** propulsion, not direct fusion propulsion. The stellarator produces electrical power, which is distributed to separate electric thrusters that accelerate reaction mass. Direct fusion rockets could exist as a distinct and more demanding technology, but ordinary merchant propulsion does not need them.

## Main Engines

The main engines have **very high specific impulse but only moderate thrust relative to the mass of the vessel**. Freighters therefore accumulate large velocity changes through continuous acceleration lasting hours or longer, rather than through brief high-thrust burns. Large merchant vessels behave more like slowly accelerating industrial structures than conventional rockets.

For normal braking, a ship rotates 180° on its attitude thrusters and runs its main engines retrograde. Forward-facing main engines or rotatable propulsion assemblies are possible, but not necessary.

Hall thrusters are extremely efficient and can run whenever electrical power is available, so ordinary spacecraft rarely spend chemical propellant on routine manoeuvring. On very large freighters, rotations may take tens of seconds or minutes.

The chemical system is deliberately **not a complete backup propulsion system**. Chemical propellant is far too mass-intensive to reproduce the velocity change available from the electric drive. It provides high instantaneous control authority when efficiency is irrelevant: it can correct a dangerous closing velocity or arrest an uncontrolled rotation, but it cannot replace the main engines partway through a journey.

## High-Thrust Propulsion

Fusion-electric engines cannot lift a vessel against a world's gravity. Hovering at 1.5 g would demand tens to hundreds of kilowatts of jet power per kilogram of vessel. Craft built to land, take off and fight therefore carry a high-thrust system as well.

### Fusion-Thermal Air-Breathing Engines

The principal high-thrust system for landing craft, ferries and combat craft. The reactor's heat expands air drawn from the surrounding atmosphere, so the atmosphere itself supplies the reaction mass.

The power needed for a given thrust is proportional to the exhaust velocity:

$$  
P_{\mathrm{jet}}=\tfrac12\,F\,v_e  
$$

Accelerating large quantities of air slowly is therefore the most power-efficient way to lift. Consequently:

- dense atmospheres are the easiest worlds to land on and leave;
- an engine's performance follows the density and composition of the local atmosphere;
- low-gravity airless moons remain accessible on stored propellant;
- airless high-gravity worlds are genuinely difficult to reach and leave.

### High-Energy Chemical Propulsion

Some craft instead use chemical propulsion built on a high-energy-density compound or storage technology. A chemical single-stage-to-orbit craft for an Earth-like world needs an exhaust velocity of roughly 8 to 10 km/s, roughly twice that of the best conventional propellants. The compound or technology is yet to be named (see [[#Open Questions]]).

## Design Limits

Energy is rarely the limiting factor. Spacecraft designers contend instead with:

- waste heat and radiator area;
- engine lifetime and plasma erosion;
- propellant throughput;
- structural loading;
- electrical distribution;
- manoeuvrability.

Fusion fuel is needed only occasionally: even an interstellar crossing under an isolation drive consumes under a kilogram for a mid-sized vessel.

Bigger ships remain attractive because energy and extraterrestrial construction materials are abundant. Enormous vessels, however, become increasingly cumbersome and concentrate more cargo and capital into a single failure. Such ships are economically analogous to ULCVs: trunk-route carriers connecting a relatively small number of major inhabited and industrial centres, usually through [[RIC|RICs]].

A large vessel relying on fusion-electric propulsion alone cannot land on a world with significant gravity. Haulers, capital ships and other large vessels stay in space, and cargo and crew move to and from the surface aboard ferries and landing craft.

## Open Questions

- **The high-energy chemical compound or technology.** Its name, nature and origin are undecided. It must give an exhaust velocity of roughly 8 to 10 km/s. Physically plausible candidates include stabilised metallic hydrogen, trapped atomic hydrogen and metastable helium.
