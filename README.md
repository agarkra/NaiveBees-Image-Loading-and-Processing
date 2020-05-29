# NaiveBees-Image-Loading-and-Processing

This notebook walks through loading and processing images. After loading and processing these images, they will be ready for building models that can automatically detect honeybees and bumblebees.

1. **Import Python Libraries** 
- numpy
- pandas
- image from piL
- matplotlib

2. **Using PIL for opening the images**
Pillow is a very flexible image loading and manipulation library. It works with many different image formats, for example, .png, .jpg, .gif and more. For most image data, one can work with images using the Pillow library (which is imported as PIL).

3. **Image manipulation using PIL**
Pillow has a number of common image manipulation tasks built into the library. For example, one may want to resize an image so that the file size is smaller. Or, perhaps, convert an image to black-and-white instead of color. Operations that Pillow provides include:

- resizing
- cropping
- rotating
- flipping
- converting to greyscale (or other color modes)

4. **Converting image as array of elements**
Converting the images into array of elements based on the three color type which is thare in the image(RGB).

5. **Explore the color channel**
Color channels can help provide more information about an image. A picture of the ocean will be more blue, whereas a picture of a field will be more green. This kind of information can be useful when building models or examining the differences between images.

6. **Now classifying different bee types**
Now we'll look at two different images and some of the differences between them. The first image is of a honey bee, and the second image is of a bumble bee.

7. **Generarting a Pipeline to build the model**
Now it's time to create an image processing pipeline. We have all the tools in our toolbox to load images, transform them, and save the results.
In this pipeline we will do the following:
- Load the image with Image.open and create paths to save our images to
- Convert the image to grayscale
- Save the grayscale image
- Rotate, crop, and zoom in on the image and save the new image
