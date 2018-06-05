# clickable-pop-up-boxes


  		  
## Tutorial		  
For detailed instruction's, view Solodev's [How to Add Pop-Up Info Boxes to Your Website](https://www.solodev.com/blog/web-design/how-to-add-pop-up-info-boxes-to-your-website.stml) article.
 
## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/fbvL6eug/).

## HTML

The tutorial contains the following basic HTML markup.

```
<div class="big-box-spaces py-5">
  <div class="container py-5">
    <section class="spaces">
      <div class="row">
        <div class="col-lg-3 col-xs-12 box-text-space">
          <h2 class="text-uppercase">Fly With Us</h2>
          <p>Travel through the Web Experience Space with us!</p>
          <a href="https://www.solodev.com/contact/" class="btn btn-danger">Sign Up Today</a>
        </div>
        <div class="col-lg-9 col-xs-12 box-space-photo">
          <div class="small-box-space-photo">
            <div class="mini-box-space-photo position-relative">
              <img src="https://s3.amazonaws.com/uploads.hipchat.com/485069/4047181/EWbdPrNIfyuao7j/upload.png" alt="Holstein space" class="w-100 img-responsive mt-3 mt-lg-0">
              <button type="button" class="pop-button button1" data-placement="bottom" data-trigger="click" data-toggle="popover" title="Did you know?" data-content="This purple planet is...Earth!"><span>&#43;</span></button>
              <button type="button" class="pop-button button2" data-placement="bottom" data-trigger="click" data-toggle="popover" title="Did you know?" data-content="Dan Spacley Pilots the ship to a successful website!"><span>&#43;</span></button>
              <button type="button" class="pop-button button3" data-placement="bottom" data-trigger="click" data-toggle="popover" title="Did you know?" data-content="Here you can see planet Markury, where your digital marketers roam."><span>&#43;</span></button>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</div>
      

```

## CSS

All required CSS is contained with clickable-pop-up-boxes.css

## JavaScript

All required JS is contained with clickable-pop-up-boxes.js

## External Resources

This tutorial includes the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" rel="stylesheet">
<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js"></script>
```

