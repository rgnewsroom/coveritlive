# Football live updating

### Table of contents

* [One day before](#one-day-before)
* [Game day](#game-day)
* [HTML basics](#html-basics)
* [Embed basics](#embed-basics)
* [Twitter embeds](#tweets)
* [Instagram](#instagram)
* [YouTube](#youtube)
* [Etc.](#etc)

---

### One day before

**See preview of example WordPress post [here](http://blogs.registerguard.com/oregon-football/?p=21483&preview=true) (must be logged in)**


* Create new CoverItLive event, turn social sharing off
* Add in the custom URL you set up via bit.ly. ie: http://rgne.ws/UOvsMSU
* Turn on 100% width in Embed field
* Turn on Infinite Height


![cil](https://cloud.githubusercontent.com/assets/4853944/4328586/fa6a96de-3f87-11e4-8d85-ed8d9d0bf89c.gif)


* Enter prep mode for the event, collect some recent social media goodness from the sports staff
* Follow those links and embed the tweets into a new WordPress post that follows the same styles as a previous post. Make sure you add plenty of tags such as:
  * `oregon, ducks, football, live, updates, news, visiting-team, eugene, register, guard` 
* Add in the game-day info above the embedded tweets. Make sure that the info is styled correctly, see previous posts such as MSU or Wyoming.
* Let it sit, adding in pertinent stories as needed.
* Go back to CoverItLive.
* Click on `Social Automate` on right side and add in `rgsports/lists/football-updates`. This will bring everyone in the rgsports football updates list into the SmartStream in the center.

![social](https://cloud.githubusercontent.com/assets/4853944/4328758/2b3753e4-3f8b-11e4-94f6-ebc72351e4b7.gif)

* Add additional users if needed, ie: interns, etc.
* Go down to scoreboard and add that for the current game.

![score](https://cloud.githubusercontent.com/assets/4853944/4328780/621f1202-3f8b-11e4-97ca-a303f90dd5a3.gif)

### Game day

* Start aggregating other pre game social media and try making some of your own via prep mode.
* When you have about ten posts or so launch the event and embed it in the post. Wipe the other embeds out of the post.
* Continue adding content throughout and respond to the comments as necessary. 
* Update the publish time on the post and the headline with each score/quarter change.
* Finish off by thanking fans and by linking to story recap and teasing other stories.
* End the event, this should be within an hour of the game ending since these are "live updates". It's nice to finish off with a link to the recap story.

## Other info

### HTML basics

If you've looked at the template code, you'll know that there is some minor HTML code for styling. Here's what you need to know:

* `<h1>` is a headline tag.
* `</h1>` is a closing headline tag. This means anything between these two tags will be styled like a headline.
* `class="h4"` modifies the tag it's in so that the headline is not too dominant on the page.
* `style="margin:0 20px"` further modifies the tag so that the spacing looks good.

So `<h1 class="h4" style="margin: 0 20px">This is my headline</h1>` can just be thought of as a headline.

The embed codes will be addressed later, but this is pretty much all of the code you'll need to know. The first `<h1>` is slightly different because it's styled as the top score. All of the `<h1>`s should be the same because they're just bolded headlines down below in the text.

Plain text is simply displayed as text.

### Embed basics

It's easy to embed tweets, Instagram photos and even Facebook photos. Here's how.

You always want to paste embed codes into the Text editor in WordPress, not the Visual editor. Also, if you start using the Text editor, you don't want to switch back and forth. In the past switching from Text to Visual has catastrophically broken WordPress posts. 

If working in only the Text editor worries you, don't worry about it. See someone on the Web Team to help you out. Some general tips are:

* The text editor is the exact same as the Visual editor except instead of visual elements, you'll have code blocks. If you're ever not sure what part of the page you're editing you can simply add some text and check a preview.
* Use a preview or published version of the story as a road map. This can help you figure out where in the page you are or help you add text in between code blocks.
* Never try and alter a code block unless you know exactly what you're changing. If you accidently delete a character or if you're not sure, go grab the embed code again and re-paste it in.
*There are (generally) two types of embed codes. The first looks like: `<iframe ... ></iframe>` and the second looks like `<script> ... </script>`. While these are text-based, think of them as one unit. Never try and break them up or delete spaces. 

#### Tweets
You can embed tweets from a number of places. You can find them via Storify, TweetDeck or straight Twitter. The most direct way is to go to the page for the tweet. Not the feed or the person, but the page for the individual tweet. The URL should looks something like this: 
`https://twitter.com/rgsports/status/508411001390112768`

The page should look like this:
![screen shot 2014-09-08 at 3 25 29 pm](https://cloud.githubusercontent.com/assets/4853944/4193929/108eeb4c-37a7-11e4-8f08-f48bdfd0aa92.png)

If you make it to this page, click on the more options three horizontal dots and click embed.

![asdf](https://cloud.githubusercontent.com/assets/4853944/4194514/3cec7954-37af-11e4-83a0-4766af11fbe8.gif)

Then simply copy the code and paste it in where you want it to go in the post.


You can also embed tweets from a straight Twitter stream or TweetDeck:

![asdfasdf](https://cloud.githubusercontent.com/assets/4853944/4194588/d9913056-37af-11e4-9fac-f58f26cd8093.gif)

-

![asdfasdfasdf](https://cloud.githubusercontent.com/assets/4853944/4194625/ac2e1880-37b0-11e4-97e9-634cb4e725cf.gif)


Really, anytime Twitter gives you those three dots, you can embed a tweet.

#### Instagram

Instagram is very similar except you have to get the the user's page. Suggested work flow goes as follows:

1. Find images via Storify.
1. Drag image into Storify "list"/"collection"/"stream"/whatever
1. Click on the username of the photo you want.
1. That should take you to their page with a bunch of photos. Find the image you want and click on it. That should open a shadow box for that single image.
1. Click `Embed` and copy the code. Paste it in the post where you want it to go.

![insta](https://cloud.githubusercontent.com/assets/4853944/4194696/e877dcbc-37b1-11e4-8cff-ff6864a9d85a.gif)

#### YouTube

Now, this one is a little more tricky.

![screen shot 2014-09-08 at 3 47 04 pm](https://cloud.githubusercontent.com/assets/4853944/4194160/1add352e-37aa-11e4-9fdd-7bf5c8759165.png)

1. Click `Share` below any video. Then click `Embed`.
1. Copy that code and paste it in the post where you want it to go.
1. This is the tricky part. Add `<div class="mm">` before the code you just pasted in.
1. Add `</div>` after the YouTube code. 
1. Place the cursor after the first `iframe` in the YouTube code. Type space and add this: `class="embed"`.
1. The final result should look something like this:

```html
<div class="mm"><iframe class="embed" width="1280" height="720" src="//www.youtube.com/embed/m-RPwpcjTho?rel=0" frameborder="0" allowfullscreen></iframe></div>
```

Any other embed code you run into should be similar the the use cases above. 

### Etc.

* You'll want to update the publish time pretty frequently, this keeps the blog at the top of blogs on the home page and helps people understand that it was recently updated.

