# Oxford IIIT Pet Dataset (fixed)

## Dataset description

The Oxford-IIIT Pet Dataset is a 37 category pet dataset with roughly 200 images for each class created by the Visual Geometry Group at Oxford. The images have a large variations in scale, pose and lighting. All images have an associated ground truth annotation of breed, head ROI, and pixel level trimap segmentation. [[kaggle.com](https://www.robots.ox.ac.uk/~vgg/data/pets/)]


Original dataset was downloaded from [https://www.robots.ox.ac.uk/~vgg/data/pets/](https://www.robots.ox.ac.uk/~vgg/data/pets/).

## Fixed images

The original dataset contains a few damaged images. We fixed them and uploaded into this repository. These images are mentioned below, as well as the steps of fixing them.

1. **Abyssinian\_34.jpg**

		File header: GIF image data, version 89a, 250 x 202
	
	File was converted to jpeg image format.
	
2. **Egyptian\_Mau\_139.jpg**
	
		File header: GIF image data, version 89a, 350 x 250
	
	File was converted to jpeg image format.
	
3. **Egyptian\_Mau\_145.jpg**

		File header: GIF image data, version 89a, 216 x 188
		
	File was converted to jpeg image format.
	
4. **Egyptian\_Mau\_167.jpg**

		File header: GIF image data, version 89a, 183 x 27
	
	File was converted to jpeg image format.
	
5. **Egyptian\_Mau\_177.jpg**

		File header: GIF image data, version 87a, 300 x 214
		
	File was converted to jpeg image format.
	
6. **beagle_116.jpg**

		Corrupt JPEG data: premature end of data segment
		
	File was loaded using OpenCV and saved again as jpeg image. It is not possible to fix damaged regions easily.
	
7. **chihuahua_121.jpg**

		Corrupt JPEG data: 240 extraneous bytes before marker 0xd9
		
	File was loaded using OpenCV and saved again as jpeg image. It is an easy way how to clean file from purposeless bytes.

		
	
	

