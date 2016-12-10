How To Install:

Extract the .zip file and copy ice_tools.py to your addons folder - typically this is found in
...\Scripts\addons of Blenders' main folder.

Go to user preferences/addons and just search for ice tools in the retopology section. You can
find the addon located in the T-panel in the 3d viewport.

How To Use:

ADD RETOPO MESH

Select your target mesh which will be used as a surface guide for retopology and
press the button. This will create an empty mesh which will proceed to edit mode and activate
surface snapping (face) by default and set the created mesh's origin based on the target mesh's
own point of origin.

The mirror and solidify toggles are on by default so once you create a retopo mesh those
modifiers will be added. Turning them off will subsequently remove them upon creation.

It will also modify additional options for the Grease Pencil
(Gpencil is undergoing development and there may come a time again where you will be faced with a
bug, if that happens message us at our Facebook page: https://facebook.com/blendespore)

SURFACE SNAP ICON

Turning this turn off will disable surface snapping from activating when you create
a retopo mesh. It will not however de-activate current snapping modes if it is not set to face
(e.g. Snapping is set to vertex or increments). This avoids issues with user workflow.

UPDATE MODIFIERS

This will only add or remove the mirror or solidify modifiers depending on their toggle states in
the T-panel menu. It will not however work if the selected mesh is not the current retopo mesh.
In order to re-assign a retopo mesh or link two objects again: select your target mesh then your
retopo mesh and press update modifiers, this will re-link them and add with default paramaters on
or remove the mirror and solidify modifiers.

MIRROR AND SOLIDIFY MODIFIER TOGGLES AND PARAMETERS

You can change the states of the modifiers here. The mirror will have X-symmetry on by default
but the T-panel menu will allow you to activate/deactivate the Y and Z axis. This is also true
for the thickness and offset of the solidify modifiers. Changes for the modifier parameters will
be live.

For adding or removing the mirror and solidify modifiers check or uncheck their toggle states and
press Update Modifiers button

APPLY SHRINKWRAP

This will add and apply a shrinkwrap modifier to your retopo mesh using your target mesh as the
shrinkwrap target. It can also be used to re-link the retopo mesh to the target mesh back
together.

Additional options are in the undo menu (F6) like Automatic Clipping which will
clip/merge the vertices in the middle if the the mirror modifier is present, Clip Selected which
will clip selected vertices (mainly used for vertices in the middle edge loop which are not
influenced by Automatic Clipping) and an option to change the shrinkwrap modifiers' wrapping mode.

FREEZE, THAW AND SHOW

This are used primarily to accentuate the Apply Shrinkwrap function. The Freeze function will
group the selected vertices and will immunize them from the shrinkwrap modifier effects. The Thaw
option will reverse the effects of the Freeze function and Show will select all the vertices you
have frozen so you can manage them easier.

DRAW WIRE, X-RAY AND HIDDEN WIRE

These are basic object functions found in Blender and is included in the addon menu to expose
them and make them easily accessible. Draw Wire will render the wireframe of your model in the 3d
Viewport, X-Ray will let you see them behind any objects and Hidden Wire is for hiding the faces
in edit mode so you can only see the verts or edges - this allows for greater ease and control in
cases of retopology.

Basic demo for hard surface modelling: https://youtu.be/vjnb0YEgg5I

Visit our blog for more tutorials: https://blenderspore.blogspot.com

Join our Facebook page (You can also message us here): https://facebook.com/blenderspore
