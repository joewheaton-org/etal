---
title: UDWR - Beaver Restoration Assessment Tool (BRAT)
---

## Project Overview

### Purpose of Project:

Extend the Beaver Restoration Assessment Tool (BRAT) a cost-effective, transferable  spatially-explicit assessment tool for estimating beaver capacity and stream and riparian restoration potential across the entire state of Utah.

### Abstract:

Beaver (*Castor canadensis*) dam-building activities lead to a cascade of hydrologic, geomorphic and ecological effects that increase stream complexity, which benefits a wide-variety of aquatic and terrestrial species. Depending on biophysical and vegetation conditions present, beaver dam-building activities variously trap sediment; raise incised streambeds, often reconnecting them with their floodplains; subirrigate the valley downstream of a dam; create wetlands; slow runoff; mitigate impacts by floods; extend seasonal streamflow; increase stream complexity; extend riparian woody and other vegetation; and create or increase habitat for diverse and sometimes rare species, including amphibians, fish, small mammals, and birds. As a result, beaver are increasingly being used as a critical component of passive stream and riparian restoration strategies. Using beaver as part of a restoration design is appealing because it is much less expensive than conventional stream restoration. As long as beaver have access to sufficient water, food and construction materials they can construct dams over an incredibly diverse range of climatic and physiographic conditions spanning from desert streams to alpine meadows.  However, the capacity of the landscape to support such dam building activity can vary dramatically across these settings according to the flow regime and the availability of dam building materials.

In this pilot project, we developed a spatially-explicit model to assess the capacity of landscapes in and around streams and rivers to support dam building activity for beaver. Capacity was assessed in terms of readily available nation-wide GIS datasets to assess key habitat capacity indicators: water availability, relative abundance of preferred food/building materials and stream power at base flows versus regular floods (i.e. 2-year recurrence interval flows). Stream power was calculated using USGS regional regression equations and calibrated to determine where dams could be built based on base flow stream power and persist from year-to-year based on two-year recurrence interval stream power. Fuzzy inference systems were used to assess the relative importance of these inputs which allowed explicit incorporation of uncertainty resulting from categorical ambiguity of inputs into the capacity model. Factors that can potentially limit beaver from realizing the full capacity to support dams include: 1) ungulate grazing capacity 2) proximity to human conflicts (e.g., irrigation diversions, settlements) 3) conservation/management objectives (endangered fish habitat) and 4) projected benefits related to beaver re-introductions (e.g., repair incisions). Future work will combine these additional inputs into a more all-encompassing model, which we call the Beaver Restoration and Assessment Tool (BRAT). This pilot project represents the first phase of development of BRAT.

In the current project we build on a case study application and verification/validation data from the Escalante River watershed in southern Utah, a diverse watershed that contains riverscapes ranging from desert canyonlands and washes to wet alpine meadows. Model validation/calibration was conducted in both the Escalante and the Logan River watersheds in northern Utah, an area where beaver dam census data and correlated stream power and beaver dam establishment and persistence data exist. Results indicate that beaver capacity varies widely within both study areas, but follows predictable spatial patterns that correspond to distinct ecoregions and vegetation communities. We show how the capacity model is a tractable rapid assessment method and decision support tool for inventorying watersheds to assess beaver dam building capacity. Because the model used freely and readily available nation-wide GIS data as model inputs the model can be easily applied to other watersheds. If better quality, higher resolution inputs are used, more refined model predictions are possible. However, we illustrate how the capacity model can be used to help resource managers develop and implement restoration and conservation strategies employing beaver that will have the greatest potential to yield increases in biodiversity and ecosystem services. When this model is eventually combined in BRAT with other limiting factors and management realities, this could become part of a powerful suite of scenario building and planning tools. 

​                                                                                                           

![Escalante_River_Watershed_Hillshade_and_place_names]({{ site.baseurl }}/assets/images/Escalante_River_Watershed_Hillshade_and_place_names.png)

Figure 1. Study area map showing land status.

### Methods:

The primary driver of the model is the availability of suitable vegetation to support beaver dam building activity. The figure below illustrates how LANDFIRE data is classified, clipped and used to assess the capacity of every 250 m stream segment in the perennial drainage network to support dam building activity. 

[![Escalante_Landfire-to-veg_FIS_Alt]({{ site.baseurl }}/assets/images/Escalante_Landfire-to-veg_FIS_Alt.png)]({{ site.baseurl }}/assets/images/hr/Escalante_Landfire-to-veg_FIS_Alt.png)

After vegetation is considered, we use that as an input into an overall capacity model, which also considers the likelihood that beaver can build a dam at baseflows (2), and the likelihood of that dam to withstand typical floods (3). 

[![Escalante_Combined_FIS_Workflow]({{ site.baseurl }}/assets/images/Escalante_Combined_FIS_Workflow.png)]({{ site.baseurl }}/assets/images/Escalante_Combined_FIS_Workflow.png)

To verify model performance we can compare the model with dam surveys as shown below:

[![TempleFork_Combined_FIS]({{ site.baseurl }}/assets/images/TempleFork_Combined_FIS.png)]({{ site.baseurl }}/assets/images/TempleFork_Combined_FIS.png)

### Significance of Project:

- This project will help watershed and resource managers better assess the capacity and recovery potential of the landscape to use beaver as a conservation, restoration and climate adaptation tool.  
- The project will help scientists better forecast the influence beaver could have on our stream ecosystems should they achieve some proportion of their recovery potential.

#### BRAT Output: Escalante Watershed

<iframe src="https://www.google.com/maps/embed?pb=!1m10!1m8!1m3!1d594545.5982959252!2d-111.376648!3d37.699034!3m2!1i1024!2i768!4f13.1!5e1!3m2!1sen!2sus!4v1504990365924" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

