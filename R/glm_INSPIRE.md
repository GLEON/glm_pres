<style type="text/css">
.indent {
  padding-left: 2em !important;
}

.centered {
  width: 100%;
  margin-left: auto;
  margin-right: auto;
  text-align: center;
}

.large {
  font-size: 1.2em !important;
  line-height: 64px !important;
}


</style>
Lake modeling workshop
========================================================
author: Jordan S Read, Paul C Hanson, Hilary Dugan, Craig Snortheim
font-family: 'Helvetica'
width: 1440
height: 900



GLM overview
====================================
id: slide1
type:section


GLM overview
====================================
type:sub-section
more stuff

GLM overview
====================================
type:prompt
more stuff

Why R?
====================================
more stuff

GLMr
========================================================
type:section

<div class="indent large">GLMr R package</div>
<div class="indent large">Maintainer: Luke A Winslow  </div>
<div class="indent large">Authors: Luke A Winslow, Jordan S Read  </div>
<div class="indent large">Location: <a target="_blank" title="glmtools on github" href="https://github.com/GLEON/GLMr">https://github.com/GLEON/GLMr</a></div>

GLMr holds the current version of the "General Lake Model",  
and can run the model on all platforms (windows, mac, linux)

GLMr
========================================================
incremental: false
type:prompt
left: 50%

<div style="text-align: center; width: 100%;"><span class=large>GLMr Code in R:</span></div>


```r
library(GLMr) 

glm_version()

nml_template_path()
```

***
<div style="text-align: left; width: 100%;"><span class=large>   Explanation</span></div>

 - load the GLMr package in R  

 - get the current version of GLM  
    
 - find the included example glm.nml  

GLMr
========================================================
incremental: false
type:prompt
left: 50%
id: sectionRun

<div style="text-align: center; width: 100%;"><span class=large>GLMr Code in R:</span></div>


```r
run_glm(sim_folder)
```


```r
Reading config from glm.nml
No WQ config
No diffuser data, setting default values
---------------------
| GLM Version 1.4.0 |
---------------------
nDays 32767 timestep 86400.000000
Simulation begins...
Running day  2455806, 100.00% of days complete

---------------------
     Run Complete

```

***
<div style="text-align: left; width: 100%;"><span class=large>   Explanation</span></div>

 - Run the GLM model on your computer
 
GLMr
========================================================
incremental: false
type:prompt
left: 60%
<div style="text-align: center; width: 100%;"><span class=large>GLMr Code in R:</span></div>

































```
Error in citation("GLMr") : package 'GLMr' not found
```
