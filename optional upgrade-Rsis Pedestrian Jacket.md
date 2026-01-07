Photon Ember Rsis Pedestrian Jacket — Usage Canvas
PhotonEmber™ Expedition Jacket — RSIS Pedestrian Visibility Canvas
Purpose of This Canvas

This canvas explains how the original PhotonEmber Solar Ember Jacket blueprint is used inside 
the RSIS ecosystem, focusing on the RSIS Pedestrian Coat (PC‑1) upgrade.

The jacket does not provide voice communication. Instead, it functions as a 
low‑energy, solar‑sustained GPS presence node that makes the wearer visible to RSIS‑enabled vehicles and infrastructure.

1. Role Definition Inside RSIS

RSIS Actor Type:

Pedestrian / Vulnerable Road User (VRU)

What the jacket wearer is:

A passive safety beacon

A moving geospatial signal, not a communicator

A non‑interactive participant in RSIS

What the jacket wearer is NOT:

Not a talker

Not a controller

Not required to use a phone

2. Core Upgrade: RSIS Micro‑Module (Jacket Edition)

Integrated into the PhotonEmber power and routing architecture.

RSIS PC‑1 Module (Jacket)

GNSS Micro‑GPS (low‑power, burst‑fix)

BLE 5.x Beacon (ephemeral presence)

Optional UWB (distance refinement)

IMU (walk / stop / cross detection)

Secure Element (rotating pseudonymous tokens)

No microphone. No speaker.

3. Energy Model — Photon‑Sustained Operation

The RSIS module draws from a dedicated low‑noise 3.3V rail supplied by:

OPV solar textiles (photon capture)

Dual LiFePO₄ battery buffers

Smart regulator (priority‑aware)

GPS Energy Behavior

GPS wakes only in:

Movement

Crosswalk‑like patterns

RSIS query windows

Sleeps indoors or when stationary

Result:

Under daylight conditions, the RSIS GPS operates in a net‑energy‑neutral state.

4. What Other RSIS Users See
Vehicles / RSIS Nodes Receive:

“Pedestrian detected — Jacket PC‑1”

Heading + speed estimate

Risk‑weighted priority (VRU > vehicle)

Visualization Example:

Map tile shows moving pedestrian glyph

Color shifts with Time‑to‑Conflict (TTC)

The jacket wearer does not receive alerts — only vehicles adapt.

5. Safety Logic (Passive‑Only)
Event	Jacket Action	RSIS Network Action
Walking	Periodic BLE + GPS burst	Vehicles slow awareness
Crossing intent	IMU pattern flag	Crosswalk alert pushed
Vehicle approaching fast	None	Vehicle warned
Collision risk	None	Vehicle braking / reroute

This preserves zero distraction for the wearer.

6. Privacy & Identity Model

No persistent ID broadcast

Tokens rotate every 10–20 minutes

No audio, no biometrics

No cloud account required

The jacket appears as:

“Anonymous Pedestrian Safety Node”

7.  No Mic / No Speaker 

This RSIS upgrade is intentionally one‑way:

Reduces cognitive load

Eliminates surveillance concerns

Prevents alert fatigue

Enables ultra‑low power operation

The jacket is seen, not heard.

8. System Positioning Summary

The PhotonEmber RSIS Pedestrian Jacket becomes:

🌞 Solar‑powered

📡 GPS‑anchored

🧠 AI‑interpreted

🛑 Safety‑prioritized

🔒 Privacy‑preserving

It is a foundational VRU node for RSIS — enabling safer roads without changing human behavior.

Final Statement

The PhotonEmber Expedition Jacket with RSIS PC‑1 upgrade transforms a pedestrian into a visible, 
energy‑sufficient safety participant within a multi‑agent road intelligence system — without requiring interaction, 
communication, or attention from the wearer.
