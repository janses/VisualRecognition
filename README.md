# VisualRecognition
Uses visual recognition to determine the species/subspecies of an animal

Let’s begin our journey by preparing our data.
1. First download the following images to your local drive.
beagle.zip 50 images of dogs. Breed type: Beagle
husky.zip 50 images of dogs. Breed type: Husky
golden-retriever.zip 50 images of dogs. Breed type: Golden Retriever
cats.zip 50 images of large and small cats: from lions to house cats.
2. Extract the images on your local drive.
3. Login into IBM Cloud: https://cloud.ibm.com/registration
4. Click the Catalog tab.
5. Search for the Visual Recognition service and click that tile.
6. Click Create.
7. Click the Watson Studio button.

Working with pre-built classifiers
1. From the General tile, click the Test.
2. Browse and upload the extracted images from the Beagle.zip file from your local drive (not just the zip
file itself….extract them first).
3. Select various classifiers (check box) and observe the retrieved images.
4. Now go to Google images and search for images of your choosing.
5. Click on one of those images.
6. Click that image, then drag it to your desktop. It has to be .jpg or .png, no gif files please.
7. Back to the test tab and clear search results and drag and drop the image onto the test section.

Working with Custom Classifiers
1. Click the IBM Watson Studio link in the top left corner. The Watson Studio Project page
appears.
2. Scroll down and click the Launch tool of your Visual Recognition service.
3. From the Classify images tile, click Create model.
4. In the ensuing project page, specify a name.
5. Click Browse and select the zip file for Golden-Retriever and Husky (two zip files).
6. Click Train Model in the top left.
7. In the message bar, click the here link to test your model.
8. Click Test in the ensuing page.
9. Go to Google Images and search for husky dog.
10. You may need to first click on the image, then drag and drop it onto your desktop.
11. Browse and import the newly downloaded image. View the results.
12. Click Clear results.
13. Back to Google images and download the picture of a cat or a car.
14. Browse and import the image of the cat. Not good! It has a high confidence that it is a dog. Time to use
negative classes. Naturally, it has to fit it into the only two classifications that you have, but a super low
confidence would be what we are trying to achieve.
15. Click the link back to your Visual Recognition instance.
16. In the Classify Images tile, click Create model.
17. Upload the Cats zip file.
18. Select the already uploaded golden-retriever and husky zip files and add them to your models.
19. Open the Cats images and notice some of those “cats” are not exactly home pet animals—cat they
maybe.
20. Select the lions and the tigers and reclassify them as negatives.
21. Click View All Classes.
22. Click Train Model.
23. Once the training is complete, click the here link and start by uploading the original cat image that you
used earlier. Much higher confidence indeed and the other classes? Zero confidence!
24. Have fun with other cat, dog, lion, tiger images.
