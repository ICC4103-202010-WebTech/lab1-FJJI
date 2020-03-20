
# :boom: :boom: Point 3.3 :boom: :boom:      
 The structure of the list in the 'Elements' tab is from more general to more specific, being items       
included in table-rows that they can also be part of another bigger table-row      
      
- This can be seen in this example:      


>		 -> Banner
>		        -> the links of the banner     
>		-> Big list that includes the pages     
>	        -> box 1     
>	            -> page 1     
>		    -> box 2     
>				-> page 2
 # :boom: :boom: Point 3.4 :boom: :boom:  
  The files downloaded when i pressed F5 in `Sources` contains files as `hn.js` and `news.css`      
   
- `hn.js`      
   
      
>Theese are the functions that appears in the page, it haves a similarities with the .h files  
 in c and c++, being first declare all altogether and then they are its own development      
- `news.css`     
    
    
>Theese are the 'aesthetic' part of the page as witch size to use and if it uses bold or italic and colour.           
>
>It also brings some other stuff as where to put items that are declared, for example, '.votearrow',  
 that has the size, the margin of it and a image in the background a gif 'grayarrow.gif' 
# :boom: :boom: Point 3.5 :boom: :boom:  
- When the page is refreshed it can be seen seven requests and each one of them  called in the HTML code.   
(index can be seen as the initiator).  
  
- The request were:  
  
    >- news.ycombinator.com   
    >- news.css?S5Ty60GFbTgUrObD86pQ      
    >- y18.gif  
    >- s.gif 
    >- hn.js?S5Ty60GFbTgUrObD86pQ   
    >- grayarrow2x.gif    
    >- favicon.ico  
  
- The HTTP method used for the seven request is GET, getting in all of them a status code of 200.  
  
- Seeing the `Headers` on any of the requests and, when you put near 'Response Headers', in 'view source', you can see  
that the Server used is Ngix.