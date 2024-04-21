# S2_temeserries_app


A reusable script was created for viewing and downloading S2 images in GEE (Figure 1). The script takes as user input an Area of Interest (AOI) and a time period with a start and end date. Then it filters an S2 collection based on these requirements and sorts it based on the 'CLOUDY_PIXEL_PERCENTAGE'. This simply means that the least cloudy images will appear first in the collection. The user can define how many images to visualize at once. This functionality aims to save time because loading a lot of images for big AOI in GEE can be quite slow. So by defining the number of the start and the end image to be loaded, the user can load fast images 0-10, evaluate them, then load images 10-20, etc.

The code allows the user to create a list of chosen images (since each image name has a unique index number added to it) and download them all at once or proceed with analyses in GEE on the chosen images.

![image](https://github.com/nikolovayana/S2_temeserries_app/assets/113608125/65d79f1a-5d89-4dbb-9c93-4ffd3b1d1afc)
