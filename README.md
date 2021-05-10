# randomStyleTranfer
Perform style tranfer on random images


## Add this line to load images from the web
```
  content_path = tf.keras.utils.get_file('YellowLabradorLooking_new.jpg', 'https://storage.googleapis.com/download.tensorflow.org/example_images/YellowLabradorLooking_new.jpg')
  style_path = tf.keras.utils.get_file('kandinsky5.jpg','https://storage.googleapis.com/download.tensorflow.org/example_images/Vassily_Kandinsky%2C_1913_-_Composition_7.jpg')
```

## Need to add these functionalities
- [ ] Needs to download Images contentImage.jpg and styleImage.jpg
- [x] Added functionalities to download Image from DuckDuckGo based on your search
- [ ] Add functionality either to download random images or image based on keyword
