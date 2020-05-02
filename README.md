# fav_car_colour
Using openCV and basics of ML predicting Bangalore's Favorite car Colour.

A image processing project in which multiple images of bangalore's traffic were clicked with each image containing multiple cars. OpenCV was first used to separate the car from the background and then with k- means cluster algorithm to pick out the dominant colour from the cropped image of the car which is infact the colour of the car. Simaliar colours from different images are first mapped to their respective colour using the mapper function and the the reducer program is run to find the total number of cars belonging to a particular colour across all images.

# Requirements

open cv2
python 2.7+
anaconda


