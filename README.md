# Chipotle clustering challenge

<img src="app/plots/chipotle.png" alt="left" width="450"/>

### The Dream Team
- [Christian Melot](https://github.com/Ezamey), junior AI developer
- [Jérôme Coumont](https://github.com/jcoumont), junior AI developer
- [Ebubekir Kocadag](https://github.com/EbubekirKocadag), junior AI developer

## The Mission
<img src="https://media.istockphoto.com/photos/romantic-couple-eating-street-tacos-at-outdoor-mexican-restaurant-picture-id932534338?k=6&m=932534338&s=612x612&w=0&h=9RXIf7fsAEGVynwKKv0oAq5Rg8Wrg1END87XEzA0_zg=" align="left" width="450"/>

>
>"Honey, where do you wanna eat?"
>
>"Do you even have to ask? Chipotle, of course!"
>
>"How could I forget, we've been eating Chipotle for the last 47 days..."
>
>"So get ready for number 48! Oh I can't wait to stuff my face with a burrito!"
>
>"But the closest one is an hour drive away, couldn't we just get McDonalds?"
>
>"How dare you utter that word in my presence? First the neighbors, now you!"
>
>"The neighbors? What do they have to d-"
>
>"That's it, we're moving, I can't deal with this anti-Chipotle fascism."

Find Chipotle **epicentres** to live your ideal Chipotle lifestyle by clustering the [Chipotle dataset](chipotle_locations.csv).
### Must-have features

- [X] A visualization of the USA with Chipotle locations
- [X] Visualization of the different clusters
- [X] Intrinsic analysis comparison of the clusters of at least 2 methods with varying arguments (using Euclidean distance as criteria)
- [X] A chosen centroid to live. Make your argument of why the chosen centroid is superior to others. Examples of arguments are:
    - [X] highest density
    - [X] greatest uninterrupted link of Chipotle locations with smallest link-to-link distance
    - [X] ...
- [X] a GitHub page where results are visualized


### Nice-to-have features

- [X] Color coded cluster visualization
- [X] Clear graph legends

## Description
If you want play golf with your best friend choose this location in Floride

<img src="https://www.francetvinfo.fr/image/75s4gq87o-9885/580/326/21972405.jpg" width="450"/>

### Algorithms' comparison

#### Kmeans

![img](app/plots/kmeans_25.png)

#### DBSCAN

![img](app/plots/dbscan.png)

#### Optics

![img](app/plots/optics.png)

#### Agglomerative

![img](app/plots/agglo.png)

#### BIRCH

![img](app/plots/agglo.png)

#### Gaussian mixture

![img](app/plots/gauss.png)

#### Affinity propagation

![img](app/plots/chips_affinity_propagation.jpg)

## Usage

The content of the analysis is available into the different jupyter notebooks. (They use different clustering algorithms)
## Installation

The needed libraries are in the requirement.txt. To install it, use the command below:
`python -m pip install -r requirements.txt`
To be able to access to the work, you have to install jupyter notebook. You have more information in [this website](https://jupyter.org/) and you can install it with this command:
`pip install jupyterlab`

Links to the official documentation of libraries :
[haversine](https://pypi.org/project/haversine/)
[geopandas](https://geopandas.org/)
[matplotlib.pyplot](https://matplotlib.org/tutorials/introductory/pyplot.html)
[numpy](https://numpy.org/doc/stable/)
[pandas](https://pandas.pydata.org/docs/)
[seaborn](https://seaborn.pydata.org/tutorial.html)
[sklearn.cluster](https://scikit-learn.org/stable/modules/clustering.html)

## Proposition

We use 2 differents clustering models to give you the best place to have chipotle every days and every years.

#### First clustering model

![img](app/plots/kmeans_25_min_150.png)

![img](app/plots/kmeans_best.png)

You can choose between:

![img](app/plots/kmeans_first.png)

![img](app/plots/kmeans_second.png)

![img](app/plots/kmeans_third.png)

#### Second clustering model

![img](app/plots/gauss_150.png)

![img](app/plots/gauss_10.png)

You can choose between:

![img](app/plots/gauss_first.png)

![img](app/plots/gauss_second.png)

![img](app/plots/gauss_third.png)

#### Third clustering model

![img](app/plots/chips_affinity_propagation_inf100.jpg)

![img](app/plots/affinitybest.png)


_Nice and Cosy in New Jersey_:

![img](app/plots/propsaffi1.png)

_Hardcore_:
![img](app/plots/getfat.png)
![img](app/plots/hardcore.png)
Not really a good location  but if [needed](https://www.decathlon.be/fr/browse/c0-tous-les-sports/c1-camping/c3-tentes-pop-up/_/N-mf86su) so you can leave your Chipotle dream life.