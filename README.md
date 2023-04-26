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

## reference electrode making
    1. Cut a coated lead wire into 2 cm lengths (x2).
    2. Strip the wire coating from both ends (~2 mm).
    3. Melt solder and apply to both ends.
    4. Hold a M0.8x2 screw in a vice.
    5. Apply a small amount of flux to the screw.
    6. Solder one end of the screw.
    7. Solder another end to a connector (Preci-Dip, 851-83-050-10-001101) (Reference electrode).
    8. Solder one end of the remaining wire to the pin connector (Reference wire).

## Microdrive construction

#### 1. Guide part construction.
    1. Cut guide tubes into 2 cm long.
    2. Bundle the guide tubes into holes of the guide part.
    3. Cut both sides of the guide tubes to adjust the height.
    4. Move down the guide tubes so they don't pop out into the drive inside.
    5. Cut the guide tubes about 5 mm from the drive bottom.
    6. Fix the guide tubes to the guide part by adhesive.
    7. Cut the guide tubes to match the height to the brain surface of your coordination.
    8. Apply a small amount of adhesive to bind the guide tubes.
    
#### 2. Drive body construction.
    1. Put a shuttle on a lane of the drive body and fix the shuttle to a drive screw (x16).
    2. Check the shuttle motion by rotating the screw.
    3. Fix the drive screws into the pocket on the top of the drive body with a light curing resin.
<img src="https://user-images.githubusercontent.com/61833067/185843937-cce0b9fc-2d86-4e85-bba8-733312cfec45.png" width="200px">

#### 3. Shuttle tube insertion
    1. Fix the guide part to the drive body by adhesive.
    2. Cut shuttle tubes into 3 cm long.
    3. Apply silicon oil on the surface of shuttle tubes as lubricant.
    4. Insert shuttle tubes into the guide tubes and hook into the shuttles.
    5. Adjust the position of shuttle tube so that the depth is about 1 mm from the top of the guide tube.
    6. Fix the shuttle tube to the shuttle by adhesive.
    7. Cut the top end of the shuttle tubes.
    
#### 4. Electrode loading.
    1. Fix the microdrive to the drive holder.
    2. Load a tetrode into a shuttle tube (x16).
    3. Connect the tetrode to the EIB with small gold pin.
    4. Fix the tetrode to the shuttle tube by adhesive.
    5. Cut the end of the tetrodes and align the height of it to the bottom end of the guide tube array.
    6. Rotate the EIB.
    7. Connect the reference wire to the reference channel and GND channel of the EIB with large gold pin or soldering.
    8. Lower the EIB to the top of the microdrive.
    7. Fix the EIB to the microdrive by adhesive.  
    8. Paint the drive body with a conductive paint and electrically connect with the GND.
<img src="https://user-images.githubusercontent.com/61833067/185844940-9ae3e892-f666-406f-a6b4-06b7c612030d.png" width="600px">

<img src="https://user-images.githubusercontent.com/61833067/185843646-140accab-082b-4a91-8b5f-6bda9c5e081a.png" width="600px">

#### 5. DiI coating and Mineral oil filling
    1. Lower all tetrodes and apply DiI solution (1 mg/mL in 100% EtOH) to the tetrode ends.
    2. Withdraw all tetrodes to the lower end of the guide arrays.
    3. Dip the guide arrays into mineral oil (Sigma) and fill the inside of the guide arrays.
     * Caution: This procedure prevents blood from flowing back into the guide arrays. If this is not done well, the tetrodes will get stuck.

## Surgical procedure
#### Materials
- Mouse
- Microdrive
- Ref electrode
- Silicone oil (Sigma, 378429)
- Dental Cement

#### Procedure (Protrocols must be approved by your institution.)
     1. Mark the bregma and lambda.
     2. Level the height of the skull.
     3. Mark on your coordinates.
     4. Mark on cerebellum for the reference electrode. → Drill the hole by 1/2 drill.
      * Caution. You should check the location of the blood vessels before marking. Applying saline will help you see the location.
     5. Perform craniotomy and duratomy.
      * Caution. To stop bleeding and keep the brain surface moist, use collagen sponges and saline or ACSF.
     6. Measure the difference of the height of the brain surface of each target region.
     7. Move all tetrode positions to match the height of each brain surface.
     8. Place reference electode screw on cerebellum.
     9. Lower the microdrive and attach the tetrode ends to the brain surface and fill the cranial window around the guide arrays with silicone oil.
     10. Fix the microdrive with dental cement.
     21. Recover
     22. Lower one tetrodes per region into the brain each hour (~300 μm).
      * Caution. Do not lower all the tetrodes at the same time as this will increase the surface area, spread the pressure and make it more difficult to penetrate the brain surface.
