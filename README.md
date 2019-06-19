# Ragalahari-Albums-Repository

* Have you ever been thinking that how it's been difficult to download thousands of albums from the [Ragalahari](http://raagalahari.com/) website. and each albums also contains 100's of pictures inside it. The solution to this problem is Ragalahari-Albums-Repository.

* The Ragalahari-Albums-Repository will help you to download the albums from the [Ragalahari](http://raagalahari.com/) website.

## Pre-Requirements ##

* Make sure you are having javascript enabled browser.
* Of course an active internet connection. :D

## How to use ?? ##

Step 1. First you need to visit [Ragalahari](http://raagalahari.com/) website.

Step 2. You will see many of the albums.

Step 3. Open the album you want to download pictures from.

Step 4. (Important) Right click on the very first picture and select Open image in new tab. Make sure the URL will look like as follow 

```sh
https://szcdn.ragalahari.com/XXXXXX/XXXXXXX/1t.jpg or https://szcdn.ragalahari.com/XXXXXX/XXXXXXX/1.jpg

Note : The XXXXXXXXX/XXXXXX  is the actual URL replaced with (X) sign and make sure that the url ends with 1t.jpg and if not then you can do it manually replace the url ending if required.
```

```sh
Example 1:
Before : https://szcdn.ragalahari.com/XXXXXX/XXXXX/5t.jpg //replaced 5t with 1t
After : https://szcdn.ragalahari.com/XXXXXX/XXXXXXX/1t.jpg
```

```sh
Example 2:
Before : https://szcdn.ragalahari.com/XXXXXX/XXXXX/5t.jpg //replaced 5t with 1
After : https://szcdn.ragalahari.com/XXXXXX/XXXXXXX/1.jpg
```


Step 5 : Open the file according to your requirement as shown below and you will see interface on your browser.

| File Name | Usage | URL Parameter |
|-----------|-------|---------------|
| Ragalahari_2.htm | Use if you want to load original images instead of thumbnails from URL | https://szcdn.ragalahari.com/xxxx/xxxx1.jpg
| Ragalahari_3.htm | Use if you want to load thumbnail from single URL | https://szcdn.ragalahari.com/xxxx/xxxx1t.jpg |
| Ragalahari_3_array.htm | Use if you want to load thumbnail of multiple URLS | https://szcdn.ragalahari.com/xxxx/xxxx1t.jpg`give space here` https://szcdn.ragalahari.com/xxxx/xxxx1t.jpg `All the URLS must be white space seperated` |
| Ragalahari_3_array_url.htm | Use if you want to load thumbnail from multiple URLS and save the URlS of the pictures into file when you click on images | https://szcdn.ragalahari.com/xxxx/xxxx1t.jpg`give space here` https://szcdn.ragalahari.com/xxxx/xxxx1t.jpg `All the URLS must be white space seperated`  |
| Ragalahari_3_array_urlload.htm | Use if you want to load thumbnail or images from URLS created from `Ragalahari_3_array_url.htm` file | URLS created from `Ragalahari_3_array_url.htm` file |

Step 6 : Choose file according to your requirement and you will see interface on your browser where you need to enter the following :
1. URL[s] of you image
2. Starting and Ending index to load pictures from that specific URL[s]
3. Click on load Images button `The button is depends on your file selection `

Step 7 : When you click on button the images will be loaded and now you can directly click on the particular images to download them or you can also click on download all button to download all images at once.

Step 8 : Finish

### Conclusion

Thats all from my side still if you find anything which makes my repository works more better then feel free to tell me. you can also contact on `zaidpathan339@gmail.com` Thank you :)
