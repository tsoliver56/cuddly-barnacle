# cuddly-barnacle
Medical file image reading application with tools to increase perceptual understanding of MRI and CT scan data.

# Medical Image File Formats
## Analyze
Fixed-length: 348 byte binary format .img and .hdr Unsigned integer (8-bit), signed integer (16-, 32-bit), float (32-, 64-bit), complex (64-bit)
## Nifti
Fixed-length: 352 byte binary formata (348 byte in the case of data stored as .img and .hdr) .nii Signed and unsigned integer (from 8- to 64-bit), float (from 32- to 128-bit), complex (from 64- to 256-bit)
## Minc
Extensible binary format .mnc Signed and unsigned integer (from 8- to 32-bit), float (32-, 64-bit), complex (32-, 64-bit)
## Dicom
Variable length binary format .dcm Signed and unsigned integer, (8-, 16-bit; 32-bit only allowed for radiotherapy dose), float not supported
