# apple-scpt 
tell application"浏览器/打开运行的app"          
   open location"URL"      
   --
   open location"URL        
   --
   end tell         
   
            
标签类：   
 tell applicationn "浏览器/打开运行的app"   
   open location“URL”   
   --标签名   
   open location"URL"   
   --标签名      
   open location"URL"    
   --     
end tell     

  

没有表情类：                  

set websiteList to {"URL","URL","URL",}                 
                                                 
tell application"浏览器/打开运行的app"                            
     activate                           
	 repeat with website in websiteList                          
	        open location website                                          
	end repeat                                                  
end tell                      
