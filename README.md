# ECSE 539 Final Project

## Tutorials used in first meeting

- <https://wiki.eclipse.org/Sirius/Tutorials/DomainModelTutorial>
- <https://wiki.eclipse.org/Sirius/Tutorials/StarterTutorial>

## Getting Started with Development

Always open eclipse with workspace `./HomeManagementSystem`.

To import projects, use **File -> Import -> Existing Projects into Workspace** and then pick the workspace itself as search directory.

### Steps for SIRIUS DEVELOPMENT

- import `HMS` project
- generate **model**, **edit**, and **editor** from `HMS/model/hms.genmodel`
- right click `HMS` -> run as, eclipse application

- new eclipse opens in directory `./runtime-eclipseApplication`
- import `HomeViewpointSpecification` and `sample.hms` projects
- to check functionality, open `sample.hms/representations.aird/.../sample HMS Diagram`

A diagram with an example-house should be displayed.

### Steps for ATL DEVELOPMENT

- import `HMS`, `ATL.HMS`, `seg.jUCMNav`, `ca.mcgill.sel.core`  projects
- make sure that `input/example.home.hms` is present
- right click on `runconfigs/example.home.launch` -> run as -> example.home
  - or (if shown) click on the drop down menu at the green arrow at the top (-> run as) -> example.home

