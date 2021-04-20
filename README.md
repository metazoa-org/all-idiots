# AI: All Idiots

The project AI: All Idiots is a hybrid curatorial/artistic project dealing with the images presented by czech artists on therir own personal websites. The main goal of this project is to collect almost all images presented in such a way and use them as a source for training several machine learning (ML) models. These models will be than used to present ML algorithms in the context of fine art exhibitions.

## Philosophy

The main purpose of this project is to confront the artistic and the artificial intelligence, or better to enlight its possible relation. The first is a human creative agent whith the understandable ambitions to be visible, the latter is a machine based intelligent agent whith the understandable abitions to stay invisible. The first plays a role (among others) of the source for to improve the abilities of the other. The first is extracted, the latter is the extractor. Each has different goals and interests but they meet in the same digital environment.

The provocative word "Idiot" here plays a role of the basic *vulgar* diagnosis of the possible relationship between above mentioned agencies. As the clinically obsolete diagnosis [Idiot Savant](https://www.dictionary.com/browse/idiot-savant) fits very well to describe contemporary ML algorithms capabilities, the vulgar and offensive connotation are took from the *spoken language* to strongly enlight the hidden extraction mechanisms. As McKenzie Wark desribes in hers last book [Capital is Dead: Is this Something Worst?](https://monoskop.org/images/5/5e/Wark_McKenzie_Capital_Is_Dead_Is_This_Something_Worse_2019.pdf), the vulgarity of *spoken language* is probably one of a few artistic strategies that can clearly enlight the *written—–machine performed—–language* of ML algorithms (the Vectors).

## Data Structure

The data are structured to two main categories (artists and groups). Each category includes a set of objects titled by name of artist or group of artists respectively. Every object includes three main arrays (webs, keywords, images).

+ artists
+ + name of the artist
+ + + webs (list of artist's websites links)
+ + + keywords (list of artist's works fields)
+ + + images (list of scrapped links of images from artist's personal websites)
+ + + gender (m/f letter to determine artist's gender) – this attribute is a subject of discussion and is only implemented by very poor distinction based on czech "ová" specific in a female surrnames.
+ groups
+ + name of the group
+ + + webs (list of group's websites links)
+ + + keywords (list of group's works fields)
+ + + images (list of scrapped links of images from group's websites)

Last version of ai-db.json has 800 records with 681.518 image links.

*Note: The database is in a very raw state. Image links are not cleaned from duplicites yet.*

## Cotnribution

Feel free to open PR to add a new data. Feel free to fork this repository for your own use case or research.

## Credits

This dataset was created as one of the (special) outcomes of research project [Decentralized Big Data Collection, Analysis, Visualization and Interpretation in Art Practice](https://datatata.info) supported by Technology Agency of the Czech Republic and Faculty of Fine Arts, Brno Aniversity of Technology.

Collected images and data will be used for deep analysis and training ML algorithms for the purpose of the exhibition AI: All Idiots in the [MeetFactory](http://www.meetfactory.cz/en/) in 2021.