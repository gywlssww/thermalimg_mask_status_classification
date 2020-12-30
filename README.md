### Thermal numpy extraction from flir img file
- pip install flirimageextractor
```
fir = flir_image_extractor.FlirImageExtractor()
fir.process_image('./thermal.JPG')
proper_np=fir.get_thermal_np()
``` 

