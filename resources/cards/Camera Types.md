# Camera Types

## Frame-based Cameras

- Fixed rate
  - High-speed scenes / dynamic range environments
  - Leads to motion blur

## Spiking Cameras

- Bio-inspired
- Each pixel on a spiking camera sensor:
  - Captures the incoming photons **independently and persistently**
  - Triggers a **spike** only when the accumulated photons **reach a dispatch threshold**
- Continues spike stream & high temporal resolution
- To fit spike data to Transformer, we present an input spike embedding equipped with a spatio-temporal patch partition module to maintain features from both spatial and temporal domains.

## Event Camera

- Only records the **relative brightness changes** at each pixel

## Event vs Spike

- Spike: Absolute light intensity, both **static & dynamic** information
