# NFT-PREVIEW-CARD-COMPONENT-CHALLENGE

<p> I had built everything needed for my HTML structure to build the nft card except the small line break design in grey. I haven't created one of these before so I ended up watching a tutorial ' How To Draw a Line With CSS (Horizontal or Vertical)' (see links) on youtube to see how to achieve this. </p>


**html**

<span class="line>      <--- this is me creating a link in my html to style it 

**CSS**

.line {
<br>
Border-bottom: 2px solid #ccc
<br>
Display:block;
}

**

  <p> I learned that setting the .line to <em> **display;block;* </em> meant that it would take up the <em> width </em> of its parent element which in this case is the <em> fieldset</em>. I applied these code my HTML foundation was complete. I was happy to then move onto the css. </p>
             
     <img width="956" alt="screenshothtmldone" src="https://user-images.githubusercontent.com/92884422/143897949-2b257322-0042-45cf-91f4-d0a21a346465.png">
     
     

<p>I wanted to focus on getting the colours correct and the shadowing and then move onto the display and then the font sizes and styles

I realised I could also use Adobe Photoshop to use the Eyedropper tool the exact colour from the design example.
                                                                                                                                                
 <p> I found this a helpful and quick way to get the exact colour of images so I can be completely precise when making my projects. This is a feature I will most definatley use in the making of future projects </p> 
                                                                                                                                                
                                                                                                                                                
<p> Another problem I faced was when I reduce the browser width, the card wasnt scaling or moving from its position. I watched a video on youtube and they mentioned wrapping the content in a div/container so I went ahead and did so.</p>

<p> From trying to set the right From trying to use media queries,  I noticed that using <em> **fieldset>** </em> in the html was not working  in my favour. Instead, I created a <em> container </em>, gave it height, width and a background of the specified colour, as well as borders and then set the <em> containers </em> display to flex along with justify content center and align items center. </p>
  
![image](https://user-images.githubusercontent.com/92884422/143900940-1922daa7-f0b1-460c-8a63-f2c1535e6474.png)







        


