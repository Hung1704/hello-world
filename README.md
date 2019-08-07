
# What is mark down

  ## Emphasis
  * _this will be italic_
  * **this will be bolder**
  * ~deleted line~
  
  ## List
  * list1
    * sublist1
    * sublist2
  * list2
    * sublist1
    * sublist2
    
  ## Order list
  1. character 'a'
      1. apple
      1. ant
  1. character 'b'
      1. banana 
      1. ball


  ## Check Box
  - [X] this is a complete item
  - [ ] this is an incomplete item
  - [X] this is a small change to test the desktop works correctly
  
  ## Tables
  First Header | Second Header
  ------------ | -------------
  Content from cell 1 | Content from cell 2
  Content in the first column | Content in the second column
  
  ## Blocls
  Here are large one and small one.
  
  small one
  `Formal one word or one line`
  
  ## Link
  * [myWebsite](https://www.lhlai.nctu.me/)
  * [myFacebook](https://www.facebook.com/lovegodmimi)
  
  ## Quote
  As Kanye West said:
  > We're living the future so
  > the present is our past.
  >> quote two sentence
  
  ## Photo
  ![My Photo](67737617_2167409650054850_2423996301101236224_n.jpg)
  Format: ![My handsome Photo](url)
  
  

  ## Code
  ``` js
 var myImage = document.querySelector('img');

myImage.onclick = function(){
    var mySrc = myImage.getAttribute('src');
    if(mySrc === 'image/image1.png'){
      myImage.setAttribute ('src','image/image2.jpg');
    } else {
      myImage.setAttribute ('src','image/image1.png');
    }
}
  ```
    
  
