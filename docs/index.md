## jj's Image Host Documentation

Note: Since the api doesn't have much features yet, I will still show you some of the api features you can use. All of these api features are avaliable in any language that supports [POST] and [GET].
### [1]: Uploading a simple image using POST

The /add url allows you to upload images

Html Code Example:
```html
<form action="https://jjdev.ga/add" enctype="multipart/form-data" method="post"><input name="file" type="file" />
  <input type="submit" value="Create Image" />
</form>
```

### [2]: Getting Image Data
You can access image data by using GET

Examples:
going to https://jjdev.ga/v1/imagedata?image=615692867214d1d0d5b979f02c998726.PNG will return a json
this will allow you to use it in any language you want
you will need to add the image name + file extension cuz currently we do not support it on the api

Json Descriptions

response: the page response

fullname: the full name of the image

uploaded: the date/time the image was uploaded

Note: the api is in the beta stage so not a lot is done yet
