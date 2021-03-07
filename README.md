# cake-promo

## Characater Creation

- Create Model in Text Tools
- Export to TexTools Folder
- Copy Entire Folder into Models
- Create new Blender File in Models file (Save as [Name]Mesh.blend)
- Remove all Bones / lights /cameras
- Select all objects
- Rotate -90 on x axis To Stand Straight up
- Change Rendering to Cycles
- Delete any Facial Markings you don't want
- If you need to change color create new PNG and hook up now
- Export to FBX (only choose mesh)  [Name]Mesh.fbx
- Login to mixamo
- Upload Characater
- Place joints
- Download and for pose choose "Origianl Pose(.fbx)"
- Downlond to [Name]Mixamo.fbx
- Choose some more dance moves
-- Downlaod as [Name][DanceMove].fbx (no mesh)
- Open New Blender file
- Rename Scene [Pose]
- Add Collection [Name]Pose
- Import [Name]Mixamo.fbx to [Name]Pose collection
- save to [Name]Mixamo.blend
- commit
- Click on Armature and to go Pose mode
- Move armature to see if any weights need to be adjusted
- for legs, if mesh weighted to opposite leg then click on object in object mode and duplicate (shift D)
-- append ".r" and ".l" to objects  names
-- go into edit mode delete all verticies on oppposite side
-- click on vertex groups and delete all vertex groups for opposite side
-- go to object mode and click on armature
-- go to pose mode and move leg
-- if vertex "left Behind"

--- click object mode - click armature then ctrl-click mesh with vertex issues
--- changed to weight-paint mode
--- ctrl-click the bone you want to weight the vetex to
--- repeat

- Rename scene "pose"

- Foreach Animation
-- go back to mixamo and choose animation you want to download
-- download as [Name][Dance].fbx (animation only - no mesh)
-- creeate new empty scene
-- rename to match animation
-- create new collection [Name][Dance]
-- import animation .fbx file
-- go back to pose scene and select armature add all mesh objects
-- hit ctrl-l and link to your newly created scene
-- Go back to dance scene and move all linked objects into the [Name][Dance] collection
-- Hide the [Name][Dance] collection
-- Go to dance armature and change to object mode and select all "a"
-- open Animation editor go to key frames and select all and copy

-- go to animation tab
-- go to pose mode
-- switch to characater animation scene
-- select armature and go to pose mode
-- "a" to select all
-- goto frame 1
-- "i" to insert keyframe at 0 (choose location, rotation, scale)
- 




