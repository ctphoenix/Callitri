# Callitri

## Planet Day/Year Simulator

An interactive educational applet that demonstrates how Earth's orbital position and axial tilt affect day/night cycles and seasons at different latitudes.

### Features

- **Orbital View**: Visual representation of Earth's position around the sun throughout the year
  - **Yellow axis bar**: Shows Earth's rotational axis - maintains constant orientation in space (this is what causes seasons!)
  - **Day/night terminator**: Dark overlay shows the hemisphere facing away from the sun
  - **Red marker**: Indicates your selected latitude at the subsolar meridian (only moves with latitude slider)
  - **Cyan dot**: Rotation indicator on the equator (shows planet rotation as you change the rotation angle)
- **Interactive Controls**:
  - Orbital Position slider: Choose any day of the year (0-360°)
  - Latitude selector: Pick any latitude from South Pole (-90°) to North Pole (90°)
  - Planet Rotation Angle: Rotate the planet to see different times of day (0° = solar noon, 180° = midnight)
  - Play/Pause: Animate the planet's rotation through a complete day
- **Sky View**: Real-time visualization of the sun's path across the sky
- **Live Calculations**:
  - Day length (including polar day/night)
  - Solar declination
  - Sun altitude and azimuth
  - Current season
  - Day/Night/Twilight status

### Usage

Simply open `planet-simulator.html` in any modern web browser. No installation or dependencies required!

### How It Works

The simulator uses accurate astronomical calculations including:
- 23.5° axial tilt
- Solar declination based on orbital position
- Hour angle calculations for sun position
- Altitude and azimuth computations

Perfect for learning about:
- Why seasons occur
- How day length varies with latitude and season
- The path of the sun through the sky
- Midnight sun and polar night phenomena
- Equinoxes and solstices
