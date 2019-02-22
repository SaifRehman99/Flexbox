# Flexbox
It contains all the details about Flexbox.
<!-- FlexSheet -->
<!-- Made by Saif Rehman -->
#Using display :flex it floats the items in the line without using the floats (no floats)
		display:flex;
#Using flex :1,2,3 , it determines the size of the div.
		flex:1;
		flex:2;(and so on)
#as the height and width are all same of the container and the div, bhaley content zyada hu ya kam
#for this we use 
		align-items:flex-start;
		align-items:flex-end;
		align-items: center;
    
#this is the by def action 
        align-items: stretch;


#If we want to flex in col and rows 
	    
		flex-direction: column;
		flex-direction: row; 
      


#If we want to flex in col and row but in reverse Directions 
		flex-direction: column-reverse;
		flex-direction: row-reverse;
	    

#for putting margin we use  
#this is by def action 
        justify-content: flex-start;
    
#for putting margin we use     
		justify-content: flex-end;
		justify-content: space-around;
		justify-content: space-between;
		justify-content: center;
	    
#in flex box we use flexbasis instead of width 
    	flex-basis: 324px;
    

#Flex wrap is used to wrap the div when the size of the window shrinks 
    	flex-wrap: wrap;