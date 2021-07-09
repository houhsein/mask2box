# mask2box

Transfer the Bounding Shape.mitkgeometry file croped by MITK to coordinate and create a new mask nifti file to be a label data, which can augmentation in dataloader.

Coordinate format is (x1, y1, x2, y2, z1, z2)

The output nifti have the same dicom header as original data.
