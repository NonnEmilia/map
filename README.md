# map
Is a leaflet map of water wells surved in 1st rasmata onlus - H2OpenMap mapping campaig in Burkina Faso.
- leaflet library
- multiple layers
- custom icons
- data and photos in pop up

See how it work on www.h2openmap.org/map

###done stuff:

- data are taken from internal SqLite database and dinamically from OSM by Overpass Turbo query
- basemap option include Satellite Google view
- icons are dinamically selected due to data
- popup show downloadPDF link
- draw instrument to determine distances
- download csv for internal database


###ToDo list:

- better PDF
- insert if/else in overpass turbo query to do not display data already showed by internal db
- pass protected edit form for internal data
- convert draw tool in measurement instruments ( see issues)
- add two heatmaps, one for drinking_water=yes, one for drinking_water=no




