
![alt text](https://github.com/kamranmajid41/DeCArate/blob/main/Screen%20Shot%202021-10-31%20at%205.17.50%20AM.png)

Professional holiday decoration in the palm of your hand.

## Inspiration

Finding the right halloween decorations for your home can be a hassle, one that we have experienced firsthand. To simplify this process and provide users with a streamlined, professional decoration platform (without the hefty price tag) we created DecARate!

## What it does

Uses a Deep Convolutional Neural Network (DCNN) to find out which housing style best matches your house, and recommends decoration layouts that fit your house, and your budget. 

Gives you an AR view of the decorations on your house in real-time - giving you control over the placement, density, and overall theme of your decoration layout. 

Employs a set of checks that determine various safety hazards that the lighting may pose to ensure that you stay safe. 

Lets you know where you can find the specified decorations and allows you to export a shopping list of decoration items. 

## How we built it

We used Google Colab as well as various toolkits, frameworks, and libraries including tensorflow, fastai, scikit-learn, numpy, and matplotlib for our DCNN. Our data was derived both from a Kaggle dataset, and also from a web scraper that used Google Images to increase the reliability of our algorithm. Our UI was designed using Figma. 

## Challenges we ran into

Our product was very multifaceted so we struggled initially to select just a few areas to focus on. 

## Accomplishments that we're proud of

After trying ResNet34, we weren’t happy with our accuracy, so we switched to ResNet50 and had a nearly 30% increase in our training accuracy. 

## What we learned

We learned about various architectural styles and deepened our understanding of machine learning architectures. 

## What's next for DecARate

In the future, we would like to flesh out the augmented reality portion of our app.
