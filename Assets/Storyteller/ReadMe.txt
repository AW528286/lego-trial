to launch Storyteller go to Tools>DaiMangou>Storyteller

All necessary windowswill launch and auto dock. the undocked window is the Start window . in the start wndow you will find buttons which lead you to tutorials, forums and discussions.
Close the Start window.

Click the Create New button.

You will be presented with a project creation window.


To begin using storyteller. click Create or  select a folder where you want to have your story file created, then in the Storyteller , give your story a name , the default name will be "New Story". you will see three buttons the 1st is for games, 2nd for stories, 3rd for storyboards. click the buton which represents the type of project you wish to create.
Then click create.

you will be presented with a blank window.

to begin creating a story , right click on the canvas and go to Make Node> Character Node.

you can then begin adding more nodes which you will find in the Make Node menu.

There is a system in place which should prevent you from making bad connection.

Create this conversation. between three characters.

Tom: hi how is everyone doing today(dialogue)
Mary: we are doing just fine, thank you(dialogue )
Wils: speak for yourself Mary, i lost my wallet just now (dialogue)
Tom: I will help you to look for it (dialogue)
Tom: where did you last place it?(dialogue)
Mary: begins to sweat (action)
Wils: Mary are you okay?


right click in your project folder go to Create > Game Bridge > Scene Data

give your SceneData file any name you choose.

RIght click on th node cnavas , go to > Windows> Game Bridge.

Select your newly created SceneData and in the Game Bridge window clck the (Push To Scene Data) button.

The cleanup wondow will open and will check if there are any iddues with your nodes.

if all is well you will see no warning messages and the cleanup window will close.

your data is now game ready.


Create a new gameobject in the scene and in the Game Bridge widnow assign a Interaction component to it.

Then assign the SceneData to the defined slot in the Interaction component in the Inspector.

this example will be in linear mode by default.

From this point you can choose to use a UI for your project.

please open the Dating sim example scene and observe the UI assignment.

once your UI is setup , whatever input you use to start your game , should also call the function GenerateActiveDialogueSet() or doRefresh()

you can now play though this very basic example.
