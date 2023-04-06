# ECSE 539 Final Project

## Tutorials used in first meeting

- <https://wiki.eclipse.org/Sirius/Tutorials/DomainModelTutorial>
- <https://wiki.eclipse.org/Sirius/Tutorials/StarterTutorial>

## Steps for current setup

- clone repo
- open eclipse with workspace as repo root
- import `basicfamily`, `.edit` and `.editor`
- open `basicfamily/model/*.genmodel`
  - right click top level entry, "generate model"
- right click on `basicfamily` project (side bar), run as, RUN CONFIGURATIONS
  - set `Location` to `${workspace_loc}/runtime`
  - click Run
  - next time this should stay configured

in runtime:
- import from `./runtime` both projects `basicfamily.sample` and `my.family.design`
- unfold the .sample, double click aird
  - double click 'Persons diagram'
  - select family, click finish, give it any name
  - this should give you all the persons in a diagram opening up.

editing and saving the diagram leads to the `.basicfamily`-file in that project being saved.

basically, sirius now acts as an editor for the xmi file `*.basicfamily`.
