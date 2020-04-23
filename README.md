# Wardrobe Organizer

At the age of 17, I was introduced to Polyvore. A cool website which allowed user's to put together outfits in any way they liked. I loved it! It gave me the idea to create an app which worked in a similar way. This idea blossomed in my mind when AI was not yet as advanced as it is now. Later on in this post, I will cover how I have updated the concept using Deep Learning. 

<!-- wp:heading {"level":3} -->
<h3>Ideology</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Enable women to experiment with their clothing virtually and come up with new combinations, rather than wasting hours actually changing into different clothing.  </p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>Method</h3>
<!-- /wp:heading -->

<!-- wp:list {"ordered":true} -->
<ol><li>The user takes images of their clothing. It does not have to be artistic, it could even be a shot of just one detail of the garment (for example a beaded collar). The objective is for the user to be able to recognise the garment later on.</li><li>The user then selects the type of clothing they just took a picture of from the list displayed on the screen.</li><li>The user can then retrieve the images later.</li></ol>
<!-- /wp:list -->

<!-- wp:paragraph -->
<p>I was unhappy with the method above because it is not user friendly. There is too much effort that the user has to put in. I needed to simplify the process. Cue, the magic of Deep Learning.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>Applying Deep Learning</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Now, I came across a dataset known as the "<a href="https://github.com/zalandoresearch/fashion-mnist" rel="nofollow">Fashion MNIST</a>". This is the solution to my problem! By designing and training a model using the Fashion MNIST dataset, I can now have the app do the sorting for the user. All the user has to do is take images of garments in their wardrobe.</p>
<!-- /wp:paragraph -->

<p align="center">
  <img width="" height="" src="https://github.com/zalandoresearch/fashion-mnist/raw/master/doc/img/embedding.gif">
</p>

<!-- wp:paragraph -->
<p>For more information on Fashion MNIST, visit the link below:</p>
<!-- /wp:paragraph -->

https://github.com/zalandoresearch/fashion-mnist/tree/master/data/mnist


https://github.com/zalandoresearch/fashion-mnist/tree/master/data/mnist


<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.vins.vinslookbook&hl=en">
  <img width="300" height="80" src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSojpFFWqTqH_wHsjAwe--ZdKXrsSNZBDWNNz4qK8fYRX_wK0Wb&usqp=CAU"> 
</p>
