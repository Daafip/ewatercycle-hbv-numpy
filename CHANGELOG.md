## Changelog

### v1.0.0
working basic version after various testing [versions](https://test.pypi.org/project/ewatercycle-HBV/)
#### v1.1.0
upgrade to new version: added support for updating memory vector on the fly for Data assimilation
##### v1.1.1
Fixed bug with Tlag and setting memory vector correctly 
##### v1.1.2
Adding `.finalize()` method - clears up the directory. Especially useful for DA. 
### V1.2.0
- pretty big issue with setting values fixed - won't affect most use but will cause issues for Data Assimilation
- use opportunity to name all HBV packages/naming/images to 1.2.0 
### V1.3.1
- now supports camels.txt files natively. Just download the ones you want from there and add it. 
- make sure you also include the alpha value which is a model output from the run, defaults to 1.26 but varies per catchment. Eq1 of camels paper.
### v1.3.2. - 1.3.3
- now correctly slices the ds to given start and end time whoops
### v1.3.4 - 1.3.9
- formalises forcing: either `.txt`  or (two) `.nc` forcing supplied & run corresponding code