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
       
[_Ilexparaguariensis_](https://powo.science.kew.org/taxon/urn:lsid:ipni.org:names:315555-2) is an evergreen shrub or tree native to the subtropical forests of Brazil, Paraguay, Uruguay, and Argentina that can grow up to forty-nine feet tall. It’s a plant species of the genus ilex (or “holly”) that contains caffeine as well as other alkaloid components, and it has stimulant, diuretic, antioxidant, and antimicrobial properties that made it attractive to both the indigenous Guaraní people and to Spanish colonial settlers. After being dried, roasted, and powdered, mate leaves are used to prepare a hot or cold beverage, also known as mate or Paraguayan Tea. World Tree. The loose powder is typically steeped in hot water and strained through a metallic straw, or bombilla, shared by many people, passing from mouth to mouth. During the 19th century, the drink became associated with South American *gauchos*. gauchos . The same mate and bombilla are shared in social gatherings, a habit that has endured despite recent public health campaigns to prevent COVID-19 pandemic.



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

#### Image with paragraph

to add zoom-in's in an image, include image as usual in code below text. open visual essay and select the jstor edit button on image, bottom of menu options on the right side. ctrl+shift+click and drag to select the zoom parameters. type an annotation.
<param ve-image 
       label="James Ward Sketch of Larch Tree, 1859" 
       description="Photograph" 
       license="public domain"
       url="16-07-06-Rathaus_Graz_Turmblick-RR2_0275.jpg">



