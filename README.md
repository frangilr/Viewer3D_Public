# Viewer3D_Public

## Usage notes
- To use the App after downloading it, right-click on the app's icon, and then press "Open." Clicking only once on the icon will most likely fail to open the app on the first trial due to it being an app downloaded from the internet. By doing  right-click > Open, Apple treats it as a different instruction. Afterwards it should work by just clicking the icon once as any other app.
- When using the App for the first time, please read "About" file, which is accessible by clicking on the "Help" button on the App, and it contains all the relevant information about the App.
## Version 2.04 (07/10/2024)
- Improved file-saving code
## Version 2.03 (06/20/2024)
- Mouse rotations now parallel to mouse movements
- App is good to go
## Version 2.02 (06/18/2024)
- Inverted rotation matrix to Euler angles
- Cleaned code and updated About file
## Version 2.01 (06/18/2024)
- Inverted rotation matrices
## Version 2.00 (06/18/2024)
- Rewrote the way 3D rotations were handled entirely
- Implemented mouse rotations along all 3 dimensions using the rolling-ball algorithm
- Added camera controls
- Rotation angles now wrap around the [0,360) range
- Displaying axes for debugging purposes
## Version 1.01 (06/09/2024)
- Save button can now write to both new and exisiting files.
## Version 1.00 (03/01/2024)
- Output file is only saved if it is a brand new file. The App will not overwrite existing files. That needs to be added for future versions of the App. Please keep this in mind while annotating.
- Sliders are constantly performing computations. Need to add some delay that the human eye can't perceive to avoid roundoff errors building up.

## License
- This App was built for research/academic purposes and not commercial use. The authors are not liable for any issues that may arise from using the software, and there are no warranties associated with the software. If you would like to use the software, contact the authors.
