<div align="center">
    <img src="https://cdn.discordapp.com/emojis/869468304346058782.gif?size=128&quality=lossless" />
    <p style="font-size: 20px"> how to use my code stuff :)</p>
</div>


### 💳 Cards:


---

#### Feature Card: 

    <FeatureCard array={['alt/img-name', 'scale%', 'src']} />

| Syntax | Usage |
|--------|------|
| alt    | text that shows if image is unable to load, i reccomend putting the image title here.|
| scale |  allows for easy scaling of images to make images align better, can be left BLANK.| 
|src | source of the image, self explanatory lol.|

---

#### ~~Team Card:~~ DEPRECATED i think? 


    <TeamCard cardArray={['name', 'role', 'img-src', 'github-link', 'linkedin-link', 'twitter-link', 'at-link']} />

| Syntax | Usage                                                  |
| ---- |--------------------------------------------------------|
| name | the username of the person                             |
| role | the role of the person. ie: Owner, Developer, ect...   |
| img-src | meant to be the head img of the player can be any link |
| [name]-link | DEPRECATED - we moved it to DB i think? |

---

### 🔘 Buttons:

---

#### Homepage Button:

    <HomepageButton array={['text', 'background-color', 'border-size', 'text-color']} />

| Syntax | Usage |
|---|---|
|text| text for the button|
|background-color| changes the color of the button, set to 'transparent' if you want it to be transparent|
|border-size| only use if background is transparent, leave blank otherwise.|
|text-color| changes color of button text|

---

#### ~~CardButtons:~~ DEPRECATED
was merged with team card and now only
houses button image links and styling.
likely to be deprecated in the near future!
