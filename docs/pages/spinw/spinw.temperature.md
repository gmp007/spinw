---
{title: spinw.temperature( ), summary: get/set stored temperature value, keywords: sample,
  sidebar: sw_sidebar, permalink: spinw_temperature.html, folder: spinw, mathjax: 'true'}

---
 
TEMPERATURE(obj, T)
 
If T is defined, it sets the temperature stored in obj object
to T, where T is scalar. The units of temerature is
determined by the spinw.unit.kB value, default is Kelvin.
 
T = TEMPERATURE(obj)
 
The function returns the current temperature value stored in
obj.
 
