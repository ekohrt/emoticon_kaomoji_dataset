# Emoticon / Kaomoji Dataset (ﾉ◕ヮ◕)ﾉ*:・ﾟ✧
A dataset of 62,000 text emoticons and kaomojis with tags.
  
Emoticon dataset includes the original tags from the source of the emoticon, as well as new higher-quality tags manually labeled by me. Most sites that were scraped had section headers that are treated as tags, but sometimes emoticons had individual titles. Manually-labeled tags were constructed using a combination of the original tags, extensive regular expressions, and visual inspection. About 10,000 of the emoticons are missing the manual tags. Manual tags should not be considered comprehensive.
  
Also included is a notebook with code for searching emoticons by TF-IDF similarity, and a few examples from each tag.
  
### Scraping sources:  
- https://www.textemoticons.top/  
- https://www.messletters.com/en/emoticons/  
- https://kaomojis.org/  
- https://jref.com/articles/emoji.36/  
- https://www.emoticonstext.com/  
- https://en.wikipedia.org/wiki/List_of_emoticons  
- https://slangit.com/emoticons/kaomoji  
- https://wikileaks.org/ciav7p1/cms/page_17760284.html  
- http://www.emojicons.com/popular  
- https://www.fastemoji.com/  **  
- https://www.toolcalculator.com/japanese-smiley-face.html  

** fastemoji has extensive user-submitted search tags for each emoticon (several hundred total tags) but only the emoticon titles were used here. Visiting each emoticon to scrape its tags would too long for me, and most of the tags are redundant. But if those tags are useful to you then check it out.
  
### Manually-labeled Tags (95)
['angel', 'anger', 'annoyed', 'archery', 'asleep', 'basketball', 'bats_vampires', 'beach', 'bear', 'bird', 'birthday', 'blush', 'bomb', 'breasts', 'butt', 'butterfly', 'cat', 'cheerleader', 'chess', 'christmas', 'cigarette', 'clown', 'computers', 'crab', 'crying', 'dancing', 'dead', 'devil', 'dog', 'donger', 'drink', 'excited', 'fight', 'fish', 'flex', 'flower', 'food', 'football', 'frog', 'glasses', 'goodbye_message', 'gun', 'hamster', 'heart', 'hello_message', 'hug', 'kiss', 'koala', 'lenny', 'lying_down', 'middle finger', 'money', 'monkey', 'monocle', 'morning_night_evening_message', 'mouse', 'music', 'mustache', 'penis', 'pig', 'ping_pong', 'pointing', 'pokemon', 'proposal', 'rabbit', 'radio', 'rain', 'robot', 'rose', 'running', 'sad', 'salute_wave', 'seal', 'sheep', 'shrug', 'smiling', 'smirk', 'soccer', 'sparkles', 'spider', 'spinning', 'surprised', 'sweat', 'sword', 'syringe', 'table_flip', 'table_upright', 'thanks_message', 'thumbs_up', 'wall', 'wand', 'wink', 'writing', 'yummy', 'zombie']
