<template>
  <div id="app">
  <div class="page-container article-single-container  ">
      <section class="lede entry-header" id="">
          <div v-editable v-bind:active="activeEdit" key="article.topics" v-bind:edit-method="topicSelection.bind(this, true)" class="primary-topic">
              <a href="//broadly.vice.com/en_us/topic/politics">{{ article.topics[0] }}</a>
          </div>
          <h1 v-editable v-bind:active="activeEdit" key="article.title" class="entry-title">{{ article.title }}</h1>
          <div class="entry-subheader">
              <div class="contributor-widget">
                  <a href="//broadly.vice.com/en_us/contributor/brenna-ehrlich">
                      <div class="contributor-image"><img src="//broadly-images.vice.com/images/contributors/meta/2016/04/02/brenna-ehrlich-1459630909.jpg?crop=1xw:1xh;center,top&amp;resize=300:*&amp;output-quality=70" alt="Brenna Ehrlich"></div>
                  </a>
                  <div class="contributor-name">
                      <span class="byline">by <a href="//broadly.vice.com/en_us/contributor/brenna-ehrlich">{{ article.byline.name }}</a></span>
                  </div>
              </div>
              <div class="date-time-container">
                  <span v-editable v-bind:active="activeEdit" key="article.date" class="date">{{ article.date }}</span>
                  <span v-editable v-bind:active="activeEdit" key="article.time"  class="time"> {{ article.time }}</span>
              </div>
              <section id="" class="share-widget article-share" data-title={ article.title } data-tweet={ article.tweet } data-url="https://broadly.vice.com/en_us/article/a-palm-reader-who-claims-she-read-donald-trumps-hand-tells-all" data-media="//broadly-images.vice.com/images/articles/meta/2016/04/03/the-palm-reader-who-claims-she-read-donald-trumps-hand-1459715053.jpg?crop=0.75xw:1xh;center,top" data-topic="Politics">
                  <div class="facebook" data-share-type="facebook">
                      <span class="circle-frame">
                        <span class="site-icon icon-facebook"></span>
                      </span>
                  </div>
                  <div class="twitter" data-share-type="twitter">
                      <span class="circle-frame">
                        <span class="site-icon icon-twitter"></span>
                      </span>
                  </div>
                  <div class="pinterest" data-share-type="pinterest">
                      <span class="circle-frame">
                        <span class="site-icon icon-pinterest"></span>
                      </span>
                  </div>
              </section>
          </div>
      </section>
      <div class="entry-container">
          <div class="column left">
              <section class="lede left-col" id="">
                  <div class="image-container">
                      <img class="sixteenbynine" src="//broadly-images.vice.com/images/articles/meta/2016/04/03/the-palm-reader-who-claims-she-read-donald-trumps-hand-1459715053.jpg?crop=1xw:0.75xh;center,top&amp;resize=1000:*&amp;output-quality=70" alt="A Palm Reader Who Claims She Read Donald Trump's Hand Tells All">
                      <p class="image-credit">
                          Photo via Youtube </p>
                  </div>
                  <div class="image-placeholder"></div>
                  <p  v-editable v-bind:active="activeEdit" key="article.summary"  class="entry-summary">
                      {{ article.summary }} </p>
                  <div class="vmp-ad display-none" data-ref="content_small" id="content_small-APilhjkludmFxT-1459914179734-5" style="display: none;"></div>
              </section>
              <div class="rich-text">
                  <p> Donald Trump and I have something in common: We both have meaty, fleshy palms. How do I know this? We've both had our hands read by a prominent New York psychic named <a href="http://www.fahrusha.com/index.html">Fahrusha</a><b>. </b>According to Fahrusha and her booking company, Shelley Carroll Entertainment, which was known as the Magic Agency at the time, she read Trump's hand in the late 1990s. (The Trump Organization did not return Broadly's request for comment)<b> </b></p>
                  <p class="read-more">Read More: <a href="https://broadly.vice.com/en_us/article/the-women-who-love-donald-trump" target="_blank">The Women Who Love Trump</a>
                      <br>
                  </p>
                  <p>When I set up a meeting with Fahrusha a few years back, Donald Trump had neither announced his intention to run for president nor said all of the horrifying shit he's said over the past year. Back then, to me at least, he was just some guy who owned buildings and starred in reality TV shows that I would never watch. When Fahrusha gripped my palm and told me that it was kind of chubby—just like Trump's—I made a mental note to cut back on the Pad Thai.</p>
                  <p>Eager to know more about Trump's mitts, I gave the psychic a call for a first-hand account.</p>
                  <p><b>BROADLY: Where did you read Donald Trump's hand?</b>
                      <br><b>Fahrusha: </b>It was a private dinner in the wine cellar, which was also called the Cigar Room, of a popular New York bar and eatery on the East Side near the UN. I can't remember the name of it. There were more than 12, less than 20 men—all, at the time, over 50 years old, all millionaires, tycoons from New York real estate. Ian Schrager was there, the fellow who once owned Studio 54.</p>
                  <p><b>Were you the only palm reader there? </b>
                      <br>I was with two other women: one of whom was doing Tarot cards, the other of whom was doing possibly face reading. I don't recall, but I was the only one doing palms. We were hired to work in the room.</p>
                  <p class="has-image"><img src="//broadly-images.vice.com/images/2016/04/03/the-palm-reader-who-claims-she-read-donald-trumps-hand-body-image-1459715165.jpg?output-quality=70" data-original-width="900px" data-original-height="600px" style=""></p>
                  <p class="photo-credit">Photo via <a href="https://www.flickr.com/photos/gageskidmore/8567826396" target="_blank">Flickr user Gage Skidmore</a></p>
                  <p><b>How did you end up reading Trump's hand? </b>
                      <br>I pretty much read everyone's palm there. Now, I don't remember everybody's palm, but I do remember a few things about Trump's palm that I could say. Unlike what the media has said, he does not have particularly small hands at all. At the time, I believe he was heavier than he is today. I think that running around, doing campaigning and so forth, has whittled his waist a little bit—or maybe he already was a little thinner.</p>
                  <p>His hand was not tiny by any means. It seemed proportionate to his height. His hand was large —the palm part, as opposed to the fingers, which may have been a bit short for the palm. The fingers were a little shorter than the average palm of that size. The palm part was large and red—very puffy, very pink, red. That would indicate to me that he indulged in physical excesses. Now, what those excesses were, I could not tell you. The large, puffy palms could indicate excess food, drink, drugs, sex, exercise, overworking—any of those things. And gambling would be in there, too; however, there's no way to tell just from a red palm or a puffy palm which of these excesses the person is engaged in. The fact that it was pink, almost red, could indicate that he had high blood pressure. It could indicate that he had had a few drinks—and he probably had, because it was a dinner with alcohol there. But he was not in any way drunk.</p>
                  <p>But the fact that his fingers were a little shorter than average for the size of the palm would only mean that he would put self-interest first before the interest of others.</p>
                  <blockquote>His hand was not tiny by any means. It seemed proportionate to his height.
                      <br>
                  </blockquote>
                  <p><b>Do you remember the lines on his palms? </b>
                      <br>I think the lines were fairly normal, which is to say that there was a clear life line, head line, heart line. I don't recall any vast abnormalities about the lines on his palm.</p>
                  <p><b>Did anything indict he would become president?</b>
                      <br>No, no, no. Nothing to indicate that. I doubt that he will be, but you never know.</p>
                  <p><b>Do you remember if he said anything to you?</b>
                      <br>These gentlemen, as a group, did not acknowledge us as being there most of the time.</p>
                  <p></p>
                  <p><b>What was the vibe like in the room?</b>
                      <br>It felt like an old boys' club. They were older than I was. I may have been the youngest person in the room. I'm no spring chicken, but I know that Trump was older than me. They all knew each other. They were all chums with one another. I will say that they spoke freely in front of us as though we weren't there. As for what they said, I can't go there.</p>
                  <p><b>If you could read any politician or candidate's palm, whose would you read?</b>
                      <br>That's a good question. If I could say one thing, our current president has quite long fingers—as opposed to having short fingers, which indicates high ideals. In particular, he has long pinky fingers, which indicates that he is very good at being a public figure.</p>
                  <p>As far as the candidates now, I don't know. It might be interesting to read Ted Cruz's palm, although I wouldn't want to touch him. If I could look at Ted Cruz's palm without going near him, I might consider that.</p>
              </div>
              <div class="topics-container">
                  <h5 class="heading">Topics</h5>
                  <div class="topics-list">
                    <span v-for="topic in article.topics"><a href="//broadly.vice.com/en_us/topic/politics">{{ topic }}</a></span>
                  </div>
              </div>
              <div class="previous-next">
                  <div class="previous">
                      <article class="list-item" id="2132">
                          <a href="/en_us/article/what-to-expect-from-justin-bieber-now-that-he-has-dreadlocks">
                              <span class="heading">Previous</span>
                              <div class="image-container">
                                  <div class="vmp-srcN-container parsed fade-in hires-loaded lowres-loaded loaded"><img class="srcN fade-in parsed hires" data-sources="//broadly-images.vice.com/images/articles/meta/2016/04/05/untitled-article-1459831373.png?crop=1xw:0.579476861167002xh;0xw,0xh 400px,//broadly-images.vice.com/images/articles/meta/2016/04/05/untitled-article-1459831373.png?crop=1xw:0.579476861167002xh;0xw,0xh 800px" data-breakpoints="100% 400px,100% 800px" data-hires-compression="70" data-lowres-compression="10" src="//broadly-images.vice.com/images/articles/meta/2016/04/05/untitled-article-1459831373.png?crop=1xw:0.579476861167002xh;0xw,0xh&amp;output-format=jpeg&amp;output-quality=70" alt="What to Expect From Justin Bieber Now That He Has Dreadlocks"><img class="lowres" src="//broadly-images.vice.com/images/articles/meta/2016/04/05/untitled-article-1459831373.png?crop=1xw:0.579476861167002xh;0xw,0xh&amp;output-format=jpeg&amp;output-quality=10"></div>
                                  <noscript>&lt;img class="srcN fade-in lazy" src="//broadly-images.vice.com/images/articles/meta/2016/04/05/untitled-article-1459831373.png?crop=1xw:0.579476861167002xh;0xw,0xh" alt="What to Expect From Justin Bieber Now That He Has Dreadlocks" /&gt;</noscript>
                              </div>
                              <div class="information-container">
                                  <h3>What to Expect From Justin Bieber Now That He Has Dreadlocks</h3>
                              </div>
                          </a>
                      </article>
                  </div>
                  <div class="next">
                      <article class="list-item" id="2142">
                          <a href="/en_us/article/man-pleads-guilty-to-brutal-killing-of-21-year-old-trans-woman">
                              <span class="heading">Next</span>
                              <div class="image-container">
                                  <div class="vmp-srcN-container parsed fade-in hires-loaded lowres-loaded loaded"><img class="srcN fade-in parsed hires" data-sources="//broadly-images.vice.com/images/articles/meta/2016/04/05/man-pleads-guilty-to-brutal-killing-of-21-year-old-trans-woman-1459878497.jpg?crop=1xw:0.75xh;center,top 400px,//broadly-images.vice.com/images/articles/meta/2016/04/05/man-pleads-guilty-to-brutal-killing-of-21-year-old-trans-woman-1459878497.jpg?crop=1xw:0.75xh;center,top 800px" data-breakpoints="100% 400px,100% 800px" data-hires-compression="70" data-lowres-compression="10" src="//broadly-images.vice.com/images/articles/meta/2016/04/05/man-pleads-guilty-to-brutal-killing-of-21-year-old-trans-woman-1459878497.jpg?crop=1xw:0.75xh;center,top&amp;output-format=jpeg&amp;output-quality=70" alt="Man Pleads Guilty to Brutal Killing of 21-Year-Old Trans Woman"><img class="lowres" src="//broadly-images.vice.com/images/articles/meta/2016/04/05/man-pleads-guilty-to-brutal-killing-of-21-year-old-trans-woman-1459878497.jpg?crop=1xw:0.75xh;center,top&amp;output-format=jpeg&amp;output-quality=10"></div>
                                  <noscript>&lt;img class="srcN fade-in lazy" src="//broadly-images.vice.com/images/articles/meta/2016/04/05/man-pleads-guilty-to-brutal-killing-of-21-year-old-trans-woman-1459878497.jpg?crop=1xw:0.75xh;center,top" alt="Man Pleads Guilty to Brutal Killing of 21-Year-Old Trans Woman" /&gt;</noscript>
                              </div>
                              <div class="information-container">
                                  <h3>Man Pleads Guilty to Brutal Killing of 21-Year-Old Trans Woman</h3>
                              </div>
                          </a>
                      </article>
                  </div>
              </div>
          </div>
          </section>
          </section>
      </div>
  </div>

</template>

<script>
const articleData = {
  topics: ['Politics', 'Fortune Telling', 'Donald Trump', 'Palm Readers', 'Fortune', 'Election 2016'],
  summary: 'She says Trump\'s hand was red and puffy, showing no signs of him becoming president.',
  title: 'A Palm Reader Who Claims She Read Donald Trump\'s Hand Tells All',
  date: new Date(),
  time: '1:00 PM',
  byline: { name: 'Brenna Ehrlich', slug: 'brenna-ehrlich' }
};
export default {
  directives: {
    editable: {
      params: ['active', 'key', 'edit-method'],
      paramWatchers: {
        active: function (value) {
          console.log(value, this.params);
          if(this.params.editMethod) {
            console.log('running edit method');
            this.params.editMethod();
          } else {
            console.log('make editable: ', value);
            this.el.contentEditable = (value && value.activeEdit === value.key) ? true : false;
          }
        }
      },
      bind: function(value) {
        this.el.classList.add('editable');
        this.el.addEventListener('click', (evt) => {
          evt.preventDefault();
          console.log(`click: ${this.params.key}`);
          this.el.focus();
          this.vm.setEditable(this.params.key);
          this.el.addEventListener('blur', (evt) => {
            console.log(`blur: ${this.params.key}`);
            this.vm.setEditable(null);
          })
        });
      },
      unbind: function() {
        this.vm.setEditable(this.params.key);
      }
    }
  },
  data () {
    return {
      // note: changing this line won't causes changes
      // with hot-reload because the reloaded component
      // preserves its current state and we are modifying
      // its initial state.
      msg: 'Hello Vue!',
      article: articleData,
      activeEdit: null
    }
  },
  methods: {
    registerEditable(data) {
      console.log(data);
    },
    removeEditable(key) {
      console.log(`setting ${key} to uneditable`);
      this.activeEdit = null;
    },
    setEditable(key) {
      // if(this.activeEdit === key) {
      //   this.removeEditable(key);
      // } else {
        console.log(`setting ${key} to editable`);
        this.activeEdit = key;
      // }
    },
    topicSelection(isPrimary) {
      console.log(this.article.topics);
    }
  }
}
</script>

<style>
body {
  font-family: Helvetica, sans-serif;
}

.editable:hover {
  cursor: pointer;
  outline: 1px solid black;
}
</style>
