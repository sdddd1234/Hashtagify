
```javascript

    _  _   _    _           _     _              _  __       
  _| || |_| |  | |         | |   | |            (_)/ _|      
 |_  __  _| |__| | __ _ ___| |__ | |_ __ _  __ _ _| |_ _   _ 
  _| || |_|  __  |/ _` / __| '_ \| __/ _` |/ _` | |  _| | | |
 |_  __  _| |  | | (_| \__ \ | | | || (_| | (_| | | | | |_| |
   |_||_| |_|  |_|\__,_|___/_| |_|\__\__,_|\__, |_|_|  \__, |
                                            __/ |       __/ |
                                           |___/       |___/ 

```

# [Hashtagify](https://github.com/vinitshahdeo/Hashtagify)

[![Hashtagify](https://img.shields.io/badge/Hashtagify-dodgerblue.svg?style=flat&logo=instagram&logoColor=white)](https://github.com/vinitshahdeo/Hashtagify) [![Google Vision](https://img.shields.io/badge/Vision-API-critical.svg?style=flat&logo=google&logoColor=white)](https://cloud.google.com/vision/docs/quickstart) [![Imgur API](https://img.shields.io/badge/Imgur-API-critical.svg?style=flat&logo=highly&logoColor=white)](https://api.imgur.com/)

## Generate [#Hashtags](https://github.com/vinitshahdeo/Hashtagify) for your next [Instagram](https://www.instagram.com/vinitshahdeo/) Post!

![Hashtagify](./hashtagify.gif)

> **A web app which suggests hashtags for your picture! It might help you to come up with relevant <kbd>[#hashtags](https://github.com/vinitshahdeo/Hashtagify)</kbd> for your next [Instagram](https://www.instagram.com/vinitshahdeo/) post :p and it may get more eyes on your Instagram posts.**

![#](https://cdn-images-1.medium.com/max/1600/1*XPpoo_5jt2_EngZSdgZS2Q.png)

### APIs Used

- [Google Vision API](https://cloud.google.com/vision/docs/quickstart) - Google Cloud’s Vision API offers powerful pre-trained machine learning models through REST and RPC APIs.

- [Imgur API](https://api.imgur.com/) - Imgur's API exposes the entire Imgur infrastructure via a standardized programmatic interface. Using Imgur's API, you can do just about anything you can do on imgur.com, while using your programming language of choice.

### Getting Started

- Get your own imgur clientID [here](https://api.imgur.com/endpoints/image).
- Replace `XXXXXXXXX` with your clientID in `js/upload.js`.

```javascript
new Imgur({ 
    clientid: 'XXXXXXXXX', // replace this 
    callback: feedback 
});
```
- Get API keys for [Google Cloud Vision API](https://cloud.google.com/vision/docs/quickstart).

- Replace `XXXXXXXX` with your API keys in `js/upload.js`

```javascript

var settings = {
      "async": true,
      "crossDomain": true,
      // change the key below
      "url": "https://vision.googleapis.com/v1/images:annotate?key=XXXXXXXXXXXXXXXXXXX",
      "method": "POST",
      "headers": {
        "Content-Type": "application/json",
        "cache-control": "no-cache"
      },
      "processData": false,
      "data": str
    }

```

- Now open `index.html`

### Need Help ?

[![Facebook](https://img.shields.io/static/v1.svg?label=follow&message=@vinit.shahdeo&color=9cf&logo=facebook&style=flat&logoColor=white&colorA=informational)](https://www.facebook.com/vinit.shahdeo)  [![Instagram](https://img.shields.io/static/v1.svg?label=follow&message=@vinitshahdeo&color=grey&logo=instagram&style=flat&logoColor=white&colorA=critical)](https://www.instagram.com/vinitshahdeo/) [![LinkedIn](https://img.shields.io/static/v1.svg?label=connect&message=@vinitshahdeo&color=success&logo=linkedin&style=flat&logoColor=white&colorA=blue)](https://www.linkedin.com/in/vinitshahdeo/)

:email: Feel free to contact me via email.

[![GMAIL](https://img.shields.io/static/v1.svg?label=send&message=vinitshahdeo@gmail.com&color=red&logo=gmail&style=social)](https://www.github.com/vinitshahdeo)

### License

MIT &copy; [Vinit Shahdeo](https://github.com/vinitshahdeo/Hashtagify/blob/master/LICENSE)

---------

```javascript

╦ ╦╔═╗╔═╗╦ ╦╔╦╗╔═╗╔═╗╦╔═╗╦ ╦
╠═╣╠═╣╚═╗╠═╣ ║ ╠═╣║ ╦║╠╣ ╚╦╝
╩ ╩╩ ╩╚═╝╩ ╩ ╩ ╩ ╩╚═╝╩╚   ╩ 


if (isAwesome) {
    // thanks in advance :p
    starThisRepository();
}

```

-----------


