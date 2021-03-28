# n1-API-Documentation
Documentation for n1 channel backend api 


Get All Drama List

https://creator.n1channel.org/drama/read.php


Response

{
	
"drama": [
		
{
			
"drama_id": "",
			
"drama_summary": ,
			
"drama_cover": ,
			
"drama_title": ,
			
"created": ,
			
"cat_id": ,
			
"release_date": ,
			
"status": 
		
},...
   
 ]
   
}




Get Info for single Drama

https://creator.n1channel.org/drama/read_one.php?drama_id={id}


Response

{
	
"drama_id": ,
	
"drama_title": ,
	
"drama_cover": ,
	
"drama_summary": ,
	
"created": ,
	
"status": ,
	
"release_date": ,
	
"cat_id": ,
	
"cat_name": 

}



Search Drama 
 
https://creator.n1channel.org/drama/search.php?s={keyword}

Response

{
	
"drama": [
		
{
			
"drama_id": "",
			
"drama_summary": ,
			
"drama_cover": ,
			
"drama_title": ,
			
 "created": ,

 "cat_id": ,
			
"release_date": ,
			
"status": 

},...
   
   ]
  
  }
    



Get Episode List For Single Drama

https://creator.n1channel.org/drama/readEpisode.php?drama_id={id}


Response 

{
	"episodes": [
		{
			"drama_id": ,
			"ep_id": ,
			"ep_num": ,
			"ep_title": ,
			"vid_url": ,
			"dw_url":
		},...
]
}



Get Episode Info

https://creator.n1channel.org/drama/readoneEpisode.php?ep_id={episode id}

Response 

{
	"ep_id": ,
	"drama_id": ,
	"ep_num": ,
	"ep_title": ,
	"vid_url": ,
	"dw_url": 
}



GET Ads

https://creator.n1channel.org/ad/read.php

Response

{
	"records": [
		{
			"ad_id":,
			"url": ,
			"redirect": ,
			"ad_placement": 
		},...
	]
}

Get Pagination
creator.n1channel.org\/drama\/read_paging.php

Response 
{ record [
{
			
"drama_id": "",
			
"drama_summary": ,
			
"drama_cover": ,
			
"drama_title": ,
			
"created": ,
			
"cat_id": ,
			
"release_date": ,
			
"status": 
		
},...
],
paging{
"first" : "",
"pages":{
{
"page": 2,
"url": "https:\/\/creator.n1channel.org\/drama\/read_paging.php?page=2",
"current_page": "no"
},...
},
"last" : ""

}
