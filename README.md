# Callitri

## Planet Day/Year Simulator

An interactive educational applet that demonstrates how Earth's orbital position and axial tilt angle affect day/night cycles and seasons at different latitudes.

### Features

- **Orbital View**: Visual representation of Earth's position around the sun with adjustable axis orientation
  - **Yellow axis bar**: Shows Earth's rotational axis - you can adjust its angle to see how tilt affects seasons
  - **Day/night terminator**: Dark overlay shows the hemisphere facing away from the sun
  - **Red marker**: Fixed observation point showing your selected latitude (doesn't move with orbit or axis rotation)
- **Interactive Controls**:
  - **Orbital Position slider**: Move Earth around its orbit (0-360°)
  - **Latitude selector**: Pick any latitude from South Pole (-90°) to North Pole (90°)
  - **Axial Tilt Angle slider**: Adjust the orientation of Earth's rotational axis (yellow bar)
- **Sky View**: Real-time visualization of the sun's position in the sky at solar noon for your selected latitude
- **Live Calculations**:
  - Day length (including polar day/night)
  - Solar declination
  - Sun altitude and azimuth
  - Current season
  - Day/Night/Twilight status

### Usage

Simply open `planet-simulator.html` in any modern web browser. No installation or dependencies required!

### How It Works

The simulator lets you explore the geometry of Earth-Sun interactions:
- **Orbital Position**: Where Earth is in its orbit around the sun
- **Axial Tilt Angle**: The orientation of Earth's rotational axis (yellow bar) in the orbital frame
- **Solar Declination**: Calculated from the angle between the axis and the sun direction
- **Day Length**: Determined by latitude and solar declination
- **Sky View**: Shows the sun's position at solar noon for the selected latitude

Perfect for learning about:
- How axial tilt orientation creates seasons
- Why day length varies with latitude and season
- The relationship between axis angle and solar declination
- Midnight sun and polar night phenomena at extreme latitudes
- The geometry behind equinoxes (axis perpendicular to sun) and solstices (axis tilted toward/away from sun)
