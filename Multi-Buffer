#paste this inside ArcMap python console
import arcpy
# Replace a layer/table view name with a path to a dataset (which can be a layer file) or create the layer/table view within the script
# The following inputs are layers or table views: "t1_1_1"

#assigning variables
buff100='100 Meters'  #give your required value
buff200='200 Meters'
buff300='300 Meters'
#creating a list of buffer distances
bufferlist=[buff100,buff200,buff300]
#creating loop
for buff in bufferlist:
    arcpy.Buffer_analysis(in_features="t1_1", out_feature_class="C:/Users/Design-1/Desktop/Junk/Road_Buffer"+str(buff), buffer_distance_or_field=buff, line_side="FULL", line_end_type="ROUND", dissolve_option="NONE", dissolve_field="", method="PLANAR")
