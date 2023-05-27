# google-earth-annotation
annotation tasks, particularly focused on working with RGB images.
Annotation Guidelines:

Only annotate RGB images; other visualizations are for reference only.
Black images (dark with objects) should be annotated, even if visible in other visualizations.
Ignore black areas and areas smaller than 10 pixels.
Annotate objects in shadows based on what is visible in the light.
Ensure annotations cover the edges/boundaries of objects accurately.
Utilize false color, NDVI, and water index for specific identification purposes.
Avoid duplicate annotations for the same object.
Object Visibility in Different Modalities:

Buildings are better seen in RGB and false color.
Vegetation is more visible in false color and NDVI modalities.
Water sources are easily visible in the water index and NDVI modalities.
Specific Considerations:

Do not annotate walls (fences) around buildings, focus on the buildings themselves.
NDVI visualization aids in identifying river edges and isolating them from tree shadows.
Be cautious of false colors that might confuse object identification.
Do not annotate bare soil without vegetation.
Validate annotations using different visualizations to avoid misclassification.
If unable to identify an object conclusively, refrain from annotating.
Objects smaller than 10 pixels should not be annotated.
Use the NDVI modality to check for vegetation in shadows.
Football and playing fields should not be annotated as grassland.
Tree Annotation:

Tree shadows are taller and darker than shadows of other vegetation.
Trees appear leafier and have a dark-green color in the NDVI modality.
Annotate entire images with homogeneous tree cover using one large tree annotation.
For images with both tree cover and other objects, use overlapping annotations.
Annotation of Other Interfering Vegetation:

Other interfering vegetation is shorter than trees but taller than grassland.
Use one large annotation for images with only other interfering vegetation.
Use the overlapping rule for images with both interfering vegetation and other objects.
