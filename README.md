<a href="https://www.juncture-digital.org"><img src="https://juncture-digital.github.io/juncture/static/images/ve-button.png"></a>

<param ve-config 
       title="Yerba Mate: From Sacred Drink to Caffeinated Star"
       source-image="https://upload.wikimedia.org/wikipedia/commons/b/bf/Timber_between_Larch_Mountain_and_Mount_Hood_%284587520152%29.jpg"
       banner="https://upload.wikimedia.org/wikipedia/commons/b/bf/Timber_between_Larch_Mountain_and_Mount_Hood_%284587520152%29.jpg"
       author="Hannah Hardenbergh"
       layout="vertical">

### Introduction
this is a test for how to write a visual essay. 

##### Images
add all code for images directly after a paragraph. it is recommended to download all images and place the file title into the URL parameter. though it's not working right now, you can click on the photo editor and shift-click and drag to a specific area in the image and provide a caption for the specified area of the image. 

Linking the text to an image: 
highlighting some words will take you to a part of the corresponding image when you move cursor to that word. place words in code: 
<span data-mouseover-image-zoomto="147,105,340,232">
       Show me the eagle. 
       </span>
After written code, the rest of the text will follow continuously. You will need the image code that corresponds to the zoom-in to follow the paragraph itself directly. here is that code: image is sourced from its wikimedia commons URL.
<param ve-image 
       label="*Shaman drum." 
       description="Photograph" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/7/78/Weeping_larch.jpg">

New paragraph, new image.
<param ve-image 
       label="*Hamatsa Emerging From The Woods*, 1914. Photo by E.S. Curtis." 
       description="Photograph" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/5/52/Hamatsa_shaman.jpg" region="468,765,612,418">

If you want to upload an image from your downloads folder, just replace the URL with the filename.
<param ve-image 
       label="James Ward Sketch of Larch Tree, 1859" 
       description="Photograph" 
       license="public domain"
       url="16-07-06-Rathaus_Graz_Turmblick-RR2_0275.jpg">

##### videos
code ID from youtube videos will fill the parameter "vid".
<param ve-video 
       vid="aSprX-NIr14" >

##### Jstor Global Plant Specimens
to use a specimen image from JSTOR only. (if you want to use the Harv Herbarium specimens, download the image and upload it using the param=ve-image format. Access Jstor Global Plants through Hollis Databases or another means of access. search for plant, and once selected, the parameter "jpid" will be filled by the part of the URL of the JSTOR plant specimen webpage after the word "stable/" and before "?search".
<param ve-plant-specimen 
       jpid="10.5555/al.ap.specimen.p00662193">

##### Online Book Viewer
Nav to archive.org. search in the lower search bar for a book by topic. open it full-screen. then copy the URL and paste into the parameter "src".
<param ve-iframe 
       src="https://archive.org/details/Galaxy_v18n06_1960-08/page/n3/mode/2up?view=theater">

<param ve-entity 
       eid="Q155" 
       title="Brazil">
<param ve-entity 
       eid="Q267376" 
       title="World Tree">
<param ve-entity 
       eid="Q210377" 
       title="gauchos">
<param ve-entity 
       eid="Q46429" 
       title=“Guaraní people”>
<param ve-entity 
       eid="Q84263196" 
       title=“COVID-19 pandemic”>

#### Annotate images with zoom-in slideshow

to add *only* zoomed-in portions of an image, include image as usual in code below text. open visual essay and select the jstor edit button on image, bottom of menu options on the right side. ctrl+shift+click and drag to select the zoom parameters. type an annotation in comment area. (if you add text into the "tag" section, it will show up in the image metadata.) click ok. add as many as you like. then select 'play annotations' in menu bar to view all. This feature only supports one image at a time.
<param ve-image 
       description="Photograph" 
       license="public domain"
       url="16-07-06-Rathaus_Graz_Turmblick-RR2_0275.jpg"
       >

#### Maps
the following is instructions on how to add a map. the base map includes a title, coordinates from google maps, and a zoom attribution. to add layers: nav to geojson.io, an open-source mapping tool that creates maps in json format. you can draw segments, add pin drops, and create area regions in geojson. 
<param ve-map
       title="Larches Native to Siberia"
       center="53.524605, 107.963269"
       zoom="2"
       >
<param ve-map-layer 
       geojson 
       url="https://raw.githubusercontent.com/hehardenbergh/dh_test/main/Sargent-in-Siberia.json"
       >
linking text to a part of the map:
<span data-mouseover-map-flyto="53.524605, 107.963269",
       14>
       Lake Baikal. 
       </span>

