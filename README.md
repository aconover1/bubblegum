# bubblegum
*{ box-sizing:border-box; }


html,body{
  margin:0;                       
  padding:0;                      
  color:#000;                     
  background:#fff;                
}



.page{
  width:2000px;                   
  max-width:1200px;               
  min-width:320px;                
  margin:20px auto;               
  padding:0 20px;                 
}



header{
  text-align:center;              
  font-variant:small-caps;        
  font-size:18px;                 

  border-top:1px solid #000;      
  border-bottom:1px solid #000;   

  position:relative;              
  padding:8px 0;                  
  margin:0;                       
}


header::after{
  content:"";                     
  position:absolute;              
  top:0;                          
  right:0;                        
  width:20px;                     
  height:100%;                    
  background:#000;                
}


  

.title-row{
  display:flex;                   
  align-items:flex-start;         
  gap:24px;                       
  margin-top:0;                   
}


.title-row h1{
  flex:1 1 auto;                  
  margin:16px 0 8px;              
  font-size:45px;                 
  line-height:1.05;               
  font-weight:700;                
}


aside{
  flex:0 0 320px;                 
  margin:0 0 0 auto;              
  padding:14px 36px 14px 16px;    
  text-align:right;               
  position:relative;              
  border-top:none;                
}


aside::after{
  content:"";                     
  position:absolute;              
  top:0; right:0;                 
  width:20px;                     
  height:100%;                    
  background: #d234;             
}


aside strong{ font-weight:700; }




  
  

article{
  position:relative;              
  margin:12px auto 0;             
  z-index:1;                      
  overflow:hidden;                
  max-width:85%;                  
}


article h2{
  font-style:italic;              
  font-weight:700;                
  font-size:35px;                 
  text-align:center;              
  line-height:1.3;                
  margin:28px 0 18px;             
}


article p,
article section{
  margin:0 0 18px;                
  line-height:1.6;                
  font-size:17px;                 
       
}


article section{
  background:#fff8e2;             
  border:2px solid #ff2543;       
  border-left-width:60px;          
  padding:16px 18px;               
}



article::before{
  content:"W";                    
  position:absolute;              
  top:0; left:50%;                
  transform:translate(-50%, 0);   
  font-family:"Times New Roman", serif; 
  font-size:560px;                
  font-weight:bold;               
  line-height:1;                  
  color:rgba(88,88,88,0.08);      
  z-index:0;                      
  pointer-events:none;            
}


article::after{
  content:"c";                    
  position:absolute;              
  top:0; left:50%;                
  transform:translate(140%, 0);   
  font-family:"Times New Roman", serif; 
  font-size:320px;                
  font-weight:bold;               
  line-height:1;                  
  color:rgba(174,174,174,0.07);   
  z-index:0;                      
  pointer-events:none;            
}


  

footer{
  width:100%;                     
  margin:24px 0 0 0;             
  padding:6px 12px;               
  text-align:right;               

  font-size:14px;                 
  color:#666;                     
  font-style:italic;              

  border-top:1px solid #999;      
}


footer a{
  color:inherit;                  
  text-decoration:underline;      
}
