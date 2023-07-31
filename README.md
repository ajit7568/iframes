# iframes
<!-- hosted link -->
https://ajit7568.github.io/iframes/
<!-- local file-->
<!DOCTYPE html>
 <html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>local file</title>
 </head>
 <body>
    <h3>Welcome to Geekster</h3>
    <p>This content is displayed from a local HTML file using an iframe.</p>
    <p>Similarly you can craete different sizes of windows using iframes in HTML</p>
 </body>
 </html>
 <!-- main index.html file -->
 <!DOCTYPE html>
<html lang="en">
<head>
    <!-- Meta tags for character encoding and viewport -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Title of the webpage -->
    <title>iframes</title>
</head>
<body>
    <!-- Main heading of the webpage -->
    <h1>HTML Project with iframes</h1>

    <!-- Container for displaying a local HTML file using iframe -->
  <div class="iframe-container">
        <!-- Heading for local content -->
  <h2>Local Content</h2>
        <!-- Embedding a local HTML file using the iframe -->
        <iframe src="localfile.html" frameborder="0"></iframe>
    </div>

    <!-- Container for displaying an external website using iframe -->
 <div class="iframe-container">
        <!-- Heading for external website -->
  <h2>External Website</h2>
        <!-- Embedding an external website using the iframe -->
  <iframe width="560" height="315" src="https://www.geekster.in/"></iframe>
    </div>

    <!-- Container for displaying a YouTube video using iframe -->
   <div class="iframe-container">
        <!-- Heading for YouTube video -->
  <h2>YouTube Video</h2>
        <!-- Embedding a YouTube video using the iframe -->
 <iframe width="560" height="315" src="https://www.youtube.com/embed/H335Vdkmdhk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </div>
</body>
</html>
<!--The first container demonstrates embedding a local HTML file using the <iframe> tag. The src attribute of the iframe is set to "localfile.html", which loads the content from the localfile.html in the same directory.
The second container demonstrates embedding an external website using the <iframe> tag. The src attribute is set to "https://www.geekster.in/", which loads the content from the Geekster website.
The third container demonstrates embedding a YouTube video using the <iframe> tag. The src attribute is set to the YouTube video URL, and additional attributes like title, frameborder, allow, and allowfullscreen are used to control the behavior and appearance of the embedded video. -->




