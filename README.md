# CoveritLive

**Example workflow using CoveritLive to publish live updates during an Oregon Football game.**

Take the concepts and techniques outlined below and apply to any CoveritLive workflow.

## Example: Oregon Football

The below steps outline a typical workflow one can use to cover an Oregon Football game.

[![Example page](https://cloud.githubusercontent.com/assets/4853944/4329161/422e346c-3f92-11e4-9f28-1cf35e49b53b.png)](https://cloud.githubusercontent.com/assets/4853944/4329161/422e346c-3f92-11e4-9f28-1cf35e49b53b.png)

### One day before: [CoveritLive](http://www.coveritlive.com/)

One should prepare the CoveritLive event one day before so as to be prepared for game day.

#### Create event

Login to the RG‘s [CoveritLive](http://www.coveritlive.com/) account and click on the “Add New Event” link:

![new-event](https://cloud.githubusercontent.com/assets/218624/4510407/1c3fbc28-4b2a-11e4-923b-2f7cba3fcfb8.gif)

#### “Build an Event”, page 1

Fill in the form fileds as best as you can.

Turn off “Social Sharing” option:

![social-sharing](https://cloud.githubusercontent.com/assets/218624/4484825/9a0d6314-49c0-11e4-8ac1-f8f75cd8470b.png)

Click “Next Step >>”.

![next-step](https://cloud.githubusercontent.com/assets/218624/4510446/7bf5a830-4b2a-11e4-9401-f165266fcc47.gif)

#### “Build an Event”, page 2

Fill in the form fileds as best as you can.

Input a custom URL into the “Location / URL” field:

![location-url](https://cloud.githubusercontent.com/assets/218624/4510471/addfd276-4b2a-11e4-81a7-749523cc4af7.png)

Typically, this URL should be an RG-branded [bit.ly](https://bitly.com/) link, e.g.: <http://rgne.ws/UOvsMSU>

Scroll down to “Embed Code“ section and turn “ON” the “100% Width” and “Infinite Height” options:

![embed-code-options](https://cloud.githubusercontent.com/assets/218624/4510693/109ed13a-4b2d-11e4-99fe-dfd9aa95cdfa.png)

Click the blue “Save Event” button:

![save](https://cloud.githubusercontent.com/assets/218624/4510653/a5553338-4b2c-11e4-85d2-51aeacf7e02a.gif)

#### “Prep Mode”

On the “My Upcoming Events" page, click the “Prep Mode” button for the event you just created:

![prep-mode](https://cloud.githubusercontent.com/assets/218624/4510853/8a5069c0-4b2e-11e4-9830-65c16d46ba45.gif)

#### Social media automation

Click on the “Social Automate” icon (on the upper-right side) and add in `rgsports/lists/football-updates`. This will bring everyone in the [@rgsports](https://twitter.com/rgsports/) [“Football updates” list](https://twitter.com/rgsports/lists/football-updates) into the “SmartStream” center column:

![social](https://cloud.githubusercontent.com/assets/4853944/4328758/2b3753e4-3f8b-11e4-94f6-ebc72351e4b7.gif)

Optionally, add other individuals (or lists) that pertain to this game.

#### Add scoreboard widget

Click on the “Scoreboard” icon (on the upper-right side) and sort through options to add the upcoming game you’ll be covering:

![scoreboard](https://cloud.githubusercontent.com/assets/218624/4510908/050a6044-4b2f-11e4-8d0f-68a0fa6326f5.png)

Click the blue “Publish” button.

#### Pre-populate

Find pre-game coverage (e.g., tweets from the sports staff) via the search icon in the top-right corner. Once found, click the plus icon that appears when hovering over tweet. This should be approximately 5 tweets, consisting of the stories in today’s newspaper and/or any other relevant information:

![search](https://cloud.githubusercontent.com/assets/218624/4510993/0a902746-4b30-11e4-8045-4e5db7ad84aa.png)

### One day before: [WordPress](http://blogs.registerguard.com/oregon-football/)

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

Below, [embed tweets](https://github.com/rgnewsroom/twitter/tree/gh-pages/embeds) that contain story information.

#### Publish post

Publish post one day before game day.

#### Shorten URL

Copy post URL and shorten with bit.ly using The Register-Guard’s account, which will produce an `rgne.ws` URL.

#### Promote

Share and promote landing on social media.

### Game day: Pre-game coverage

At the beginning of your day, aggregate more social media from today’s paper into the WordPress blog post. Be sure to also add that content into the CoveritLive “Prep Mode” interface.

Make sure to update publish date of the WordPress blog post so that it reflects the current time.

Continue updating with any relevant information throughout the day.

### Game day: One hour prior to game

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

### In-game coverage

Aggregate social media throughout game using CoveritLive interface.

Occasionally check `#goducks` hashtag for other visual content.

As the game progresses, update post title to reflect quarter and score (e.g., “4th quarter: Oregon 24, Arizona 31 | Live updates and game day information”.

Throughout game update the post’s publish date.

### Post-game coverage

Finish off by thanking fans and by linking to story recap and teasing other stories.

End the event, this should be within an hour of the game ending since these are “live updates”. It’s nice to end with a link to the recap story.

![end](https://cloud.githubusercontent.com/assets/218624/4511796/fdc5ec90-4b38-11e4-8b9a-dd27801cb0ce.gif)
