# Tsunami-Alert-System
Tsunami Alert System based on Satellite imagery (Smart India Hackathon project) 

We have taken the source of satellite imagery as the indian oceanographic site  
[Source site](https://www.incois.gov.in/portal/osf/osfCoastal.jsp?region=coastal&area=westbengal&param=swh&ln=en)

Source image:<br/>
![alt text](https://github.com/sidvsukhi/Tsunami-Alert-System/blob/master/util/seawaves.JPG "MH sea waves")

The project comprises of 2 components for alerting the Tsunami:- 
1. The image processing part which is based on image processing on the web scrapped image from the source site. It detects the tsunami tides using color analysis.
2. The Machine learning part which recognizes the probability of tsunamis caused due to remote earthquakes.

Workflow:<br/>
![alt text]( "Project workflow")
