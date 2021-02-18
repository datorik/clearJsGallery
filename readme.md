# Clear JS Hashtag Gallery (clearJsGallery)

## Image gallery  with hashtags, excluding libraries

## Demo

[https://datorik.github.io/clearJsGallery](https://datorik.github.io/clearJsGallery)

## Example

![](examples/Screenshot.png)

### Installing
```
Just add it on page
```
### Settings
Init
```
new clearJsGallery(galleryImagesList, settings);
```
galleryImagesList
```
'example.jpg': { //Image name
                    name: 'Example',
                    linkText: 'example',
                    link: '/',
                    hashtag: ['EXAMPLE', 'EXAMPLE2'] // one or more  hashtag
                }
```
settings
```
{
    multiSelection: true,
    imageLink: true,
    showTextLink: true,
    allBtnText: 'All', // all button text
    selectType: 'AND', // 'AND' or 'ALL'
    btnContainerID: 'clearJSgalleryBtnContainer', // button container ID
    rowContainerID: 'clearJSgalleryRowContainer', // gallery container ID
    imagesDir: 'images/' // images directory
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

[Russian readme](readme-ru.md)

