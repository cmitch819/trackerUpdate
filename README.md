# trackerUpdate
Modified version of Tracker (github.com/OpenSourcePhysics/tracker) for work at Theia Markerless

## Modified Files
-PointMass.java and PointShapeFootprint.java: added Cross footprint (combination of horizontal line and vertical line footprints)
-TToolbar.java: added deleteStepButton (deletes all points on current frame; leaves other frames intact) and deleteTapeButton (deletes modified tape measure/line profile item
-LineProfile.java and LineProfileStep.java: changed line profile functionality into tape measure (added angle display box, ability to rotate)
-TMenuBar.java: replaced tape measure button with line profile button because this version of a tape measure is more useful for Theia's specific purpose
-TrackerPanel.java, TMouseHandler.java, and TrackControl.java: added new keyboard shortcuts, associated the first 9 tracks created with keys a-l across the middle keyboard row. Holding shift still works to move the point, but now instead of clicking on the point first and then long pressing the shift key, you can now simply long press the letter key associated with the point you want to move and it will be automatically selected.
