# Vegan vs. Not Vegan Classifier


## Goal
To practice what I have learned during week 1 of Fast AI v3.

French medium article for the github can be find here.

## Scraping data from Instagram

I choose Instagram to scrape data because it contains a vast amount of pictures that are relatively similar and aspire to the same aesthetics standard.
Close-up of dishes are easy to found and are usually sorted by category, for example: Vegan and Not Vegan.
I decided to train a classifier to see if it would be able to tell the difference.

### Vegan Accounts
- [https://www.instagram.com/buddha_bowls](@buddha_bowls)
- [https://www.instagram.com/vegan_bowls](@vegan_bowls)
- [https://www.instagram.com/vegansrecipe](@vegansrecipe)
- [https://www.instagram.com/thevegansclub](@thevegansclub)
- [https://www.instagram.com/thevegansclublifestyle](@thevegansclublifestyle)
- [https://www.instagram.com/thefeedfeed.vegan](@thefeedfeed.vegan)

### Not Vegan Accounts
- [https://www.instagram.com/burgersofthedays](@burgersofthedays)
- [https://www.instagram.com/sushiporn](@sushiporn)
- [https://www.instagram.com/foodgawker](@foodgawker)
- [https://www.instagram.com/ks_ate_here](@ks_ate_here)
- [https://www.instagram.com/thefeedfeed](@thefeedfeed)
- [https://www.instagram.com/huttoneats](@huttoneats)


### Scraper
Thanks to @racerga for creating this tool.
https://github.com/rarcega/instagram-scraper

## A not so easy challenge
### Between the two dishes below, one is vegan the other is not. Can you tell which is which?*
![Two dishes, one vegan the other not, very hard to tell which is which.](https://github.com/remiconnesson/instaclassifier/blob/master/illustration1.png)
*\*the anwser at the bottom of the page*

## Starting small
The first notebook is called Sample Dataset, the neural network is trained on a dataset of about 300 images.
The results were actually concluding and I wanted to see what happends if I added...

## More Data
The second notebook is called Bigget Dataset, the neural network is trained on a dataset of about 21000 images.

## Conclusion & Area of Improvement
This is a toy project so I didn't dive too much into the data to check if everything is fine. 
Some things that are worth keeping in mind:
- Not-vegan accounts can feature vegan dishes as it is not mutually exclusive.
- Though vegan accounts won't feature not-vegan dishes.
- Both types of accounts feature images not related to food, e.g: Advertisements, People, Logo, Drinks etc...
- I haven't thought of this before but a more fine-grained probleme would have been "Healthy but Not Vegan Dishes" vs "Vegan Dishes".

## Reproducibility
Everything you need to run the notebooks are inside the notebook. 
Start by the one called "Sample Dataset" as it includes extra step for setting things up.

Only prerequisite is to install conda env with Fastai librarie v1.

*\* Answer : the one on the left is Thai Cicken Curry Soup (not vegan) and the one on the right is a Vegan Tofu Burrito.
Credit to @thefeedfeed and @thefeedfeed.vegan*

Disclaimer: All images belongs to their respectful owner.

