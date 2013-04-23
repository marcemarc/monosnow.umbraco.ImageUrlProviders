monosnow.umbraco.ImageUrlProviders
==================================

a provider for the umbraco image control (see http://24days.in/umbraco/2012/introducing-the-umbraco-image-control/) to work with Eksponent Crop Up, drop the monosnow.umbraco.ImageUrlProviders into the bin folder,
you can then use then drop the image control onto the page and set CropUp name and mode via parameters, eg

<umbraco:Image runat="server" field="relatedImage" Parameters="cropAlias=thumb&cropMode=BestFit" Provider="CropUp" />

would display an image from a property called 'relatedImage' on the current model, and would use a defined crop in the CropUp configuration file called 'thumb' and would use the cropMode BestFit, to make the image exactly fit the crop width and height
 