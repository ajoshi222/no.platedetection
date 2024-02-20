![246499711-c5c50f95-01ec-442f-b805-912d946ce6ab](https://github.com/ajoshi222/no.platedetection/assets/69758727/57a9d7b2-abd7-41f7-95dc-78edad797b3c)Morphological transformation

The Top-hat and Black-hat filters are part of Morphological transformations in image processing. The Top-hat filter is utilized to amplify bright objects of interest within a relatively darker background

Resize the image to the required size and then grayscale it.
 ![Screenshot 2024-02-20 234850](https://github.com/ajoshi222/no.platedetection/assets/69758727/2b0fec2a-49b6-405d-a1fd-2f1967a590f6)


edge detection use the canny edge method from OpenCV

![Screenshot 2024-02-20 235104](https://github.com/ajoshi222/no.platedetection/assets/69758727/3da3efcc-6b80-49ba-b274-ec6d50d3126f)


Once we have found the right counter we save it in a variable called screenCnt and then draw a rectangle box around it to make sure we have detected the license plate correctly.

![Screenshot 2024-02-20 235133](https://github.com/ajoshi222/no.platedetection/assets/69758727/8ede0940-8c78-47ec-8405-e21351d82d66)

The masked new image will appear something like below

![Screenshot 2024-02-20 235200](https://github.com/ajoshi222/no.platedetection/assets/69758727/f00874d7-cfc7-4a0f-beba-b4bbcc36f582)
