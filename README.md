# arcpy-scripts
Scripts used for various forms of analysis in ArcGIS Pro

### `Excel Column to SQL query`
This notebook provides the code the print a large number of values (e.g. site IDs) in a excel column into the format needed for a definition query in ArcPro for a field that is a Text type. The output will look something like this: `[field name] IN ('ID001', 'ID002', 'ID003', 'ID004')` 

### `FieldStats`
This notebook is for getting the sum of a field in ArcPro (e.g. total kV or total houses in an area) or the count of a value appearing in a field (e.g. how many times does a specific land use show up in a field)

### `SettlementSum`
This notebook was used to get the total about of houses proposed for each settlement. A table was exported from a layer in ArcPro and then exported to an excel workbook. This workbook was then the input to the notebook which uses pandas to group settlements together and then sum the field containing the housing units.    
