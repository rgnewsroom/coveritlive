# CoveritLive example: Oregon Football

**Example workflow using CoveritLive to publish live updates during an Oregon Football game.**

Take the concepts and techniques outlined below and apply to any CoveritLive workflow.

The below steps outline a typical workflow one can use to cover an Oregon Football game.

[![Example page](https://cloud.githubusercontent.com/assets/4853944/4329161/422e346c-3f92-11e4-9f28-1cf35e49b53b.png)](https://cloud.githubusercontent.com/assets/4853944/4329161/422e346c-3f92-11e4-9f28-1cf35e49b53b.png)

## One day before

### [CoveritLive](http://www.coveritlive.com/)

One should prepare the CoveritLive event one day before so as to be prepared for game day.

#### Create event

Login to the RG‘s [CoveritLive](http://www.coveritlive.com/) account and click on the “Add New Event” link:

![new-event](https://cloud.githubusercontent.com/assets/218624/4510407/1c3fbc28-4b2a-11e4-923b-2f7cba3fcfb8.gif)

#### “Build an Event”, page 1

Fill in the form fileds as best as you can.

***Turn off “Social Sharing” option. This is important because if you don't do this you will automatically tweet from The Register-Guard twitter account with some boilerplate garbage that will not be good.***

![social-sharing](https://cloud.githubusercontent.com/assets/218624/4484825/9a0d6314-49c0-11e4-8ac1-f8f75cd8470b.png)

Click “Next Step >>”.

![next-step](https://cloud.githubusercontent.com/assets/218624/4510446/7bf5a830-4b2a-11e4-9401-f165266fcc47.gif)

#### “Build an Event”, page 2

Fill in the form fileds as best as you can.

Input a custom URL into the “Location / URL” field. It's ok if you have not made one yet, just be sure to remember to make one later after you create the blog post.

![location-url](https://cloud.githubusercontent.com/assets/218624/4510471/addfd276-4b2a-11e4-81a7-749523cc4af7.png)

Typically, this URL should be an RG-branded [bit.ly](https://bitly.com/) link, e.g.: <http://rgne.ws/UOvsMSU>

Scroll down to “Embed Code“ section and turn “ON” the “100% Width” set the height to 1250px.

Click the blue “Save Event” button:

![save](https://cloud.githubusercontent.com/assets/218624/4510653/a5553338-4b2c-11e4-85d2-51aeacf7e02a.gif)

#### “Prep Mode”

On the “My Upcoming Events" page, click the “Prep Mode” button for the event you just created:

![prep-mode](https://cloud.githubusercontent.com/assets/218624/4510853/8a5069c0-4b2e-11e4-9830-65c16d46ba45.gif)

#### Social media automation

Click on the “Social Automate” icon (on the upper-right side) and add in `rgsports/lists/football-updates`. This will bring everyone in the [@rgsports](https://twitter.com/rgsports/) [“Football updates” list](https://twitter.com/rgsports/lists/football-updates) into the “SmartStream” center column when the event is open:

![social](https://cloud.githubusercontent.com/assets/4853944/4328758/2b3753e4-3f8b-11e4-94f6-ebc72351e4b7.gif)

Optionally, add other individuals (or lists) that pertain to this game.

If you would like to automate the process a bit more you can turn Moderation off for certain people. This will automatically publish the selected individuals instead of just adding them to the SmartStream for moderation. It's often alright to add:

* @rgduckfootball
* @stevemims_rg
* @rgsports
* Photogs on the field

Be wary of responses they may tweet to individuals that would look out of place when published.

#### Add scoreboard widget

Click on the “Scoreboard” icon (on the upper-right side) and sort through options to add the upcoming game you’ll be covering:

![scoreboard](https://cloud.githubusercontent.com/assets/218624/4510908/050a6044-4b2f-11e4-8d0f-68a0fa6326f5.png)

Click the blue “Publish” button.

#### Pre-populate

**This part is not always necessary but helpful to get the feel of CoveritLive before the event starts.**

Via the search icon in the top-right corner, find at least 5 tweets of pre-game coverage (e.g., tweets from the sports staff ) consisting of the stories in today’s newspaper and/or any other relevant information:

![search](https://cloud.githubusercontent.com/assets/218624/4510993/0a902746-4b30-11e4-8045-4e5db7ad84aa.png)

Once desired content is found, click the plus icon (that appears when hovering over tweet) and add it to the “Published Content” box:

![add-tweet](https://cloud.githubusercontent.com/assets/218624/4512094/5b37f51e-4b3c-11e4-9c81-62cdcbfe31f6.gif)

### [WordPress](http://blogs.registerguard.com/oregon-football/)

Login to WordPress and create a new Oregon Football blog post.

**Note:** View an [example WordPress post](http://blogs.registerguard.com/oregon-football/?p=21483&preview=true) (must be logged in) that contains all of the necessary components listed below.

#### Create post

**Important:** Switch post editing mode to “Text”:

![text](https://cloud.githubusercontent.com/assets/218624/4511385/2a87561a-4b34-11e4-8c3a-e543b772e8a5.gif)

Add these elements:

* Post title
* “Live updates” subcategory under “Game coverage” parent category
* Post author
* Tags (e.g., `oregon, ducks, football, live, updates, news, visiting-team, eugene, register, guard`)
* Make post sticky (found via “Edit” next to “Visibility”)

#### Add post content

Add boilerplate game day information, for example:

```html
<section>
	<h1 class="h5" style="margin: 20px 0;">Matchup: Ducks vs. Spartans</h1>
	<ul class="li2">
		<li><b>When:</b> 3:35 p.m. PDT</li>
		<li><b>Where:</b> Autzen Stadium</li>
		<li><b>TV:</b> Fox networks</li>
		<li><b>Radio:</b> KUGN-AM (590) and KZEL-FM (96.1)</li>
		<li><b>Tickets:</b> Fewer than 75 reserved seats and standing room only tickets were available Thursday afternoon. Tickets are on sale at the Moshofsky Center and at www.goducks.com</li>
		<li><b>ESPN GameDay:</b> Broadcast begins at 6 a.m. from Memorial Quad.</li>
		<li><b>Gates open:</b> Parking lot opens four hours before kickoff; Moshofsky Center opens three hours before kickoff; and stadium bowl opens 90 minutes before kickoff.</li>
		<li><b>Bus info:</b> <a href="http://www.ltd.org">ltd.org</a></li>
		<li><b>Records:</b> No. 3 Oregon 1-0, No. 7 Michigan State 1-0</li>
	</ul>
</section>
```

Below, [manually embed tweets](https://github.com/rgnewsroom/twitter/tree/gh-pages/embeds) that contain relevant story information.

#### Publish post

Publish post one day before game day.

#### Shorten URL

Copy the post’s URL and shorten with [bit.ly](https://bitly.com/); login using the Register-Guard’s bit.ly account in order to obtain an `rgne.ws` URL. This should match the shortlink you put into CoveritLive earlier.

#### Promote

Share and promote blog post landing page on social media, e.g., [Twitter](https://twitter.com/robertrdenton/status/517719999008346112):

[![promote Twitter](https://cloud.githubusercontent.com/assets/218624/4512230/d7ea4110-4b3d-11e4-9b4e-513ceef7cdf2.png)](https://twitter.com/robertrdenton/status/517719999008346112)

… and [Facebook](https://www.facebook.com/registerguard/posts/10152345753397256):

[![promote-facebook](https://cloud.githubusercontent.com/assets/218624/4512268/3324b1aa-4b3e-11e4-8435-d77629398fc8.png)](https://www.facebook.com/registerguard/posts/10152345753397256)

## Game day

### Pre-game coverage

At the beginning of your day, aggregate more social media from today’s paper into the WordPress blog post. Be sure to also add that content into the CoveritLive “Prep Mode” interface.

Make sure to update publish date and time of the WordPress blog post so that it reflects the current time.

Continue updating with any relevant information throughout the day.

### One hour prior to game

#### Launch CoveritLive event

From the “Prep Mode” interface, click “Tools” and click “Launch Event”:

![launch](https://cloud.githubusercontent.com/assets/218624/4511608/d08e3996-4b36-11e4-85cd-17d534c60263.gif)

**Note:** Event will be automatically closed 24 hours after launching.

#### Get CoveritLive embed code

Copy the CoveritLive embed code found in the “Tools” section of the interface:

![embed](https://cloud.githubusercontent.com/assets/218624/4511692/d40fc278-4b37-11e4-9dd1-023688659bb2.png)

#### Update WordPress post

Remove all social media embeds in post and replace with CoveritLive embed code:

![embed-in-post](https://cloud.githubusercontent.com/assets/218624/4511720/1b45449c-4b38-11e4-9130-a6f7fd57ba20.png)

… and update the post’s publish date.

### Push notifications

Typical games will warrant three push notifications. One prior to the game, one after the first half and one after the completion of the game.

Prior:

![prior](https://cloud.githubusercontent.com/assets/4853944/5098467/861efb88-6f3b-11e4-8f62-4bbe869747f8.png)

---
Half:

![half](https://cloud.githubusercontent.com/assets/4853944/5098468/861fecc8-6f3b-11e4-9cae-306ceb675a22.png)

---
Final:

![final](https://cloud.githubusercontent.com/assets/4853944/5098469/862cc182-6f3b-11e4-9ba5-7cb5543a282d.png)



### In-game coverage

Aggregate social media throughout game using CoveritLive interface. If you have moderation turned off for any individuals, make sure to keep an eye on them.

Occasionally check `#goducks` hashtag for other visual content.

As the game progresses, update post title to reflect quarter and score (e.g., “4th quarter: Oregon 24, Arizona 31 | Live updates and game day information”. Also be sure to update the title of the GAMEDAY story via DT to reflect quarter and score.

Throughout game update the post’s publish date.

### Post-game coverage

Finish off by thanking fans and by linking to story recap and teasing other stories.

I'll tweet post-game stats and post-game presser quotes if the real-time audience is still strong. This can be measured via Google Analytics if you feel so inclined.

End the event, this should be within an hour of the game ending since these are “live updates”. It’s nice to end with a link to the recap story.

![end](https://cloud.githubusercontent.com/assets/218624/4511796/fdc5ec90-4b38-11e4-8b9a-dd27801cb0ce.gif)
