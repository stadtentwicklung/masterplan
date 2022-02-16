# :world_map: Masterplan Cottbuser Ostsee 3.0
:white_check_mark: Georeferenziertes Rendering (Rasterbild) erstellen und als Web-Map publizieren mit Standortermittlung.

### :computer: Link [https://github.com/stadtentwicklung/map1)

This link above shows the original repository with a detailed README with more material of how to create such a map in GIS on desktop.

Here are some new information provided about the render-pipeline and the raster-look.   

### :camera_flash: Webmap 2.0: [https://stadtentwicklung.github.io/masterplan/]
![Screenshot der GitHub-Pages App](https://raw.githubusercontent.com/stadtentwicklung/masterplan/master/img/update.JPG)

### :camera_flash: Webmap 1.0: [https://stadtentwicklung.github.io/map1/]
![Screenshot der GitHub-Pages App](https://raw.githubusercontent.com/stadtentwicklung/map1/master/img/screenshot.JPG) 

## :rocket: Rendering in detail:

### 1. The original georeferenced vector plan is saved as a raster image (you can see a piece of the whole plan in two versions: (1) no streets and (2) with classified street infrastructure. (I wanted to know what looks better at the end: (A) streets from the vector plan on top or (B) streets included in the render-process.)   

![screenshot raster image](https://raw.githubusercontent.com/stadtentwicklung/masterplan/master/img/01_plan_raster.png)

### 2. The next step is to organize the elevation maps for the render-loop. That are the files, which "bumps" the plan to a 2,5D-landscape, which can be logical illuminated with light and shadows. I found three possibilities:

1. digital surface model (bDOM in german):     

![digital surface model](https://raw.githubusercontent.com/stadtentwicklung/masterplan/master/img/00_1_bDOM_to_normalmap.png)

2. digital terrain model (DGM in german):

![digital terrain model](https://raw.githubusercontent.com/stadtentwicklung/masterplan/master/img/00_2_dgm_to_normalmap.png)

3. making a manual generated model (MGM):

![manual generated model](https://raw.githubusercontent.com/stadtentwicklung/masterplan/master/img/00_3_greymap_to_normalmap.png)

The MGM is a map in grey colors directly changed in the colored original vector plan. Photoshop transform all these pieces automatically in a "Normalmap" for elevation information. I wanted to find out which of these will bumps the plan best.

### 3. The last task is to fix it together. Every Normalmap will bump the plan individual.

1. Bumping with bDOM (left), DGM (middle) and both (right):

![manual generated model](https://raw.githubusercontent.com/stadtentwicklung/masterplan/master/02_render_bdom_dgm_both.png)

2. Bumping with MGM (left) and mixed MGM with DGM (right):

![manual generated model](https://raw.githubusercontent.com/stadtentwicklung/masterplan/master/img/03_render_mem_mem-dgm.png)

3. Bumping the version with streets as mentioned above. The right result is the rendering of the final map: Buildings and streets has visible shadows because of the MGM, the surface has details because of the DGM.

![manual generated model](https://raw.githubusercontent.com/stadtentwicklung/masterplan/master/img/04_render_mem_mem-dgm.png)

## :computer: See the result here: [https://github.com/stadtentwicklung/masterplan/]

### :coffee::coffee::coffee: by [Stefan](https://github.com/stefanstoehr)
