# css3
1. 边框
 * 圆角边框  
   div  
    {  
      border:2px solid;  
      border-radius:25px;  
    }  
 * 阴影  
    div  
     {  
       box-shadow: 10px 10px 5px #888888;  
    }  
2. 背景  
* background-size 属性规定背景图片的尺寸。 
* background-origin 属性  
3. 过渡
    div  
    {  
       transition: width 2s;  
       -moz-transition: width 2s;	/* Firefox 4 */  
       -webkit-transition: width 2s;	/* Safari 和 Chrome */  
       -o-transition: width 2s;	/* Opera */  
    }  
> 多项改变  
   div  
   {  
      transition: width 2s, height 2s, transform 2s;  
      -moz-transition: width 2s, height 2s, -moz-transform 2s;  
      -webkit-transition: width 2s, height 2s, -webkit-transform 2s;  
      -o-transition: width 2s, height 2s,-o-transform 2s;  
   }  
