# notes #

## index.html ##

- I changed what was in the title tag to Horiseon Social Solution Services INC (so it isn’t just “website”)

- Made a <header> tag to replace the div that was there to add semantic value and give the header section some organization structure 

- Took the <span> tag out of the <h1> section and added an <em> tag to give the “seo” of the header an emphasis and flair 
  as well as replacing it with something semantic. 

- Made sure I added a <nav> within the <header> (section) because those list items are on a navigation toolbar giving It the proper semantic structure.

- Additionally within the <header> (section) I made sure that the <ul> and sub <li> didn’t have any unneeded indentation and scrunched those properly.

- Then I worked my way down replaced the unneeded <div> for the image icon that is present below the header and gave that 
  area space within the html. Because it is its own entity and section. Instead of <div> I wanted it to have semantic value and 
  replaced it with a <figure> tag. 

- So one thing that was very evident was that the html structure of the section below the image was ALL over the place. 
  I will explain the many things I changed semantically to give that organization but first off I wanted to give this area 
  a <main> tag because it is all of the informational info of the webpage. I made sure that everything from the “search engine optimization” 
  area to the benefit cost” was inside of this tag.

- So now, there are still <div>’s which is bad to give these elements some semantics I replaced those <divs> for the middle area with the 
  images (not icons) with an <article> tag because it is an informational element of the html that is within the middle of the page. 
  Secondly, for the other <section> with the icons and some more brand information I tagged these with an <aside> tag. 
  This element of the html is aside of the page. So semantically speaking someone going into this code for the first time 
  is going to be able to differentiate easier which is what and why the html is structured the way that it is. 
  
- To Revert, I within the first section where the <article> tag is I made sure there was the proper id addition for “search engine optimization” 
  so that when your in the navigation section if you clicked on it, it would then shortcut you properly to that area of the webpage. 

- Lastly, there wasn’t a <footer> tag where there should have been for the footer and there was an <h2> when there should’ve been an <h4> 
  for some differentiation within the header tags. 

- One thing that was important in the READ ME was the proper use of alt tags on the html for images. 
  I really only found this meaningful for the <article> section because it is the only image(s) that hold some value for the audience. 
  Alts are targeted for the audience that might not be able to see the webpages aesthetics from there vision impairment and 
  people that might not be able to get the webpage to load properly. But in that instance these images are the only ones in 
  my opinion that have value and knowledge about the brand the rest are essentially aesthetic placeholders for the webpage and for 
  someone in that point of view it really doesn’t need an alt tag. 

- I additionally replaced the ID’s with a more descriptive action as to what they are doing for the HTML (articlenavSEO…etc.)

- I created for personal preference a margin for the hero <figure> to align it with the <main> section. 
