# Facebook Meme Blocker
Facebook has been [automatically adding `alt` tags](https://code.facebook.com/posts/457605107772545/under-the-hood-building-accessibility-tools-for-the-visually-impaired-on-facebook/) to images you upload that are populated with keywords representing the content of your images. This project is a hack to block all the images which contains 'text' or 'meme' in alt tag, which generally covers most of the memes. The image can still be viewed in enlarged view by clicking on it.

To reduce the aggressiveness, change line 30 in facebook.js to tag = 'meme'.