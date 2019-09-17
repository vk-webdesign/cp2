# North Korea Missle Test Visualization
https://nagix.github.io/nk-missile-tests/

## Globe
A 3D model of the globe

drag and drop function to rotate globe from centerpoint

zoom-in/zoom-out funtion mapped to mouse or trackpad scroll

a translator to map GPS coordinates to related pixels

## Database
A JSON file for every missle launched by North Korea with data of missle name, date-of-launch, test outcome, launch facility name, landing location, apogee (distance of furthest point from Earth),  distance traveled, description.

object names use data of missle-type and date-of-launch

## Visualization
zoom-in/zoom-out, buttons linked to globe model

pan-up/pan-down, buttons linked to globe model

search-bar and button, requires text input search is linked to JSON missle database, specifically object name

visualization of missle launch, uses data entry of launch origin coordinates or site, missle landing location and apogee to create a bezier curve

visualization of missle launch animation, along bezier curve

visualization of database entry, text-label of database entry placed on globe model related to launch-site

visualization of database entry, text-labels do not overlap

click function, opens a lightbox of information drawn from JSON databse

## Filters
success/failure/unknown buttons, which display or hide missle data depending on test outcome in JSON file

year slider, filters missle data depending on year

missle type checkboxes, show/hide missle data on visualizer depending on missle type
