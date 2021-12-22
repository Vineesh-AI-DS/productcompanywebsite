# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```
### Home coding:
<!DOCTYPE html>
<html lang="en">
  <head>
      Animix Private Limited
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Animix Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="https://www.fortressofsolitude.co.za/wp-content/uploads/2019/05/The-15-Most-Powerful-Anime-Characters-Of-All-Time-scaled.jpg" alt="The 15 Most Powerful &amp;amp; Strongest Anime Characters Of All Time" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 300px; height: 300px; margin: 0px padding right: 40px;">
          <div class="contenttext">
            Wide Range of products of anime DVD & Blu-ray including subtitles and audio in many languages,CD with music,dreama,radio,seiyu/voice artist and vocaloid.
            <br />
            Action-packed adventures,offbeat comedies,inspirational stories -- these anime movies and TV shows have a style and spirit unlike anything else.
            <ul>
              <li>All seasons available at affordable price</li>
              <li>Available in multiple languages</li>
              <li>Anywhere, anytime and secure access</li>
              <li>Safe and Secure online payment</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Animix Private Limited, Developed by Vineesh.M.
      </div>
    </div>
  </body>
</html>
```
```
### Products coding:
<!DOCTYPE html>
<html lang="en">
  <head>
       Animix Private Limited
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Animix Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1> Our Best Selling Anime DVD'S</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                    <img src="https://m.media-amazon.com/images/M/MV5BZmQ5NGFiNWEtMmMyMC00MDdiLTg4YjktOGY5Yzc2MDUxMTE1XkEyXkFqcGdeQXVyNTA4NzY1MzY@._V1_.jpg" alt="Naruto (TV Series 2002–2007) - IMDb" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px; padding-right: 40px;">
                  </div>
                  <div class="itemname">Naruto</div>
                  <div class="itemprice">Price: Rs.3,500</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                    <img src="https://cdn.myanimelist.net/images/anime/5/17407.jpg" alt="Naruto: Shippuuden (Naruto: Shippuden) - MyAnimeList.net" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px; padding-right: 40px;">
                  </div>
                  <div class="itemname">Naruto Shippuden</div>
                  <div class="itemprice">Price: Rs.4,000 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                  <img src="https://cdn.myanimelist.net/images/anime/3/40451.jpg" alt="Bleach - MyAnimeList.net" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px; padding-right: 40px;">
                </div>
                <div class="itemname">Bleach</div>
                <div class="itemprice">Price: Rs.2,500 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
                <img src="https://flxt.tmsimg.com/assets/p10701949_b_v9_ah.jpg" alt="Attack on Titan - Rotten Tomatoes" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px; padding-right: 40px;">
              </div>
              <div class="itemname">Attack on Titan</div>
              <div class="itemprice">Price: Rs.3,725 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
              <img src="https://static.wikia.nocookie.net/naruto/images/c/cd/Boruto_The_Movie_Novel.png/revision/latest?cb=20200802205920" alt="Boruto: Naruto the Movie | Narutopedia | Fandom" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px; padding-right: 40px;">
            </div>
            <div class="itemname">Boruto</div>
            <div class="itemprice">Price: Rs.3,000 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
            <img src="https://m.media-amazon.com/images/M/MV5BODI2NjdlYWItMTE1ZC00YzI2LTlhZGQtNzE3NzA4MWM0ODYzXkEyXkFqcGdeQXVyNjU1OTg4OTM@._V1_.jpg" alt="Demon Slayer: Kimetsu no Yaiba (TV Series 2019– ) - IMDb" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px; padding-right: 40px;">
          </div>
          <div class="itemname">Demon Slayer</div>
          <div class="itemprice">Price: Rs.3,415</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
          <img src="https://hbomax-images.warnermediacdn.com/images/GX8fnVgocBIZDKQEAAABF/tileburnedin?size=1280x720&amp;partner=hbomaxcom&amp;v=c00e18d02aac341c25377d81519ada13&amp;host=artist.api.cdn.hbo.com&amp;w=1280" alt="Watch JUJUTSU KAISEN - Stream TV Shows | HBO Max" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px; padding-right: 40px;">
        </div>
        <div class="itemname">Jujutsu Kaisen</div>
        <div class="itemprice">Price: Rs.2,700</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
             <img src="https://static.wikia.nocookie.net/deathnote/images/7/76/DEATH_NOTE_anime.jpg/revision/latest/top-crop/width/360/height/450?cb=20170720215429" alt="Death Note (anime) | Death Note Wiki | Fandom" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px; padding-right: 40px;">
              </div>
              <div class="itemname">Death Note</div>
              <div class="itemprice">Price: Rs.4,300 </div>
          </div>      
          <div class="productitem"> 
            <div class="itemimage">
              <img src="https://preview.redd.it/3liu4qpe0d171.png?auto=webp&amp;s=bf3bd000e03ae5c5ac568cc743c6608cf8a145d1" alt="Colored version of One Piece Volume 100 cover : r/OnePiece" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px; padding-right: 40px;">
            </div>
            <div class="itemname">One Peice</div>
            <div class="itemprice">Price: Rs.5,000 </div>
            </div>  
            <div class="productitem"> 
              <div class="itemimage">
                <img src="https://m.media-amazon.com/images/M/MV5BMTNmZDE2NDEtNTg3MS00OTE1LThlZGUtOGZkZTg0NTUyNGVmXkEyXkFqcGdeQXVyNTgyNTA4MjM@._V1_FMjpg_UX1000_.jpg" alt="One Punch Man (TV Series 2015–2019) - IMDb" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px; padding-right: 40px;">
              </div>
              <div class="itemname">One Punch Man</div>
              <div class="itemprice">Price: Rs.2,300 </div>
              </div>
           <div class="productitem"> 
           <div class="itemimage">
                  <img src="https://m.media-amazon.com/images/I/615UoMEsDEL._AC_SL1000_.jpg" alt="Amazon.com: POSTER STOP ONLINE Tokyo Ghoul - Manga/Anime TV Show  Poster/Print (Ken Kaneki) (Size 24&amp;quot; x 36&amp;quot;): Posters &amp;amp; Prints" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px; padding-right: 40px;">
                </div>
               <div class="itemname">Tokyo Ghoul</div>
               <div class="itemprice">Price: Rs.1,590 </div>
                </div>
                <div class="productitem"> 
                  <div class="itemimage">
                    <img src="https://m.media-amazon.com/images/I/81eJlNQ1UCL._SL1500_.jpg" alt="Amazon.com: Pokemon: Let&amp;#39;s Go, Pikachu! : Nintendo of America: Video Games" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px; padding-right: 40px;">
                  </div>
                  <div class="itemname">Pokemon</div>
           <div class="itemprice">Price: Rs.2,500    
                  </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Animix Private Limited, Developed by Vineesh.M.
      </div>
    </div>
  </body>
