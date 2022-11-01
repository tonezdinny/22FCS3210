# Instructions 

Consider a college scenario where faculty, students, and visitors have controlled access to a lab during week and weekend days to encode the following facts:  

```
Xavier and Brandi are faculty
Harvey, Ariel, Charlie, and Dan are students 
Laverne and Ramon are visitors
Dan is advised by Xavier while Ariel is advised by Brandi
```

Next, encode the following rules: 

```
faculty and students have access to the lab during business days (Monday-Friday); 
only faculty or students currently being advised by faculty have access to the lab during the weekends.  
```
 
Finally, have Prolog answer the following queries:  

```
Is Xavier a student?  
Is Dan a student?  
Is Brandi a faculty?  
Is Ariel a visitor?  
Does Xavier have access to the lab during business days?  
Does Harvey have access to the lab during business days?  
Does Laverne have access to the lab during business days?  
Does Xavier have access to the lab during the weekend?  
Does Harvey have access to the lab during the weekend?  
Does Dan have access to the lab during the weekends?  
Does Laverne have access to the lab during the weekends?   
Who is Ariel’s advisor?  
Who has access to the lab during business days?  
Who has access to the lab during the weekends?  
```