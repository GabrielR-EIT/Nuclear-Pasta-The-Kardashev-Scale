# Nuclear Pasta's The Kardashev Scale Pseudocode

## General (All Pages)

ON page load
  set page(currentPage)_link = active

IF pageX_link is touched 
  set pageX_link = highlighted  
ELSE
  set pageX_link = NOT highlighted

IF pageX_link is pressed
  GO TO pageX
  
IF videoX is pressed
  TOGGLE videoX_Playing

## Home Page

IF galleryImageX is pressed
  SET galleryView = 1
  SET galleryImage = galleryImageX
  
IF galleryView = TRUE
  IF exitGalleryView is pressed
    SET galleryView = 0