</html>
```
```
### People coding:
<!DOCTYPE html>
<html>
    <head>
          Animix Private Limited.
        <link rel="stylesheet" href="./css/layout.css" />       
         <link rel="icon" href="./img/icon.png" type="image/x-icon" />
    </head>
    <body>
            <div class="banner">Animix Private Limited </div> 
            <div class="menu">
                <div class="menuitem"><a href="./home.html">Home</a></div>
                <div class="menuitem"><a href="./products.html">Products</a></div>
                <div class="menuitemselected"><a href="./people.html">People</a></div>
                <div class="menuitem"><a href="./contacts.html">Contact Us</a>
                </div>
             </div>
         </div>
         <div class="content">
            <div class="productcontent">    
                <h1><b><u>Our Crew:</u><b></h1>
                <div class="productitems">
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="https://www.newschoolfreepress.com/wp-content/uploads/2013/10/derek-padula-author.jpg" alt="Dragon Ball Z and Buddhism: Connecting Two Cultures with One Book - The New  School Free Press" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px; padding-right:40px;">
                        </div>
                        <div class="itemname">CEO</div>
                        <div class="itemprice">Mr.Ichigo </div>
                    </div>
                    <div class="productitem"> 
                        <div class="itemimage">
                          <img src="https://static.wikia.nocookie.net/naruto/images/a/a3/Masashi_Kishimoto_2014.png/revision/latest?cb=20141111205854" alt="Masashi Kishimoto | Narutopedia | Fandom" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px; padding-right: 40px;">
                        </div>
                        <div class="itemname">Product Manager</div>
                        <div class="itemprice">Mr.Kishimoto </div>
                    </div>
                    <div class="productitem"> 
                        <div class="itemimage">
                          <img src="https://static.wikia.nocookie.net/bleach/images/1/1e/Tite_Kubo.png/revision/latest?cb=20180110000716&amp;path-prefix=en" alt="Tite Kubo | Bleach Wiki | Fandom" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px; padding-right: 40px;">
                        </div>
                        <div class="itemname">VP of Marketing</div>
                        <div class="itemprice">Mr.Tite Kubo</div>
                    </div>
                    <div class="productitem"> 
                        <div class="itemimage">
                            <img src="https://cdn.myanimelist.net/images/voiceactors/2/10593.jpg" alt="Eiichiro Oda - MyAnimeList.net" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px; padding-right: 40px;">
                        </div>
                        <div class="itemname">Project Manager</div>
                        <div class="itemprice">Mr.Eiichiro Oda </div>
                    </div>
                    <div class="productitem"> 
                        <div class="itemimage">
                            <img src="https://biographyhost.com/uploads/images/HAJIME-ISAYAMA--IMG.jpg" alt="Hajime Isayama - &amp;#39;Attack On Titans,&amp;#39; Book &amp;amp; Art - Biography" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px;padding-right: 40px;">
                        </div>
                        <div class="itemname">Technical Lead</div>
                        <div class="itemprice">Mr. Hajime Isayama</div>
                    </div>
                    <div class="productitem"> 
                        <div class="itemimage">
                            <img src="https://m.media-amazon.com/images/M/MV5BMDE5MTI3YTMtNWFmMC00NjhmLWFmZjQtODExMjNkMmEzOGRhXkEyXkFqcGdeQXVyNDQxNjcxNQ@@._V1_.jpg" alt="Akira Toriyama - IMDb" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 150px; height: 150px; margin: 0px; padding-right: 40px;"> 
                        </div>
                        <div class="itemname">Senior Engineer</div>
                        <div class="itemprice">Mr. Kakashi Hatake </div>
                </div>        
            </div>
        <div class="footer">
            Copyright &#169; 2021 Animix private limited,Developed by Vineesh.M.
          </div>
        </div>
      </body>
    </html>
    </body>  
