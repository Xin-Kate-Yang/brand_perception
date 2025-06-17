define(['pipAPI', 'https://cdn.jsdelivr.net/gh/baranan/minno-tasks@0.*/IAT/qualtrics/quiat9.js'], function(APIConstructor, iatExtension){
    var API = new APIConstructor();

	return iatExtension({
		category1 : {
			name : ‘Apple’, //Will appear in the data.
			title : {
				media : {word : 'Apple’}, //Name of the category presented in the task.
				css : {color:'#31940F','font-size':'2em'}, //Style of the category title.
				height : 4 //Used to position the "Or" in the combined block.
			}, 
			stimulusMedia : [ //Stimuli content as PIP's media objects
    		  {image : ‘a1.png'}, 
    			{image : ‘a2.png'}, 
    			{image : ‘a3.png'}, 
    			{image : ‘a4.png'}, 
    			{image : ‘a5.png'}, 
    		  {image : ‘a6.png'}, 
    			{image : ‘a7.png'}, 
    			{image : ‘a8.png'}, 
    			{image : ‘a9.png'}, 
    			{image : ‘a10.png'}, 
    			{image : ‘a11.png'}, 
    			{image : ‘a12.png'}
			], 
			//Stimulus css (style)
			stimulusCss : {color:'#31940F','font-size':'1.8em'}
		},	
		category2 :	{
			name : 'Google Pixel’, //Will appear in the data.
			title : {
				media : {word : 'Google Pixel'}, //Name of the category presented in the task.
				css : {color:'#31940F','font-size':'2em'}, //Style of the category title.
				height : 4 //Used to position the "Or" in the combined block.
			}, 
			stimulusMedia : [ //Stimuli content as PIP's media objects
    		  {image : ‘p1.png'}, 
    			{image : ‘p2.png'}, 
    			{image : ‘p3.png'}, 
    			{image : ‘p4.png'}, 
    			{image : ‘p5.png'}, 
    		  {image : ‘p6.png'}, 
    			{image : ‘p7.png'}, 
    			{image : ‘p8.png'}, 
    			{image : ‘p9.png'}, 
    			{image : ‘p10.png'}, 
    			{image : ‘p11.png'}, 
    			{image : ‘p12.png'}			], 
			//Stimulus css
			stimulusCss : {color:'#31940F','font-size':'1.8em'}
		},	

		base_url : {//Where are your images at?
			image : 'https://xin-kate-yang.github.io/brand_perception/images/'
		} 
	});
});
