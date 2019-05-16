# TopologyMapExe

## Description
This tool is used to visualize the relationship between motion bodies, joints and connectors from a .mdef file as a diagram.

## Features
### Opening .mdef files
File->Open->choose any .mdef file.
### Changing the view
#### Presenting data from an ortographic perspective 
View->Perspective-> Top, Side or Front

Each perspective uses the actual x,y,z coordinates, eliminating a dimension depending of the point of view.

In this view the shape of the motion bodies is calculated from the connection points and the center of gravity.

#### Circle view
Used for testing a concept, might be removed in the final version

#### Force-directed
Displays the elements as graph

Implemented using the force-directed graph drawing algorithm.

#### Removing the names of elements.
View->Display names

Used for making the whole scene less cluttered with text.

### Help
Tab for helping the user understand the system better.

#### Legend
Help->Legend
Opens a panel displaying each type of joint or connector depending on the symbol.

#### Search
Help->Search
Used for finding motion bodies, joints or connectors from a given name or using regex.
The highlight color can be changed.

#### Info panel
Help->Info
Used for displaying important data related to elements
Still work in progress.

### Interacting with the scene
The user can zoom in or zoom out using ctrl+scroll wheel.

Motion bodies can be moved aroung using the left mouse button.

The color of the elements can be changed using right click, which opens a menu.

### Saving the scene

The user can save the state of the scene in a .xml file which can be used in the future for the same model.

File->Save : Saves the scene using the name of the model.

File->Save as : Saves the scene with a different name.

File->Load : Loads a saved scene.



