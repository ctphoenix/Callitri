# Callitri

## Planet Day/Year Simulator

An interactive educational applet that lets you explore a complete day and year on Earth, showing how orbital position, axial tilt, and time affect the sun's position at any latitude.

### Features

- **Orbital View**: Visual representation of Earth's position around the sun with adjustable axis orientation
  - **Yellow axis bar**: Shows Earth's rotational axis - adjust its angle to see how tilt affects seasons
  - **Day/night terminator**: Dark overlay shows the hemisphere facing away from the sun
  - **Red marker**: Fixed observation point at your selected latitude

- **Interactive Controls**:
  - **Day of Year (0-29)**: Scrub through a simplified 30-day year to see seasonal changes
  - **Axial Tilt Angle**: Adjust the orientation of Earth's rotational axis (yellow bar)
  - **Latitude**: Pick any latitude from South Pole (-90°) to North Pole (90°)
  - **Hour of Day (0-24)**: Scrub through a complete day or use "Play Day" to animate it

- **Sky Chart (Azimuth × Altitude)**: Full panoramic view of the sun's position
  - **X-axis**: Complete 360° horizon (North → East → South → West → North)
  - **Y-axis**: Altitude from horizon (0°) to zenith (90°) directly overhead
  - **Sun path**: Dashed line shows the sun's trajectory throughout the day
  - **Current position**: Bright marker shows where the sun is right now

- **Live Calculations**:
  - Day length (including polar day/night phenomena)
  - Solar declination
  - Sun altitude and azimuth angles
  - Current season
  - Day/Night/Twilight status

### Usage

Simply open `planet-simulator.html` in any modern web browser. No installation or dependencies required!

### How It Works

The simulator uses accurate astronomical calculations to show Earth-Sun geometry:
- **Day of Year**: Controls orbital position (each day = 12° of orbit in simplified 30-day year)
- **Axial Tilt Angle**: The orientation of Earth's rotational axis in the orbital frame
- **Hour of Day**: Controls rotation, affecting which longitude faces the sun
- **Solar Declination**: Calculated from the angle between the axis and sun direction
- **Sun Position**: Altitude and azimuth computed from latitude, declination, and hour angle

Perfect for learning about:
- How axial tilt orientation creates seasons
- Why the sun rises and sets at different points on the horizon throughout the year
- How day length varies with latitude and season (watch it change as you scrub through the year!)
- The sun's path across the sky at different latitudes and seasons
- Midnight sun and polar night phenomena at extreme latitudes
- The geometry behind equinoxes (axis perpendicular to sun) and solstices (axis tilted toward/away from sun)

### Tips

- **Watch a day**: Set your latitude and day of year, then press "Play Day" to watch the sun move across the sky
- **Watch a year**: Slowly scrub the "Day of Year" slider while watching how the sun's path changes
- **Explore extremes**: Try latitude 66° (Arctic Circle) at different days to see when polar day/night occurs
- **Find equinoxes**: Adjust the axis angle until the sun rises due east (90°) and sets due west (270°)
