 <!DOCTYPE html>
<html>
  <head>
    <title>ADMO Demo</title>
    <style>
	body {
  margin: 0;
  padding: 0;
  overflow: hidden; /* Prevent scrolling of the main page */
  background-color: black;
}

      /* CSS for top banner */
      .banner {
        background-color: red;
        color: white;
        font-size: 24px;
        font-weight: bold;
        text-align: center;
        padding: 10px 0;
      }
      
      /* CSS for left section */
      .left-section {
        float: left;
        width: 10%;
        height: 100%;
      }
      
	  .banner {
      background-color: red;
      color: white;
      font-size: 24px;
      font-weight: bold;
      text-align: center;
      padding: 10px;
    }
	
      /* CSS for iframe */
      iframe {
        float: left;
        width: 90%;
        height: 100%;
        border: none; /* optional - removes border around iframe */
      }
      
      /* CSS for html and body */
      html, body {
        height: 100%;
        margin: 0;
        padding: 0;
      }
    </style>
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-QX5F9S04SR"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-QX5F9S04SR');
</script>
  </head>
  <body>
    <div class="banner">
      ADMO Demo Site
    </div>
    <div class="left-section">
      
      <ul style="list-style: none; padding: 0; margin: 0;">
        <li><a href="data:image/jpeg;base64,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" target="myFrame">Article 1</a></li>
        <li><a href="https://whatson.ae/2023/04/the-ultimate-guide-to-iftars-in-abu-dhabi-during-ramadan-2023/" target="myFrame">Article 2</a></li>
        <li><a href="https://www.youtube.com/embed/IDWKzkUqunM" target="myFrame">Article 3</a></li>
      </ul>
    </div>
    <iframe name="myFrame" onload="setTitle()" src="https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcQTrThFwUdCLTW_qzag8SDltf4J2qOnvxN-iHUaMm5mMp9-90v7" </iframe>
    <script>
      function setTitle() {
        var iframe = document.getElementsByName("myFrame")[0];
        iframe.contentDocument.title = "ADMO Web Performance";
      }
    </script>
  </body>
</html>
