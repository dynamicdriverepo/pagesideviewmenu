# Page Sideview Menu #

*Description:* This menu displays itself prominently on the page with the help of css3 transforms and transitions. The menu glides in from the left edge of the screen while shrinking the rest of the page content into the background, bringing the user's focus squarely on the menu itself. Clicking anywhere on the page again hides the menu and returns the page back to its original state.

## Directions ##

*Step 1:* This script uses the following external files:

+ jQuery 1.10 or above (served via Google CDN)
+ sideviewmenu.js
+ sideviewmenu.css
+ menucontents.txt (external file where menu markup is defined)

*Step 2:* Add the below code to the HEAD section of your page:

	<meta name="viewport" content="width=device-width">
	<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>
	
	<link href='http://fonts.googleapis.com/css?family=Asul:400,700' rel='stylesheet' type='text/css'>
	
	<link type="text/css" rel="stylesheet" href="sideviewmenu.css" />
	
	<script src="sideviewmenu.js">
	
	/***********************************************
	* Page Sideview Menu- (c) Dynamic Drive DHTML code library (www.dynamicdrive.com)
	* This notice MUST stay intact for legal use
	* Visit Dynamic Drive at http://www.dynamicdrive.com/ for this script and 100s more
	***********************************************/
	
	</script>
	
	<script>
	
	jQuery(function(){ // on DOM Load
		sideviewmenu({ // call sideviewmenu() function
			menuid: 'sideviewmenu',
			onopenclose:function(state){ // state is either "open" or "closed"
				// custom code
			}
		})
	})
	
	</script>


*Step 3:* Then, add the below sample markup to your page:

	<div class="toggler" onClick="sideviewmenu.toggle()"></div>

## Page Sideview Menu set up ##

See script project page for additional details on setup and documentation: <http://www.dynamicdrive.com/dynamicindex17/notifier.htm>
