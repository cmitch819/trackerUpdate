# trackerUpdate
Modified version of Tracker (github.com/OpenSourcePhysics/tracker) for work at Theia Markerless

## Modified Files
- PointMass.java and PointShapeFootprint.java: added Cross footprint (combination of horizontal line and vertical line footprints)
![Screenshot (392)](https://user-images.githubusercontent.com/22796402/185718829-fe99a549-35c7-491a-b8ab-dd3d920e408b.png)
- TToolbar.java: added deleteStepButton (deletes all points on current frame; leaves other frames intact) and deleteTapeButton (deletes modified tape measure/line profile item
![Screenshot (396)](https://user-images.githubusercontent.com/22796402/185718932-53c3f056-9d8c-4dc8-adbd-ce490baba91c.png)
- LineProfile.java and LineProfileStep.java: changed line profile functionality into tape measure (added angle display box, ability to rotate)
![Screenshot (395)](https://user-images.githubusercontent.com/22796402/185718967-772c633e-c57a-4e37-a9d1-340238b36363.png)
- TMenuBar.java: replaced tape measure button with line profile button because this version of a tape measure is more useful for Theia's specific purpose
![Screenshot (394)](https://user-images.githubusercontent.com/22796402/185718974-607b9577-2211-46a9-9b1e-401de152b259.png)
- TrackerPanel.java, TMouseHandler.java, and TrackControl.java: added new keyboard shortcuts, associated the first 9 tracks created with keys a-l across the middle keyboard row. Holding shift still works to move the point, but now instead of clicking on the point first and then long pressing the shift key, you can now simply long press the letter key associated with the point you want to move and it will be automatically selected.
