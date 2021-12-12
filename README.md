# image-classifier-from-28*28p-gray-scale-images
As a practice project, we are going to create an image classifier. We will be classifying this kind of images into ten different categories,  such as T-shirts, trousers, pullover dresses, bags, boots, etc.

For this, we are going to use a very famous database that is known as Fashion mnist Database.
Here we have around 70000 gray scale images of ten different fashion categories, objects.

A training site will be of 60000 images which we are going to use to train our model.
We have another set of 10000 images which we will be using as a test set to evaluate the 
performance of our model.

These images are in the form of 28*28 pixel is square and each pixel is represented
on a gray scale in a scale of 0 to 255.

The great thing about this database is that it is available within us and we can directly
imported from keras.We don't have to upload a separate file to access this database here.
You can see the ten different objects that are present in this database.
