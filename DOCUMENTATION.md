Not gonna try TOO hard on this, just to keep us up to date internally

### Data storage for trails:
- Trail name (str) *
- Unique ID (int, only stored internally)
- Length (float, in miles) *
- Elevation gain (int, in feet) *
- Trail type (point to point, loop, out&back, etc) *
- Starting elevation (int, in feet)
- Trail roughness (int out of 10, subjective rating)
- Opening hours (idk what to store this as)
- Estimated time (float, in hours, +- 50%)
- Description (str, max of 2000 chars)
- Location (tuple (float, float), gps coordinate) *
- Surfaces (dirt, rocks, asphalt, etc multiselect)
- Associated org (e.g. mt rainier natl park)
- Biomes (forest, river, mountain rock etc)
- Images (list of str for links)
* = mandatory in the entry field