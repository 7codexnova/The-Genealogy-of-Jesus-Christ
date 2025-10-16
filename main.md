<!DOCTYPE html>
<html lang="nl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Matthew 1 & 2 - The Birth and Early Life of Jesus</title>
  <style>
    body {
      font-family: Georgia, serif;
      line-height: 1.6;
      /* padding-top to account for the fixed navbar */
      padding-top: 5rem;
      padding-left: 5rem;
      padding-right: 5rem;
      max-width: 1000px;
      margin: auto;
      background-color: #fdfdfd;
      color: #333;
    }

    /* Styling for the navigation bar */
    .navbar {
      background-color: #ffc8f2;
      overflow: hidden;
      position: fixed;
      top: 0;
      width: 100%;
      left: 0;
      z-index: 1000;
      display: flex;
      justify-content: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }

    .navbar a {
      color: #fdfdfd;
      text-align: center;
      padding: 1rem 2rem;
      text-decoration: none;
      font-size: 1.2rem;
      font-weight: bold;
      transition: background-color 0.3s ease;
    }

    .navbar a:hover {
      background-color: #edbbf5;
      color: #2c3e50;
    }
    
    .container { 
      display: flex;
      height:auto;
    }
    .side{
      flex: 1;
      background-color:#fdfdfd ;
      gap: 1rem;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
    .side img{
      max-width: 100%;
      height: auto;
    }
    .center {
      flex: 2;
      background-color: #fdfdfd;
      padding: 20px;
      text-align: left;
    }
    h1, h2 {
      color: #2c3e50;
    }
    h1 {
      border-bottom: 2px solid #ccc;
      padding-bottom: 0.5rem;
    }
    .verses {
      cursor: pointer;
      border-bottom: #edbbf5;
      padding-bottom: 4px;
      color: #333;
    }
    .verses:hover {
      text-decoration: none;
      border-bottom: 3px dotted #f475e9;
    }
    .section-title {
      font-weight: bold;
      font-size: 1.2rem;
      margin-top: 2rem;
    }
    .comment-box {
      display: none;
      margin: 0.5rem 0 1rem 1rem;
      padding: 0.5rem;
      background-color: #fdeefe;
      border: 1px solid #ddd;
      border-radius: 4px;
    }
    .comment-label {
      font-weight: bold;
      margin-bottom: 0.25rem;
    }
    textarea {
      width: 100%;
      height: 60px;
      padding: 0.5rem;
      font-family: inherit;
    }
  </style>
</head>
<body>

  <div class="navbar">
    <a href="#">Bijbel</a>
    <a href="preek.html">Preek</a>
    <a href="#">Studie/Onderzoek</a>
    <a href="#">PDF/Bron</a>
  </div>

  <div class="container">
    <div class="side">
      <img src="photos/3.jpg" alt="Foto links">
      <img src="photos/1.jpeg" alt="Foto links">
      <img src="photos/4.jpg" alt="Foto links">
    </div>

    <div class="center">
      <h1>Matthew 1</h1>
      <div class="section-title">The Genealogy of Jesus Christ</div>

      <span class="verses" onclick="toggleComment('c1')">
        (1)The book of the genealogy of Jesus Christ, the Son of David, the Son of Abraham:
      </span>
      <div id="c1" class="comment-box">
        <div class="comment-label">💬 Notes Verse 1:</div>
        1:1 Jesus means “O Lord, save,” referring to His role as Savior (v. 21). Christ means “Anointed One,” the <br>
        Messiah, the One who is filled with the Holy Spirit (see Jn 1:33). Though the Son alone became Man, God <br>
        the Father and the Holy Spirit work in Jesus Christ to save us. Jesus became Man as a Jew, from the <br>
        lineage of Abraham, the father of all Jews, and of David, Israel’s greatest king and the prototype of the <br>
        royal Messiah. This genealogy reveals that the Son of God so identifies with the human condition that He <br>
        takes it all on Himself and becomes part of it. Christ's ancestry includes both righteous and wicked <br>
        people, faithful kings and murderers, Jews and Gentiles, kings and peasants.
      </div>
      

      <span class="verses" onclick="toggleComment('c2')">(2)Abraham begot Isaac, Isaac begot Jacob, and Jacob begot Judah and his brothers.</span>
      <div id="c2" class="comment-box">
        <div class="comment-label">💬 Notes Verse 2:</div>
        While Luke’s genealogy runs from Jesus back to Adam (Lk 3:23-38), Matthew's list descends from <br>
        Abraham,with whom God established the Old Covenant of circumcision, to Jesus, the author of the New <br>
        Covenant. God promised to bless all the tribes of the earth in Abraham (Gn 12:3; 28:14); this <br>
        promise is fulfilled in Abraham’s greatest Son, Jesus Christ.
      </div>

      <div class="verses" onclick="toggleComment('c3')">(3)Judah begot Perez and Zerah by Tamar, Perez begot Hezron, and Hezron begot Ram.</div>
      <div id="c3" class="comment-box">
        <div class="comment-label">💬 Notes Verse 3:</div>
        1:3 Jewish genealogical lists normally included only men. The mention of women (Tamar, Rahab, Ruth, and <br>
        Bathsheba) is unusual. Each one was either a Gentile or a sinner. The inclusion of these women declares <br>
        God's graciousness and prefigures the calling of Gentiles into the Church. It also underscores the role of <br>
        women in God's plan of salvation and anticipates the special place of the Virgin Mary in that plan.</p>
      </div>

      <div class="verse"> (4)Ram begot Amminadab, Amminadab begot Nahshon, and Nahshon begot Salmon.</div>
      <div class="verse">(5)Salmon begot Boaz by Rahab, Boaz begot Obed by Ruth, Obed begot Jesse,</div>

      <div class="verses" onclick="toggleComment('c6')">(6)and Jesse begot David the king. David the king begot Solomon by her who had been the wife of Uriah.</div>
      <div id="c6" class="comment-box">
        <div class="comment-label">💬 Notes Verse 6:</div>
        1:6 Through anointing by Samuel, David was made king. Through his psalms, David was revealed as a great <br>
        prophet. Thus, David foreshadows both the royal and the prophetic nature of Jesus Christ (Ps 109). As an <br>
        adulterer and a murderer, David also functions as a type for all repentant sinners. </p>
      </div>

      <div class="verse">(7)Solomon begot Rehoboam, Rehoboam begot Abijah, and Abijah begot Asa.</div>
      <div class="verse">(8)Asa begot Jehoshaphat, Jehoshaphat begot Joram, and Joram begot Uzziah.</div>
      <div class="verse">(9)Uzziah begot Jotham, Jotham begot Ahaz, and Ahaz begot Hezekiah.</div>
      <div class="verse">(10)Hezekiah begot Manasseh, Manasseh begot Amon, and Amon begot Josiah.</div>
      <div class="verse">(11)Josiah begot Jeconiah and his brothers about the time they were carried away to Babylon.</div>
      <div class="verse">(12)And after they were brought to Babylon, Jeconiah begot Shealtiel, and Shealtiel begot Zerubbabel.</div>
      <div class="verse">(13)Zerubbabel begot Abiud, Abiud begot Eliakim, and Eliakim begot Azor.</div>
      <div class="verse">(14)Azor begot Zadok, Zadok begot Achim, and Achim begot Eliud.</div>
      <div class="verse">(15)Eliud begot Eleazar, Eleazar begot Matthan, and Matthan begot Jacob.</div>

      <div class="verses" onclick="toggleComment('c16')">(16)And Jacob begot Joseph the husband of Mary, of whom was born Jesus who is called Christ.</div>
      <div id="c16" class="comment-box">
        <div class="comment-label">💬 Notes Verse 16:</div>
        1:16 Joseph can be named as Jesus’ immediate predecessor since OT marriage laws confer hereditary rights <br>
        on adopted as well as biological sons. The church fathers teach, Mary also was descended from David; of <br>
        whom is feminine in Greek, referring only to Mary. Thus, Jesus is shown to be born of Mary, and not <br>
        begotten of Joseph. (See also note on Lk 3:23-38.)</p>
      </div>

      <div class="verses" onclick="toggleComment('c17')">(17)So all the generations from Abraham to David are fourteen generations, from David until the captivity in Babylon are fourteen generations, and from the captivity in Babylon until the Christ are fourteen generations.</div>
      <div id="c17" class="comment-box">
        <div class="comment-label">💬 Notes Verse 17:</div>
        1:17 Christ's ancestors are arranged in three groups of fourteen generations. Fourteen is the numerical <br>
        equivalent of the consonants in the name David, underlining Jesus’ descent from David. This a so shows the <br>
        division of the leadership of the Jews, being under judges until David, under kings unti Babylon, and under <br>
        priests until Christ. </p>
      </div>

      <div class="section-title">Christ Born of Mary</div>
      <div class="verse">(18)Now the birth of Jesus Christ was as follows: After His mother Mary was betrothed to Joseph, before they came together, she was found with child of the Holy Spirit.</div>

      <div class="verses" onclick="toggleComment('c19')">(19)Then Joseph her husband, being a just man, and not wanting to make her a public example, was minded to put her away secretly.</div>
      <div id="c19" class="comment-box">
        <div class="comment-label">💬 Notes Verse 19:</div>
        1:19 The righteousness of Joseph consisted of a mercy that transcends the Law (Hos 6:6). Joseph showed <br>
        this mercy by his unwillingness to expose Mary’s supposed sin, even though he was obliged by the Law <br>
        to do so. Her husband: The Bible calls engaged couples husband and wife before their marriage (Rachel <br>
        was called the wife of Jacob before marriage by virtue of their engagement in Gn 29:21; see also Dt <br>
        22:23, 24). Thus, Joseph is called the husband of Mary, and Mary is called his wife (vv. 20, 24). In <br>
        the Church, Joseph is remembered as the Betrothed, pointing out Mary's ever-virginity. (See also note <br>
        on Est 2:7.)</p>
      </div>

      <div class="verses" onclick="toggleComment('c20')">(20)But while he thought about these things, behold, an angel of the Lord appeared to him in a dream, saying, “Joseph, son of David, do not be afraid to take to you Mary your wife, for that which is conceived in her is of the Holy Spirit. </div>
      <div id="c20" class="comment-box">
        <div class="comment-label">💬 Notes Verse 20:</div>
        1:20 An angel (or "messenger") of the Lord dispels Joseph’s false reasoning by announcing the utterly <br>
        unreasonable: the pregnancy of the Virgin is by the Holy Spirit. Being born of a virgin proves Christ’s <br>
        divinity, only a revelation by God could serve as adequate evidence of this miracle. </p>
      </div>

      <div class="verse">(21)And she will bring forth a Son, and you shall call His name Jesus, for He will save His people from their sins.” </div>

      <div class="verses" onclick="toggleComment('c22')">(22)So all this was done that it might be fulfilled which was spoken by the Lord through the prophet, saying:</div>
      <div id="c22" class="comment-box">
        <div class="comment-label">💬 Notes Verse 22:</div>
        1:22 Matthew repeatedly uses the formula that it might be fulfilled which was spoken (see 2:15, 23; 4:14;<br>
        8:17; 12:17; 13:35; 21:4; 26:56; 27:35). This underscores the intervention of God throughout history, <br>
        demonstrates the continuity between the Old and New Covenants, and indicates the beginning of the new <br>
        creation. </p>
      </div>

      <div class="verses" onclick="toggleComment('c23')">(23)“Behold, the virgin shall be with child, and bear a Son, and they shall call His name Immanuel,” which is translated, “God with us.”</div>
      <div id="c23" class="comment-box">
        <div class="comment-label">💬 Notes Verse 23:</div>
        1:23 The conception of Jesus fulfills Is 7:14, where we are told that a virgin would conceive and bear a Son. <br>
        He who is conceived in Mary is not a new Person coming into existence but the eternal Son of God now using 
        her womb as His throne. Both the virginal conception by means of the Holy Spirit and the name immanuel, God 
        with us declare Christ's divinity. </p>
      </div>

      <div class="verse">(24)Then Joseph, being aroused from sleep, did as the angel of the Lord commanded him and took to him his wife,</div>

      <div class="verses" onclick="toggleComment('c25')">(25)and did not know her till she had brought forth her firstborn Son. And he called His name Jesus.</div>
      <div id="c25" class="comment-box">
        <div class="comment-label">💬 Notes Verse 25:</div>
        1:25 The use of the word till does not imply that Joseph had marital relations with Mary after the Savior's
        birth. In the Bible, this word (sometimes translated “to") is often used to express a situation that 
        actually continues after the event mentioned (see 28:20; Gn 8:7; Dt 34:6; 2Kg 6:23). The witness of the 
        entire Church throughout history is that Mary remained a virgin for life. Firstborn: See note on Lk 2:7.</p>
      </div>
    </div>
    <div class="side">
      <img src="photos/2.jpeg" alt="Foto rechts">
    </div>
  </div>

  <script>
    function toggleComment(id) {
      const el = document.getElementById(id);
      el.style.display = el.style.display === "none" || el.style.display === "" ? "block" : "none";
    }
  </script>

  <audio controls>
  <source src="audio/preek-4.8.mp4" type="audio/mpeg">
</audio>

</body>
</html>