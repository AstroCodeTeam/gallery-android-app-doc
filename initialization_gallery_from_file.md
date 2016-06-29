# Initialization gallery from file

Async gallery initialization:
```
...
AGGallery.init(this,"assets://gallery_config.xml", new AGGallery.AGGalleryInitListener() {
    @Override
    public void onComplete(AGGallery gallery) {
        mGallery = gallery;
        }

    @Override
    public void onFail() {
        mGallery = null;
        Toast.makeText(MainActivity.this, "Initialization failed!", Toast.LENGTH_SHORT).show();
        }
});
...
```