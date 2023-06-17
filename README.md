# test-data
Test Data for GeoTIFFs

- Sea Ice Concentrations from [National Snow and Ice Data Center](https://nsidc.org/data/nsidc-0051) via https://github.com/GeoTIFF/georaster-layer-for-leaflet/issues/47#issuecomment-716449294
- Sample GeoTIFF from OSGEO, GeogToWGS84GeoKey5.tif, via https://download.osgeo.org/geotiff/samples/GeogToWGS84GeoKey/
- Export from the [Global Agricultural & Disaster Assessment System (GADAS)](https://geo.fas.usda.gov/gadas) by the USDA - Foreign Agricultural Service (translated from PNG to TIF using gdal_translate)
- Cloud-Optimized GeoTIFF from [Australian Antarctic Program](https://www.antarctica.gov.au/) via https://github.com/GeoTIFF/georaster-layer-for-leaflet/issues/105.  Original URL for the data was: https://public.services.aad.gov.au/datasets/science/voyage_202122020/multibeam/GA-4886/L3/4886_VanderfordGlacier/32Bit_Geotifs/GA4886_VanderfordGlacier_2022_EGM2008_64m-epsg3031.cog
- Global Landcover/Cropland from [OpenLandMap](https://openlandmap.org/) via https://gitlab.com/openlandmap/global-layers/-/blob/f1871cf086a713994c9f6386569a0f761246b4f7/tutorial/OpenLandMap_COG_tutorial.md
- GeoTIFF with ModelTransformation and no ModelPixelScale originally via https://github.com/geotiffjs/geotiff.js/issues/40
- [SAR](https://en.wikipedia.org/wiki/Synthetic-aperture_radar) Image of [Mount Yasur](https://en.wikipedia.org/wiki/Mount_Yasur) from [Umbra Space Open Data Program](https://umbra.space/open-data).  Discussed here https://github.com/stac-utils/stac-layer/issues/61.  Downloaded via [stac-browser](https://radiantearth.github.io/stac-browser/#/external/s3.us-west-2.amazonaws.com/umbra-open-data-catalog/stac/2023/2023-02/2023-02-12/6d584f33-0489-47dd-9412-14d2c83532fc/6d584f33-0489-47dd-9412-14d2c83532fc.json?.asset=asset-GEC) and clipped using `gdal_translate 2023-02-12-21-33-56_UMBRA-04_GEC.tiff -srcwin 4000 3000 2000 2000 umbra_mount_yasur.tiff`. Provided under [CC-by-4.0](https://creativecommons.org/licenses/by/4.0/).  This image uses UTM with a GeoTransform.
- Global Map of Total Area of Harvested Wheat by MapSPAM
