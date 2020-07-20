<template>

  <div class="main-content">

    <div class="main-content__top">
        <h1 class="main-content__title">  
          
            <div class="row">
            <div class="col-9 col-xs-10 col-sm-10 col-md-9 col-lg-11">
            <input class="searchbar" type="text" placeholder="Search">
            <button class="filter buttonclear" style="margin-left:3%"><i class="fa fa-filter" aria-hidden="true"></i>Filter</button>
            </div>
            <div class="col-3 col-xs-2 col-sm-3 col-md-3 col-lg-1">
              <button class="buttonclear" style="margin-left:-30%"><i class="far fa-bell nav-fa" aria-hidden="true"></i></button>
              <label><img
                  src="1.jpg"
                  alt="logo-img"
                  class="img"
                >
              </label>
              <button class="buttonclear"><i class="fa fa-ellipsis-v nav-fag" aria-hidden="true"></i></button>
            </div>
            </div>
        </h1>
        
          <div class="row">
             <h1 class="main-content__subtitle" style=" width: 100%; margin-top:-1%;">  
            <div class="col-xs-11 col-sm-11 col-md-11 col-lg-11">
              <label>My Filters:</label>
              <label><i class="fas fa-cheese faedit" aria-hidden="true"></i>Special</label>
              <label><i class="fas fa-concierge-bell faedit" aria-hidden="true"></i>Breakfast</label>
              <label><i class="fas fa-bread-slice faedit" aria-hidden="true"></i>Lunch</label>
            </div>
             </h1>
          </div>
        
    </div>
    
   
    <div class="row">
    <div class="col-md-9">
    <div class="main-content__body">
      <div>345 <label style="color: grey">meals found</label></div>
      <div class="row">
        <div class="col-md-3 food-list" style="background-color:#FFE9F8;">
          <div class="rating">
            <i class="fas fa-star ratingcol" aria-hidden="true"></i><label class="ratinglabel">4.2</label>
          </div>
          <div class="like">
            <center><i class="far fa-heart heart" aria-hidden="true"></i></center>
          </div>
          
          <div class="fooddetails">
            <center><img  src="1.png" alt="logo-img" class="fooditem"></center>
          
          <div class="foodname">
            <b>Akara</b>
          </div>
          <div class="foodweight">
            250g
          </div>
          </div>
          
          <div class="price">
            <b>&#8358;200</b>
          </div>
        </div>
        <div class="col-md-3 food-list" style="background-color:#FFF3E9;">
          <div class="rating">
            <i class="fas fa-star ratingcol" aria-hidden="true"></i><label class="ratinglabel">4.5</label>
          </div>
          <div class="like">
            <center><i class="far fa-heart heart" aria-hidden="true"></i></center>
          </div>
          
          <div class="fooddetails">
            <center><img  src="roastpotatoes.png" alt="logo-img" class="fooditem"></center>
          
          <div class="foodname">
            <b>Fried Yam</b>
          </div>
          <div class="foodweight">
            300g
          </div>
          </div>
          
          <div class="price">
            <b>&#8358;200</b>
          </div>
        </div>
        <div class="col-md-3 food-list" style="background-color:#E9FFFF;">
          <div class="rating">
            <i class="fas fa-star ratingcol" aria-hidden="true"></i><label class="ratinglabel">5.0</label>
          </div>
          <div class="like">
            <center><i class="far fa-heart heart" aria-hidden="true"></i></center>
          </div>
          
          <div class="fooddetails">
            <center><img  src="stewed vegetables.png" alt="logo-img" class="fooditem"></center>
          
          <div class="foodname">
            <b>Jollof Beans</b>
          </div>
          <div class="foodweight">
            400g
          </div>
          </div>
         
          <div class="price">
            <b>&#8358;200</b>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-3 food-list" style="background-color: #ECF0FF;">
          <div class="rating">
            <i class="fas fa-star ratingcol" aria-hidden="true"></i><label class="ratinglabel">4.4</label>
          </div>
          <div class="like">
            <center><i class="far fa-heart heart" aria-hidden="true"></i></center>
          </div>
          
          <div class="fooddetails">
            <center><img  src="seafood.png" alt="logo-img" class="fooditem"></center>
          
          <div class="foodname">
            <b>Afang Soup</b>
          </div>
          <div class="foodweight">
            350g
          </div>
          </div>
          
          <div class="price">
            <b>&#8358;200</b>
          </div>
        </div>
        <div class="col-md-3 food-list" style="background-color:#F6FFE9;">
          <div class="rating">
            <i class="fas fa-star ratingcol" aria-hidden="true"></i><label class="ratinglabel">4.9</label>
          </div>
          <div class="like">
            <center><i class="far fa-heart heart" aria-hidden="true"></i></center>
          </div>
          
          <div class="fooddetails">
            <center><img  src="beansoup.png" alt="logo-img" class="fooditem"></center>
          
          <div class="foodname">
            <b>Egusi Soup</b>
          </div>
          <div class="foodweight">
            350g
          </div>
          </div>
         
          <div class="price">
            <b>&#8358;200</b>
          </div>
        </div>
        <div class="col-md-3 food-list" style="background-color:#ECF0FF;">
          <div class="rating">
            <i class="fas fa-star ratingcol" aria-hidden="true"></i><label class="ratinglabel">3.9</label>
          </div>
          <div class="like">
            <center><i class="far fa-heart heart" aria-hidden="true"></i></center>
          </div>
          
          <div class="fooddetails">
            <center><img  src="stewed vegetables1.png" alt="logo-img" class="fooditem"></center>
          
          <div class="foodname">
            <b>Ogbono Soup</b>
          </div>
          <div class="foodweight">
            400g
          </div>
          </div>
          
          <div class="price">
            <b>&#8358;200</b>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-3 food-list" style="background-color:#FFE9F8;">
          <div class="rating">
            <i class="fas fa-star ratingcol" aria-hidden="true"></i><label class="ratinglabel">4.2</label>
          </div>
          <div class="like">
            <center><i class="far fa-heart heart" aria-hidden="true"></i></center>
          </div>
          
          <div class="fooddetails">
            <center><img  src="soup.png" alt="logo-img" class="fooditem"></center>
          
          <div class="foodname">
            <b>Jollof Rice</b>
          </div>
          <div class="foodweight">
            350g
          </div>
          </div>
          
          <div class="price">
            <b>&#8358;500</b>
          </div>
        </div>
        <div class="col-md-3 food-list" style="background-color:#FFFEE9;">
          <div class="rating">
            <i class="fas fa-star ratingcol" aria-hidden="true"></i><label class="ratinglabel">4.4</label>
          </div>
          <div class="like">
            <center><i class="far fa-heart heart" aria-hidden="true"></i></center>
          </div>
          
          <div class="fooddetails">
            <center><img  src="1.png" alt="logo-img" class="fooditem"></center>
          
          <div class="foodname">
            <b>Coconut Rice</b>
          </div>
          <div class="foodweight">
            300g
          </div>
          </div>
          
          <div class="price">
            <b>&#8358;500</b>
          </div>
        </div>
        <div class="col-md-3 food-list" style="background-color:#FFE9F6;">
          <div class="rating">
            <i class="fas fa-star ratingcol" aria-hidden="true"></i><label class="ratinglabel">4.2</label>
          </div>
          <div class="like">
            <center><i class="far fa-heart heart" aria-hidden="true"></i></center>
          </div>
         
          <div class="fooddetails">
            <center><img  src="okroshka.png" alt="logo-img" class="fooditem"></center>
          
          <div class="foodname">
            <b>Poundo Yam</b>
          </div>
          <div class="foodweight">
            400g
          </div>
          </div>
          
          <div class="price">
            <b>&#8358;200</b>
          </div>
        </div>
      </div>
      <center>
        <div class="load">
        <i class="fa fa-refresh faedit" aria-hidden="true"></i>Load More
        </div>
      </center>

    </div>
    </div>
    <div class="col-md-3 all">
      <h1><b style="font-size: 0.6em; float: left;">My Order</b></h1>
      <div id="editlink" style="">edit</div>
      <div class="clear">
      </div> 
      <div class="orderdetails" style="margin-top:20px; font-size: 0.91em; ">
        <div class="time" style="padding-top:20px;">
          <div>
           <i class="fas fa-clock faedit1 facont" style="color:#FF6D00;" aria-hidden="true"></i><label class="labelpad">14:30pm</label>
          </div>
         
        </div>
        <div class="address" style="padding-top:20px;">
          <div>
           <i class="fas fa-map-marker-alt faedit1 facont" style="color:#FF6D00;" aria-hidden="true"></i><label class="labelpad">42, Montgomery road Yaba, First Floor</label>
          </div>
        </div>
        <div class="comment" style="padding-top:20px; padding-bottom:10px;">
          <div>
           <i class="fas fa-comment-dots faedit1 facont" style="color:#FF6D00;" aria-hidden="true"></i><label class="labelpad">Please, add extra pepper</label>
          </div>
        </div>
        <hr>
        
        <div class="ordercontainer">
          <div class="fooditemdetails">
            <img  src="okroshka.png" alt="logo-img" class="fooditemcheck">
             <b style="font-size: 13px; float:left; padding-left:10%;">Beans</b>
             <p class="movegram">350g</p>
              <div class="buttoncont" style=" width:56px; margin-left:180px;">
               <button class="buttonclear">-</button>
              1
               <button class="buttonclear">+</button>
             </div>
              <div style="float:right; margin-top:-20px;">
               <b style="">&#8358;200</b>
               <button class="buttonclear" style="margin-right:10px; color:grey; ">X</button>
             </div>
             <div class="clear"></div>
            
            
          </div>
          <div class="fooditemdetails">
            <img  src="roastpotatoes.png" alt="logo-img" class="fooditemcheck">
             <b style="font-size: 13px; float:left; padding-left:10%;">Chicken</b>
             <p class="movegram">300g</p>
              <div class="buttoncont" style=" width:56px; margin-left:180px;">
               <button class="buttonclear">-</button>
              1
               <button class="buttonclear">+</button>
             </div>
              <div style="float:right; margin-top:-20px;">
               <b style="">&#8358;500</b>
               <button class="buttonclear" style="margin-right:10px; color:grey; ">X</button>
             </div>
             <div class="clear"></div>
            
            
          </div>
          <div class="fooditemdetails">
            <img  src="roastpotatoes.png" alt="logo-img" class="fooditemcheck">
             <b style="font-size: 13px; float:left; padding-left:10%;">Jollof Rice</b>
             <p class="movegram">300g</p>
              <div class="buttoncont" style=" width:56px; margin-left:180px;">
               <button class="buttonclear">-</button>
              1
               <button class="buttonclear">+</button>
             </div>
              <div style="float:right; margin-top:-20px;">
               <b style="">&#8358;500</b>
               <button class="buttonclear" style="margin-right:10px; color:grey; ">X</button>
             </div>
             <div class="clear"></div>
          </div>
          
          <div class="dragdrop">
            <p style="padding-top:6px;">Drag&Drop</p>
          </div>
          
          <div class="total">
            <p style="float:left;">Total</p>
            <p class="adjust" style="float:right; font-weight: bold; font-size: 14px;">&#8358;1200</p>
          </div>
          <div class="clear"></div>
          <div class="adjust checkoutcont">
            <div class="checkout">
            <p>Checkout</p>
            </div>
          </div>
          
          <div class="carddetails adjust">
          <div class=carddetcont>
            <img  src="visa.png" alt="visa-img" style="">
            <span style="padding-left:20%;  font-size:14px;">**** **** **** 6132</span>
          
            <i class="fa fa-pencil-square-o fa-1px fascope"></i>
            
          </div>
          </div>
          <br>
        </div>
      </div>
    </div>
    </div>
    
  </div>

</template>

<script>

export default {
  name: 'home'
}

</script>
