# ![alt tag](https://github.com/tanhng/utubesearch/blob/master/img/QTASearch.png)
**QTASearch** is a Video Search Engine built using the Youtube API v3.

* Features/Technologies: 
  * HTML5, CSS3, JavaScript
  * Youtube Data API v3
  * jQuery $.get() request
  * inserting HTML via html() method
  * Uses search.list method to search videos.
  * 'Fancybox' lightbox script to open the video on our site instead of being redirected to YouTube.

## Version
1.0.0

 
## Usage
  In your js/script.js, find functions search(), prevPage(), nextPage().  
  
  Enter your API key in the GET request for all the 3 functions.
  
   	 $.get(
		"https://www.googleapis.com/youtube/v3/search",{
			part: 'snippet, id',
			q: q,
			pageToken: token,
			type:'video',
			key: 'YOUR_API_KEY_HERE'},
			function(data){

## Snapshots
  
 **Search Video** | 
--- |
 ![alt text](https://github.com/tanhng/utubesearch/blob/master/img/search-view.png)   |
 

## Vendors
jQuery - [http://jquery.com](http://jquery.com) 

Fancybox - [http://fancybox.net/](http://fancybox.net/)


## License
MIT License