</html>
```
```
### Contact coding: 
<!DOCTYPE html>
<html lang="en">
  <head>
       Animix Private Limited
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Animix Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/People.html">Contact Us</a></div>
        <div class="menuitem"><a>People</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>People</h1>
          <img src="https://www.fortressofsolitude.co.za/wp-content/uploads/2019/05/The-15-Most-Powerful-Anime-Characters-Of-All-Time-scaled.jpg" alt="The 15 Most Powerful &amp;amp; Strongest Anime Characters Of All Time" jsname="HiaYvf" jsaction="load:XAeZkd;" class="n3VNCb" data-noaft="1" style="width: 400px; height: 400px; margin: 0px padding left: 60px;">
          <div class="contenttext">
            For further questions and queries pls contact the following personelles
            <br> 
            <ul>
              <li>Vineesh.M Phone no:76564519 Email:vineesh@gmail.com</li>
              <br>
              <li>Aadheeshwar Phone no:91557634 Email:aadheeshwar@gmail.com</li>
              <br>
              <li>Shyam Santino Phone no:91500043 Email:shyam@gmail.com</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Animix Private Limited, Developed by Vineesh M.
      </div>
    </div>
  </body>
</html>
```
## OUTPUT:
### Home:
![Screenshot 2021-12-22 212703](https://user-images.githubusercontent.com/93427254/147140518-ef0310d0-388a-4be5-a342-fc54c451a84c.png)
### Products:
![Screenshot 2021-12-22 212905](https://user-images.githubusercontent.com/93427254/147140578-391d0e79-b3fe-4621-959a-25eec7139c46.png)
### People:
![Screenshot 2021-12-22 212812](https://user-images.githubusercontent.com/93427254/147140646-d62a09c9-4d2e-45f4-ab2e-c15a77bd667e.png)
### Contact:
![Screenshot 2021-12-22 213039](https://user-images.githubusercontent.com/93427254/147140742-7f828ae9-3511-41b5-a6fa-0c47a1239d59.png)

