	/* 
  *	 getElementByAttribute(htmlTag, attr)
  *  Retrieves the entire element from the DOM that matches both tag name and attribute
	*/

	function getElementByAttribute(tagName, attribute){
		var withProperty = [],
		tagNameElements = document.getElementsByTagName(tagName);
		
		for (i = 1; i < tagNameElements.length; i++) {
			if (tagNameElements[i].hasAttribute(attribute)) {
				return tagNameElements[i];
			}
		}
	}

/* Use Case
var el = getElementByAttribute('iframe','allowfullscreen');

// RETURNS <iframe id="exampleIframe"" width="100%" height="100%" allowfullscreen="yes" src="/examples/video.mp4"></iframe>
 */
