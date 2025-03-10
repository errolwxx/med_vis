## Requirements
- Python == 3.8.13
- vtk == 9.0.3
- PyQt5 == 5.15.2
- Pydicom == 2.3.1
- opencv-python == 4.7.0.72
- NumPy == 1.24.2
- Shapely == 2.0.1

## How to use
cd src, run main.py.
- Measure length
  - Click measure length button and click on the slice. Distance will be calculated when points number reaches 2.
  - Change the target slice by choosing from axial, sagittal, and coronal.
  - Click exit measure button to quit measuring mode.
- Volume rendering
  - Click Open 3D button.
  - Further interactables in popped window.
- ROI measure
  - Click measure ROI button and draw on the slice by pressing and dragging the mouse. Area will be calculated when the mouse is released.
  - Rest are the same as length measuring.
