FIREIMMUNE TISSUE RESOURCE

by narhiril






---

This resource was designed to allow for more easily fireproofing a select caste of a single creature.  Since 0.34 was released, 
it is no longer possible to modify creature materials at caste level, so this resource adds a bunch of copies of standard materials 
with different names and fire-immune properties.


--
TO INSTALL:

Drag and drop the contents of the "objects" folder into your own df\raw\objects folder.



--
TO USE THESE TEMPLATES IN YOUR OWN CREATURES


Define the body of your creature at caste level (use [SELECT_CASTE] and [SELECT_ADDITIONAL_CASTE]).  For the fireimmune caste(s), when you define 
their bodies, use the following tokens (where applicable).

	[BODY_DETAIL_PLAN:FIREIMMUNE_ADDITIONAL_MATERIALS]
	[BODY_DETAIL_PLAN:FIREIMMUNE_ADDITIONAL_TISSUES]
	[BODY_DETAIL_PLAN:VERTEBRATE_TISSUE_LAYERS_FIREIMMUNE:SKIN_FIREIMMUNE:FAT_FIREIMMUNE:MUSCLE_FIREIMMUNE:BONE_FIREIMMUNE:CARTILAGE_FIREIMMUNE]


For additional materials and non-uniform tissues that need definitions, replace the usual something like...


	[USE_MATERIAL_TEMPLATE:NAIL:NAIL_TEMPLATE]
	[USE_TISSUE_TEMPLATE:NAIL:NAIL_TEMPLATE]
	[TISSUE_LAYER:BY_CATEGORY:FINGER:NAIL:FRONT]
	[TISSUE_LAYER:BY_CATEGORY:TOE:NAIL:FRONT]


...with...

	[USE_MATERIAL_TEMPLATE:NAIL_FIREIMMUNE:NAIL_FIREIMMUNE_TEMPLATE]
	[USE_TISSUE_TEMPLATE:NAIL_FIREIMMUNE:NAIL_FIREIMMUNE_TEMPLATE]
	[TISSUE_LAYER:BY_CATEGORY:FINGER:NAIL_FIREIMMUNE:FRONT]
	[TISSUE_LAYER:BY_CATEGORY:TOE:NAIL_FIREIMMUNE:FRONT]


All of the material and tissue templates are named identically to their vanilla counterparts, just with "TEMPLATE" replaced by "FIREIMMUNE_TEMPLATE"

NOTE: As these files are pulled from Legends of Forlorn Realms, there may be some vanilla material and tissue templates that are not defined simply because they were not needed 
by LFR.  If your creature needs an additional template, take a look at how the included files are written, and if that doesn't help you make your own, drop me a PM (narhiril at bay12forums).