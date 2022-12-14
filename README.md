## art

![output](https://user-images.githubusercontent.com/32826270/210912088-f77e66f3-2955-47f3-a572-1eac57c8d8a3.png)

NFT artwork generation. 

This code is generating NFT art by combining different images and then saving them in the 'Output' directory. The images are combined using the Pillow library's paste function and resized using the resize function. The resulting image is saved in the 'Output' directory with the file name being a concatenation of the attribute values.

The code creates a class called NFT which takes in six attributes, attr0 through attr5, in its initialization. The NFT class has a __str__ method which returns the string representation of the object, which is the concatenation of the six attributes. The NFT object also calls the generate function, which generates and saves the NFT art by combining and resizing the images and saving them to the 'Output' directory.

![cool](https://user-images.githubusercontent.com/32826270/210976583-fd2d1ad2-18eb-4243-b8e3-bc7220f0bf35.png)

# Generate
Generates a new NFT object and saves it to the Output directory

# Delete
Deletes an NFT object from the Output directory

# Previous
Displays the previous NFT image in the Output directory

# Next
Displays the next NFT image in the Output directory

# View
Views an NFT object from the Output directory
