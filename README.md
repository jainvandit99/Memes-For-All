![](https://raw.githubusercontent.com/jainvandit/Memes-For-All/master/Memes%20For%20All/Assets.xcassets/AppIcon.appiconset/Icon-App-83.5x83.5%402x.png)
# Memestagram!
Memestagram is a light weight iOS Application that lets you browse through the different meme templates and view individual submissions for the same.

## Design
The app uses a simple ```UITableView``` for the home screen and a simple ```UICollectionView``` to implement the grid on the submissions screen.

<img src="https://raw.githubusercontent.com/jainvandit/Memes-For-All/master/Final%20Look%20Assets/HomeScreen.png" width="250"><img src="https://raw.githubusercontent.com/jainvandit/Memes-For-All/master/Final%20Look%20Assets/SubmissionsScreen.png" width="250"><img src="https://raw.githubusercontent.com/jainvandit/Memes-For-All/master/Final%20Look%20Assets/ErrorScreen.png" width="250">
## API
## Optimisation
* To save data consumption, the ```Kingfisher``` image caching library is used. It doesn't fetch the image repeatedly unless its contents are changed and only loads the image once
* 
## External Frameworks Used
* [```NVActivityIndicatorView```](https://github.com/ninjaprox/NVActivityIndicatorView) - is a collection of awesome loading animations.
* [```Kingfisher```](https://github.com/onevcat/Kingfisher) - Kingfisher is a powerful, pure-Swift library for downloading and caching images from the web.
* [```TagListView```](https://github.com/ElaWorkshop/TagListView) - Simple and highly customizable iOS tag list view.
