Triple Ten Project 4 Stage 2 "Around The US"

Project 3 Walkthrough
https://drive.google.com/file/d/139kcQdMhVcHj6eFEcsLL6P6sMpX-CInc/view?usp=sharing

GitHub repository:
https://github.com/gmwgm8/AroundTheUS_FINAL.git


Rough Description:

This project implemented adaptive tools to allow the website to adjust to three different screen sizes.
The desire was to smoothly transition from Desktop, Tablet to Mobile while shrinking the browser window. 
To accomplish this, we utilized the @mediaquery tool and specified the screen size limits for Tablet and Mobile only. 
This is because Desktop screen size is the default. We also utilized Grid instead of Flexbox to allow the cards of the same size
to fall into desired alignment and spacing. We used Figma for the first time in detecting the desired margins and spacing of website features within desktop
and mobile screen sizes, tablet spaces were more or less inherited from the desktop styles along with a bit of my own determinations. 
Using Figma I did encounter some issues with calling out too many margins and spaces, but tutors did help me to weed these out. 

Now in Sprint 4 we've begun implementing Javascript using the tools "Array" and "Object" which are on small display here. 
The start of responsive modal (pop-up form) to allow editing of the name and description of the around the world site. 
Also, a @mediaquery to modify this popup in a mobile screen size.

Javascipt was implemented to open and close the Responsive Modal used to edit the profile. In the final stage we've begun using javascript to prevent the page
from reloading upon clicking the save button in the modal as well beginning work on creating and editing new cards for the profile from a template. 


New cards:

Place: Mammoth Caverns

Image URL: https://images.unsplash.com/photo-1654179859807-619e4d0201f4?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTR8fE1hbW1vdGglMjBDYXZlcm5zfGVufDB8fDB8fHww

Place: Sedona

Image URL: https://images.unsplash.com/photo-1592249797396-311ed9d417f3?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Nnx8U2Vkb25hfGVufDB8fDB8fHww

Place: Mesa Verde

Image URL: https://images.unsplash.com/photo-1581540529586-e28d24840327?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Nnx8TWVzYSUyMFZlcmRlfGVufDB8fDB8fHww


Project 6:

Form validation for the Add New Card and create profile modals:

Prevents saving of profile or creation of cards unless character limitations for entries and ensuring that fields are not blank. 

Increasing user friendliness of modals by allowing them to close by pressing ESC or clicking outside modal planes. 

