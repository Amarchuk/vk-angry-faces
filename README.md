# My Vk Angry Faces

Using [Microsoft Cognitive Serices Emotion API](https://www.microsoft.com/cognitive-services/en-us/emotion-api#detection) for emotions detection on VK photos. 

[Notebook on Nbviewer](https://nbviewer.jupyter.org/github/Amarchuk/vk-angry-faces/blob/master/My%20Angry%20Faces.ipynb).

Instructions:
- get IPython (Jupyter) Notebook (simplest way - download [Anaconda](https://www.continuum.io/downloads))
- register on [Microsoft Cognitive Serices](https://www.microsoft.com/cognitive-services/en-us/emotion-api#detection) and get key for free 30,000 API calls
- give my app access to obtain photos - run https://oauth.vk.com/authorize?client_id=5578186&scope=photos&redirect_uri=https://oauth.vk.com/blank.html&display=page&v=5.0&response_type=token (you can register your own desktop app in VK at https://vk.com/apps?act=manage and change client_id)
- copy access_token from obtained link
- select prefered album_id (if None than will load photos on which user tagged) and insert your user_id
- Run all cells and enjoy! (note that API's performance is 20 photos/min)

| [![happy](https://github.com/Amarchuk/vk-angry-faces/blob/master/pics/1.png)](happy)  | [![sad](https://github.com/Amarchuk/vk-angry-faces/blob/master/pics/2.png)](sad) |
|:---:|:---:|

| [![disg](https://github.com/Amarchuk/vk-angry-faces/blob/master/pics/3.png)](disg)  | [![neu](https://github.com/Amarchuk/vk-angry-faces/blob/master/pics/4.png)](neu) |
|:---:|:---:|
