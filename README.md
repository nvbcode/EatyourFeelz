# EatyourFeelz
SUMMARY: 
This app uses the Face++ API to glean emotions from a photo of the user's face, converts those emotions into keywords relating to foods, and runs a search through the Edamam API to recommend recipes for the User.

USER EXPERIENCE: 
Though the process should be completely intuitive, this file documents the steps a user would follow to utilize this app:
1. Give the app access to the computer/phone's camera.
2. Take a selfie with the first button, which will be displayed next to the camera live-stream.
3. If satisfactory, the user will submit the photo with the second. Else: repeat step 2.
4. A loading icon will display as the app runs. When finished, it will return the top two emotions displayed.
5. Select additional filters for recipes (if any) via checkbox.
6. Select a specific protein desired (if any).
7. Click the third button to render recommended recipes.
8. If the selections are unsatisfactory, the user can reclick the third button to find new keywords based on the same emotions. 

FUTURE PLANS:
Though the app is fully mobile responsive and functional, there are additional functionalitiess that could be incorporated.
1. Full Mobile Integration - during testing, we found that touchscreens could not reliably trigger the buttons. Smoothing this out for mobile use would be a priority.
2. "Quick View" - rather than requiring users to open a new tab to see every recipe (especially on smaller screens), a functionality that offers an in-page, blown-up preview of the recipe would simplify navigation.
3. Restaurant Mapping - while focusing on recipes now, this app would naturally expand into an app that also searches for restaurants in the area that serve dishes similar to the recipes recommended. Unfortunately, Google has started charging for use of their map API, so this fell out of the scope of an educational project.
