# AI: All Idiots

The project AI: All Idiots is a hybrid curatorial/artistic project dealing with the images Czech artists use for selfpresentation on their personal websites. The main goal of this project is to collect almost all images presented in such a way and use them as a source for training several machine learning (ML) models. These models will be subsequently used to present ML algorithms in the context of fine art exhibitions.

## Philosophy

The main purpose of this project is to confront the artistic and the artificial intelligence, or better to enlighten their possible relation. The former is a human creative agent with the understandable ambition to be visible, the latter is a machine based intelligent agent with the understandable ambition to stay invisible. The former fulfils (among others) the role of being a source for improvement of the abilities of the letter. The former is extracted, the latter is extracting. Each of them has different goals and interests but they both meet in the same digital environment.

The provocative word "Idiot" here plays a role in the basic *vulgar* diagnosis of the possible relationship between above mentioned agencies. As the clinically obsolete diagnosis [Idiot Savant](https://www.dictionary.com/browse/idiot-savant) fits very well to describe contemporary ML algorithms capabilities, the vulgar and offensive connotations are taken from the *spoken language* to strongly highlight the hidden extraction mechanisms. As described by McKenzie Wark in her latest book [Capital is Dead: Is this Something Worst?](https://monoskop.org/images/5/5e/Wark_McKenzie_Capital_Is_Dead_Is_This_Something_Worse_2019.pdf), the vulgarity of *spoken language* is probably one of a few artistic strategies that can clearly highlight the *written—–machine performed—–language* of ML algorithms (the Vectors).

## Data Structure

The data are structured into two main categories: artists and groups. Each category includes a set of objects titled according to the name of a specific artist or group of artists respectively. Every object includes three main arrays: webs, keywords, and images.

+ artists
+ + name of the artist
+ + + webs (list of artist's websites)
+ + + keywords (list of fields in which the work of the artist belongs)
+ + + images (list of scrapped links to images located at artist's websites)
+ + + gender (m/f letter to determine artist's gender) – this attribute is subject to discussion and is only implemented by the very poor distinction based on the Czech suffix "-ová" specific for female surnames.
+ groups
+ + name of the group
+ + + webs (list of group's websites)
+ + + keywords (list of fields in which the work of the group belongs)
+ + + images (list of scrapped links to images located at group's websites)

Last version of ai-db.json has 800 records with 681.518 image links.

*Note: The database is in a very raw state. Image links have not been cleaned from duplicities yet.*

## Cotnribution

Feel free to open PR to add a new data. Feel free to fork this repository for your own use case or research.

## Credits

This dataset was created as one of the (special) outcomes of research project [Decentralized Big Data Collection, Analysis, Visualization and Interpretation in Art Practice](https://datatata.info) supported by the Technology Agency of the Czech Republic and the Faculty of Fine Arts, Brno Aniversity of Technology.

Collected images and data will be used for deep analysis and training ML algorithms for the purpose of the exhibition AI: All Idiots in the gallery [MeetFactory](http://www.meetfactory.cz/en/) Prague in Autumn 2021.