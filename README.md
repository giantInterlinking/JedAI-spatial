
<p  align="center">
<img  src="https://github.com/GeoLinker/GeoLinker/blob/main/documentation/GeoLinker_compressed.gif">
</p>

# Run Parallel Experiments

See instructions [here](parallel/README.md).

# Run Serial Experiments

See instructions [here](serial/README.md).

# Run JedAI-spatial Docker

The Docker file for JedAI-spatial Web application is available [here](https://drive.google.com/file/d/11ZiiFgAh2kvcBURwTj6ozsLlAbdz3Qal/view?usp=sharing).

### Load Docker from TAR

	sudo docker load < geolinker-docker.tar 

### Execute Docker

	sudo docker run -e JAVAOPTIONS=‘-Xmx4g’ -p 8080:8080 geolinker
	
# Supported Geometry Types
- 1D Linestrings/Polylines
- 2D Polygons
