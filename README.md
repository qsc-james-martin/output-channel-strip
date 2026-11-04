# Output Channel Strip

## Put common output processing and metering in one Q-SYS component.

Building an output chain from separate blocks takes space and spreads controls
and meters across the design. Output Channel Strip combines gain, delay,
filtering or shelving, EQ, limiting, and signal-path metering in one
configurable component.

## Signal path

`Input → Gain → Delay → Low section → EQ → High section → Peak Limiter → Output`

Gain, delay, and peak limiter are available in the chain. Set the Low and High
sections to a shelf, filter, or Off; choose parametric EQ, graphic EQ, or Off.
Processing stages default to bypass, while Gain is active. The channel count
is configurable from 1 to 8.

## Pages and metering

- **Strip** presents the processing sections in signal order, with meters
  before the first section and after every section.
- **EQ** provides the Low/EQ/High controls and a live response graph when at
  least one of those sections is enabled.
- **Single Meter** (on by default) shows the loudest channel at each tap.
  Turn it off for separate meters per channel; audio is never summed.

Use the plugin properties to set channel count, maximum delay, section types,
filter slopes, and EQ configuration. Parametric EQ supports 1–16 bands;
graphic EQ supports 6, 11, 16, or 31 bands. The response graph is a calculated
approximation of the configured response, not a measurement.
