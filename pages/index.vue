<template>
<div>
  <div class="d-1-section">
    <div class="d-1-menu-wrapper">
        <a href="#section1" class="d-1-menu-item-wrapper">
            <div class="d-1-menu-item-text">Channel 1</div>
        </a>
        <a href="#section2" class="d-1-menu-item-wrapper">
            <div class="d-1-menu-item-text">Channel 2</div>
        </a>
        <a href="#section3" class="d-1-menu-item-wrapper">
            <div class="d-1-menu-item-text">Channel 3</div>
        </a>
        <a href="#section4" class="d-1-menu-item-wrapper">
            <div class="d-1-menu-item-text">Channel 4</div>
        </a>
        <a href="#section5" class="d-1-menu-item-wrapper">
            <div class="d-1-menu-item-text">Channel 5</div>
        </a>
    </div>
</div>
    <div id="section1" class="d-2-section">
        <div class="d-2-youtube-wrapper">
            <div style="padding-top:56.17021276595745%" class="w-embed-youtubevideo d-2-youtube"><iframe src="https://www.youtube.com/embed/EAHzlJFPWLc" frameborder="0" style="position:absolute;left:0;top:0;width:100%;height:100%;pointer-events:auto" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe></div>
        </div>
    </div>
    <div id="section2" class="d-3-section">
        <div class="d-3-youtube-wrapper">
            <div style="padding-top:56.17021276595745%" class="w-embed-youtubevideo d-3-youtube"><iframe src="https://www.youtube.com/embed/clMYVElbo2w" frameborder="0" style="position:absolute;left:0;top:0;width:100%;height:100%;pointer-events:auto" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
        </div>
    </div>
    <div id="section3" class="d-4-section">
        <div class="d-4-youtube-wrapper">
            <div style="padding-top:56.17021276595745%" class="w-embed-youtubevideo d-4-youtube"><iframe src="https://www.youtube.com/embed/-FlxM_0S2lA" frameborder="0" style="position:absolute;left:0;top:0;width:100%;height:100%;pointer-events:auto" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
        </div>
    </div>
    <div id="section4" class="d-5-section">
        <div class="d-5-youtube-wrapper">
            <div style="padding-top:56.17021276595745%" class="w-embed-youtubevideo d-5-youtube"><iframe src="https://www.youtube.com/embed/X1uaOtiJ9Vc" frameborder="0" style="position:absolute;left:0;top:0;width:100%;height:100%;pointer-events:auto" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
        </div>
    </div>
    <div id="section5" class="d-6-section">
        <div class="d-6-youtube-wrapper">
            <div style="padding-top:56.17021276595745%" class="w-embed-youtubevideo d-6-youtube"><iframe src="https://www.youtube.com/embed/xZp7W-VvLlo" frameborder="0" style="position:absolute;left:0;top:0;width:100%;height:100%;pointer-events:auto" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
        </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
export default {
    head() {
        return {
            title: "Sample"
        }
    },
    components: {
    Logo
  }
}
</script>

<style>
.w-embed-youtubevideo {
    width: 100%;
    position: relative;
    padding-bottom: 0px;
    padding-left: 0px;
    padding-right: 0px;
    background-image: url('https://d3e54v103j8qbb.cloudfront.net/static/youtube-placeholder.2b05e7d68d.svg');
    background-size: cover;
    background-position: 50% 50%;
}
.w-embed-youtubevideo:empty {
    min-height: 75px;
    padding-bottom: 56.25%;
}
.d-1-section {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    height: 100vh;
    -webkit-box-pack:center;
    -webkit-justify-content:center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    background-image: url('~assets/hero.jpg');
    background-position: 0px 0px;
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    text-decoration: none;
}
.d-1-menu-wrapper {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    margin-right: 320px;
    margin-left:320px;
    padding-right:15px;
    padding-left: 15px;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
    grid-auto-columns: 1fr;
    grid-column-gap: 16px;
    grid-row-gap: 16px;
    -ms-grid-columns: 1fr 1fr;
    grid-template-columns: 1fr 1fr;
    -ms-grid-rows: auto auto;
    grid-template-rows: auto auto;
    border-radius: 5px;
    background-color: #fff;
    color: #fff;
}
.d-1-menu-item-wrapper {
    display: block;
    margin: 20px 30px;
    -webkit-box-flex: 0;
    -webkit-flex: 0 auto;
    -ms-flex: 0 auto;
    flex: 0 auto;
    text-decoration: none;
}
.d-1-menu-item-text {
    position: relative;
    z-index: 1;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    margin: 0px;
    float: none;
    clear: none;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    -webkit-box-pack: start;
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
    border: 0px none #000;
    font-family: 'Open Sans', sans-serif;
    color: #000;
    font-size: 24px;
    line-height: 38px;
    font-style: normal;
    font-weight: 700;
    text-align: center;
    text-decoration: none;
    text-transform: uppercase;
    white-space: normal;
    -o-object-fit: fill;
    object-fit: fill;
}
.d-1-menu-item-underline {
    position: static;
    display: block;
    height: 10px;
    margin-top: -15px;
    clear: none;
    -webkit-align-self: auto;
    -ms-flex-item-align: auto;
    -ms-grid-row-align: auto;
    align-self: auto;
    -webkit-box-flex: 0;
    -webkit-flex: 0 auto;
    -ms-flex: 0 auto;
    flex: 0 auto;
    background-color: #ffaff9;
    -webkit-transform-origin: 0% 50%;
    -ms-transform-origin: 0% 50%;
    transform-origin: 0% 50%;
    line-height: 20px;
    text-decoration: none;
}
.d-2-section {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    height: 50vh;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    background-color: #deb99f;
    background-image: url('~assets/hero.jpg');
    background-position: 0px 0px;
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
}
.d-3-section {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    height: 50vh;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    background-color: #deb99f;
    background-image: url('~assets/hero.jpg');
    background-position: 0px 0px;
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
}
.d-4-section {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    height: 50vh;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    background-color: #deb99f;
    background-image: url('~assets/hero.jpg');
    background-position: 0px 0px;
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
}
.d-5-section {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    height: 50vh;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    background-color: #deb99f;
    background-image: url('~assets/hero.jpg');
    background-position: 0px 0px;
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
}
.d-6-section {
    position: static;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    height: 50vh;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    background-color: #deb99f;
    background-image: url('~assets/hero.jpg');
    background-position: 0% 0%;
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
}
.youtube {
    position: relative;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    width: 100vh;
    height: 50vh;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
}
.d-2-youtube-wrapper {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;

}
.d-2-youtube {
    width: 50vh;
}
.d-3-youtube {
    width: 50vh;
}
.d-4-youtube {
    width: 50vh;
}
.d-5-youtube {
    width: 50vh;
}
.d-6-youtube {
    width: 50vh;
}




</style>