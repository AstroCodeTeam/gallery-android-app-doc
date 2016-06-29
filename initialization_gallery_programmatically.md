# Initialization gallery programmatically

Create object that represents gallery and add some albums:
```
...
AGGallery mGallery = new AGGallery(this);

AGAlbum album_1 = new AGAlbum("Capitals of the world","Travel");

album_1.addImage(new AGImage("assets://Paris.jpg"));
album_1.addImage(new AGImage("assets://Berlin.jpg"));
album_1.addImage(new AGImage("assets://Tokyo.jpg"));

mGallery.addAlbum(album_1);

AGAlbum album_2 = new AGAlbum("Carnivores","Animal");

album_2.addImage(new AGImage("assets://Lion.jpg"));
album_2.addImage(new AGImage("assets://Tiger.jpg"));
album_2.addImage(new AGImage("assets://Wolf.jpg"));

mGallery.addAlbum(album_2);
...
```
