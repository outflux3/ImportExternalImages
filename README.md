# Processwire  ImportExternalImages
Imports External Images - for use in Processwire 3


## What it Does

This module allows you to monitor RTE fields for the presence of external images, and to import those images to a local image field, and subsequently replace the reference within the markup to the newly imported (local) image.

## Configuration

Configuration options allow you to specify **Textarea** fields to search for external image references, the **Images** field to use for importing, and which **Templates** to enable the feature on.

## Use Cases

One use case could be for a company that sells a product and that product has some reviews on external sites. The site owner wishes to copy and paste the entire review, along with all of the images into their site. Assuming the review site has granted the site owner the rights to reproduce the images on their own site, the site owner can now copy and paste the content into their ProcessWire site, and have all of the image be local, which allows them to resize, crop, and otherwise manipulate the local images. This also prevents errors in case the site owner tries to click on an externally referenced image (because the image dialog will not work with an external image).

## Status

The module should be considered beta and users are advised to test the functionality before integrating to a live site. The module is installed and in active use on 3 live sites, so at this time, there are no known issues, errors or side effects to having it installed.

