# Pre-Cog Task
References - Task

Dataset Creation 

Learning how to make images of specific size and single colour background in python - used Pillow Library for the same
- https://www.tutorialspoint.com/python_pillow/python_pillow_creating_images_with_colors.htm

Learning how to add text to images - used Pillow Library for the same
- https://cloudinary.com/guides/image-effects/a-guide-to-adding-text-to-images-with-python

Learning how to add noise to image - use skimage.util -> random_noise did not work, used wand did not work
- https://campus.datacamp.com/courses/image-processing-in-python/image-restoration-noise-segmentation-and-contours?ex=4#:~:text=We%20can%20add%20noise%20to,image%20by%20using%20this%20function
- https://www.geeksforgeeks.org/python-noise-function-in-wand
- Noise is basically meaningless data added to the image. Here the meaningless data means random pixels coloured with random colors that make it harder to identify, so I used random for that that colours the image randomly

Training a neural classifier

- https://www.geeksforgeeks.org/building-a-convolutional-neural-network-using-pytorch/
