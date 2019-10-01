# The Seas of Plastic | http://dumpark.com/seas-of-plastic-infographic/

[img-1]: https://raw.githubusercontent.com/vk-webdesign/cp2/master/00-Deconstructions/03b__seas-of-plastic-infographic/img/img-1.png "img-1"
[img-2]: https://raw.githubusercontent.com/vk-webdesign/cp2/master/00-Deconstructions/03b__seas-of-plastic-infographic/img/img-2.png "img-2"
[img-3]: https://raw.githubusercontent.com/vk-webdesign/cp2/master/00-Deconstructions/03b__seas-of-plastic-infographic/img/img-3.png "img-3"
[img-4]: https://raw.githubusercontent.com/vk-webdesign/cp2/master/00-Deconstructions/03b__seas-of-plastic-infographic/img/img-4.png "img-4"
[img-5]: https://raw.githubusercontent.com/vk-webdesign/cp2/master/00-Deconstructions/03b__seas-of-plastic-infographic/img/img-5.png "img-5"


#### Description
The Seas of Plastic is an infographic hosted on the web which shows ocean plastic pollition. The infographic uses data from:

"Numerical modelling of floating debris in the world’s oceans Marine Pollution Bulletin, Volume 64, Issue 3, March 2012, Pages 653-661. L.C.-M. Lebreton, S.D. Greer, J.C. Borrero"

The infographic is broken down into two parts.

One, a 3d-illustrated globe with static information display. Two, a bar-graph showing a spacial amount of plastic ocean waste categoriezed into country of origin and a the Gyre where the plastic waste winds up.

#### Deconstruction
This deconstruction will assume the 3d-illustrated globe is built using data rather than an illustration.

##### Globe
The globe graphic shows plastic particle collection densities by location.

UI - four collumn grid. col-1 includes description, map key, and source. col-2, col-3, col-4, includes 3d-globe and about section.

Database - information collected from "Numerical modelling of floating debris in the world's oceans".

Globe - 3d-model with a map to translate real world data location to 3d-model. Ocean colors mapped to real world data of plastic particle concentration. Point colors mapped to real world data of coastal population pressure. Line markers mapped to ocean current directions.

Click n' drag - functionality added to rotate 3d-model of globe.

Gyres - secondary infographic representing amount of platic particle within gyre.

Gyre (click) - rotates the globe model to point of gyre.

##### Source
The source infographic shows plastic particle's sourses by country of origin and plastic particle's destination.

Data - Percentatge of total plastics are mapped to country of origin and a visual representation of height. Percentate of total plastics from country of origin to resulting gyre. Bezier curve equasion for line connecting country of origin and gyre. Color selection for each country.

Country of Oragin (click) - click functionality to show plastic particle data from selected country.

Gyre (click) - click functionality to show oragin of plastic particle data from within selected gyre.


Reference-style: 
![alt text][img-1]
![alt text][img-2]
![alt text][img-3]
![alt text][img-4]
![alt text][img-5]