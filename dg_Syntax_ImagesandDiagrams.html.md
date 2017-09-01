# Images and diagrams

As someone once said, a picture is worth a thousand words. That is true in YaaS documentation as well. Whenever possible, use a diagram, image, or screenshot to convey a lot of information visually. Follow these guidelines when placing a diagram, screenshot, or other image in your content. For information on using the HTML or MD syntax itself, see the <a href="/tools/documentationsdk/index.html#About">Syntax</a> section of the Documentation SDK.

## Images and screenshots
Images and screenshots can quickly convey a lot of important information in your documentation. Do not use directional indicators, such as "above" and "below" to refer to images. Instead, include a brief introduction before each image that describes the purpose of the image and any necessary details. Do not overuse images such as including multiple screenshots of the same screen. Either condense them into one screenshot, or crop the images to show different areas. Follow the rest of these guidelines to make or use images, or capture screenshots:
 <ul>
   <li>Make or capture your images using any tool that outputs high quality images, such as **Snagit**. The desired image format is SVG (vector), but PNG and JPG (raster) are acceptable.</li>
   <li>Use an online tool such as <a href="https://tinypng.com/">TinyPNG</a> to compress images and limit the size of each image to 1MB, or smaller.
   <li>By default, displayed images are sized automatically. If you want to control the size of the image relative to the screen size, use one of these standard percentages: 100%, 75%, 50%, or 25%.</li>
   <li>Most images are left-aligned, unless it is a special case, such as images in a table.</li>
   <li>Do not include the mouse pointer in your screenshots, unless it shows a function related to the content.</li>
   <li>To highlight certain areas of an image, crop the image, or use <strong><font color="#8A5FF6">purple</font></strong> (#8A5FF6) for arrows or boxes around elements with a five point line width.</li>
   <li>The style sheets add a <strong><font color="#88929E">gray</font></strong> (#88929E) border with padding around your images by default.</li>
   <li>For multiple screenshots, use your best judgment as to whether you include one introduction, or whether you introduce each screenshot separately.</li>
   <li>Describe multiple areas using <strong><font color="#8A5FF6">purple</font></strong> round stamps with white numbers. In Snagit, you can create a number in this style and add it to the quick styles menu:
<div class="row">
    <div class="col-sm-4">
    <img src="img/snagit_win.png" class="img-click-modal" alt="Snagit Editor"></div>
    <div class="col-sm-3">
    <img src="img/snagit_mac.png" class="img-click-modal" alt="Snagit Editor Styles Menu"></div>
  </div>
   </li>
   <li>With a clickable image, include a caption or figure title, which appears at the top of the image in the pop-up window.</li>
   <li>Do not use figure captions unless it is a clickable image. Instead, introduce the image with a sentence, similar to this example:<br/><br/>
   See this example for the screenshot highlight, border, color, and clickable image guidelines:
   <br>
     <img style="width:50%" src="img/images_example.png" class="img-click-modal" alt="YaaS Market Persistence package"></li>
 </ul>

 ## Diagrams
 Diagrams are a good way to show information flows or a configuration of a product's architecture. Use the Diagram editor as described in the <a href="/tools/documentationsdk/index.html#Diagrams">Diagrams</a> section of the Documentation SDK.

For information about the UI design guidelines, see the <a href="https://techne.yaas.io/index.html">techné</a> website.
