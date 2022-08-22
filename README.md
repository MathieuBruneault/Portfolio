# Portfolio

This is a small sample of projects I've worked on over the years, be it on my own or in the context of courses.

## N-body problem

This simulates N particles interacting gravitationally. It is optimized using Fast Fourier Transforms to make what appears to be a O(n^2) problem into a O(nlogn) one, allowing this simulation of up to millions of particles. Of particular interest is the 2_particles.mp4 file, which shows two particles in orbit, and the file periodic.mp4, which shows galaxy formations with a million bodies.

https://user-images.githubusercontent.com/50559300/185988881-e20c7a06-aff7-4891-aa32-2a691aaea558.mp4

The video sometimes doesn't play properly but it should work if you manually set it at about 11 seconds, or you can also see it here: https://www.youtube.com/watch?v=Qj6eYTVf7Ww . This grid starts off with a million randomly placed particles, with no particular distribution (brightness here indicates mass density at that pixel). The grid loops around at the borders, to simulate an infinite (or at least extremely large) universe. As the bodies begin to interact gravitationally, clusters with arms are formed, much like spiral galaxies such as the one we live in. As the galaxies themselves interact and merge, they form elliptical galaxies, just like what the Milky Way will undergo with the Andromeda galaxy in a few million years.

## Housing prices

This is a machine learning project making use of this dataset: https://www.kaggle.com/c/house-prices-advanced-regression-techniques. It predicts housing prices with two different models: a neural network made with TensorFlow, as well as a random forest model.

Hyperparameters are tuned in two different ways: first by looking at the learning curves and tuning to reduce the bias/variance sweet spot. Secondly, we consider a grid of hyperparameters and find out which perform best.

## FRB public Webpage

A website I have worked on while I was doing research in the CHIME/FRB collaboration. It can be seen here: https://www.chime-frb.ca/. While some of the appearance of the website has changed since I worked on it, all the logic and organisation of database display (for instance, the catalog1 page) was done by me.
