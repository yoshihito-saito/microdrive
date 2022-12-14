# Microdrive for multi-site tetrode recording
<img src="https://user-images.githubusercontent.com/61833067/185296408-5ef86b72-5ae4-4b2e-bd06-3c34904c7fc1.png" width="400px">

## Description
* Microdrive for 16 tetrodes.
* This microdrive consists of the following parts.
  * Drive body
  * Shuttle
  * Guide
* You can record from any region by re-design the guide part.
  * [Guide part design tutorial](https://gist.github.com/yoshihito-saito/2603be5581b5dd010331ef912d4f67f2)
 ## Parts list
  * Drive body: 3D print
  * Shuttle: 3D print
  * Guide: 3D print
  * Drive holder: 3D print
  * Drive screws: OpenEphys
  * Shuttle tube: FLXBLE FUSED TUBING TSP100170 PRC PER MR (Mouser Electronics)
  * Guide tube: PIT-FS 0.20 x 0.02 (Furukawa) 
  * 64ch EIB (Open Ephys)
  * Gold pin small (Neuralynx)
  * Gold pin large (Neuralynx)

## 3D printer
* FLASHFORGE Foto8.9s: XY axis resolution, 0.05 mm


## Microdrive construction

#### 1. Guide part construction.
    1. Bundle the guide tubes into holes of the guide part.
    2. Align the height of guide tubes.
    3. Cut the guide tubes about 5 mm from the drive bottom.
    4. Fix the guide tubes by glue.
    
#### 2. Drive body construction.
    1. Put a shuttle on a lane of the drive body and fix the shuttle to a drive screw (x16).
    2. Check the shuttle motion by rotating the screw.
    3. Fix the drive screws into the pocket on the top of the drive body with a light curing resin.
<img src="https://user-images.githubusercontent.com/61833067/185843937-cce0b9fc-2d86-4e85-bba8-733312cfec45.png" width="200px">

#### 3. Shuttle tube insertion
    1. Fix the guide part to the drive body by glue.
    2. Cut shuttle tubes into 3 cm long.
    3. Apply silicon oil on the surface of shuttle tubes as lubricant.
    4. Insert shuttle tubes into the guide tubes and hook into the shuttles.
    5. Adjust the position of shuttle tube so that the depth is about 1 mm from the top of the guide tube.
    6. Fix the shuttle tube to the shuttle by glue.
    7. Cut the top end of the shuttle tubes.
    
#### 4. Electrode loading.
    1. Fix the microdrive to the drive holder.
    2. Load a tetrode into a shuttle tube (x16).
    3. Connect the tetrode to the EIB with small gold pin.
    4. Fix the tetrode to the shuttle tube by glue.
    5. Cut the end of the tetrodes and align the height of it to the bottom end of the guide tube array.
    6. Rotate the EIB.
    7. Connect the reference electrode to the reference channel and GND channel of the EIB with large gold pin or soldering.
    8. Lower the EIB to the top of the microdrive.
    7. Fix the EIB to the microdrive by glue.  
    8. Paint the drive body with a conductive paint and electrically connect with the GND.
<img src="https://user-images.githubusercontent.com/61833067/185844940-9ae3e892-f666-406f-a6b4-06b7c612030d.png" width="600px">

<img src="https://user-images.githubusercontent.com/61833067/185843646-140accab-082b-4a91-8b5f-6bda9c5e081a.png" width="600px">
 


