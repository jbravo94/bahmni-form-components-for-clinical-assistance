# Bahmni Form Components for Clinical Assistance

## Overview
This contribution is explained in detail here in the Bahmni OpenMRS forum:
https://talk.openmrs.org/t/contribution-link-and-image-view-components-for-clinical-assistance/38834/1

### Link Component
This is a form-control which displays a visually appealing button. The main purpose for this item should be to correctly link information like online clinical material, guides or any other website either with full url or just specifying the path.

### Image View Component
This is a form-control which displays a static hosted image. Similar to the Link component, it should help to provide knowledge references at hand. Usecases can be an assistance when classification need to be done e.g. rashes or certain quality checks must be done where images assist e.g. sample taking.

## Screenshots

### Observation Form 
[![Observation Form](screenshots/observation-form.png?raw=true "Bahmni Form")](https://www.youtube.com/watch?v=Q4enRBj3aX0 "Bahmni Form")

### Implementer Interface
[![Implementer Interface](screenshots/implementer-interface.png?raw=true "Implementer Interface")](https://www.youtube.com/watch?v=Q4enRBj3aX0 "Implementer Interface")

## Source Code

### Form Controls
Actual form controls needed for Bahmni form and implementer interface

https://github.com/Bahmni/form-controls/pull/83

### Implementer Interface
The dedicated designer components from-controls must be integrated and compiled into implementer interface

https://github.com/Bahmni/implementer-interface/pull/96
