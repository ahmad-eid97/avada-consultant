<template>
    <footer>
        <div class="widgets">
            <div class="row mx-0 justify-content-center">
                <div class="col-sm-6 col-md-3 text-start">
                    <div class="logo">
                        <img src="https://avada.theme-fusion.com/marketing-consultant/wp-content/uploads/sites/142/2021/04/avada-marketing-consultant-logo.svg" alt="">
                    </div>
                    <p>
                        Grow Your Online Business Strategically, and Improve Customer Retention.
                    </p>
                    <div class="col-auto socials">
                    <a href="#" >
                        <font-awesome-icon icon="fa-brands fa-facebook-f" />
                    </a>
                    <a href="#" >
                        <font-awesome-icon icon="fa-brands fa-twitter" />
                    </a>
                    <a href="#" >
                        <font-awesome-icon icon="fa-brands fa-youtube" />           
                    </a>
                    <a href="#" >
                        <font-awesome-icon icon="fa-brands fa-instagram" />          
                    </a>
                    <a href="#" >
                        <font-awesome-icon icon="fa-brands fa-linkedin-in" />          
                    </a>
                    <a href="#" >
                        <font-awesome-icon icon="fa-brands fa-tiktok" />          
                    </a>
                </div>
                </div>
                <div class="col-sm-6 col-md-3  text-start">
                    <h5>Services</h5>
                    <ul>
                        <li>
                           <a href="#" >Marketing Plan</a>
                        </li>
                        <li>
                           <a href="#" >Marketing Plan</a>
                        </li>
                        <li>
                           <a href="#" >Marketing Plan</a>
                        </li>
                        <li>
                           <a href="#" >Marketing Plan</a>
                        </li>
                        <li>
                           <a href="#" >Marketing Plan</a>
                        </li>
                    </ul>
                </div>
                <div class="col-sm-6 col-md-3  text-start">
                    <h5>contact us today</h5>
                    <ul>
                        <li>
                           <a href="#" >Marketing Plan</a>
                        </li>
                        <li>
                           <a href="#" >Marketing Plan</a>
                        </li>
                        <li>
                           <a href="#" >Marketing Plan</a>
                        </li>
                        <li>
                           <a href="#" >Marketing Plan</a>
                        </li>
                        <li>
                           <a href="#" >Marketing Plan</a>
                        </li>
                    </ul>
                </div>
                <div class="col-sm-6 col-md-3  text-start">
                    <h5>Company</h5>
                    <ul>
                        <li>
                           <a href="#" >Marketing Plan</a>
                        </li>
                        <li>
                           <a href="#" >Marketing Plan</a>
                        </li>
                        <li>
                           <a href="#" >Marketing Plan</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="copyrights">
            <div class="row mx-0 align-items-center justify-content-between">
                <div class="col-auto">
                    ?? 2020 ??? Avada Consultant ??? Powered by WordPress
                </div>
                <div class="col-auto">
                    Call Us (555) 802-1234
                </div>
                <div class="col-auto">
                    info@yourcompany.com
                </div>
            </div>
        </div>
  </footer>
</template>

<script>


export default {
    name: 'AppFooter',
    components: {},
    data() {
        return {
            
        }
    },
    methods : {
        
    }
}
</script>
<style>
    .text-start {
        margin-bottom: 20px;
    }

    footer .widgets {
        padding-bottom: 20px;
        padding-left: 32px;
        padding-right: 32px;
        padding-top: 80px
    }
    footer .widgets .logo {
        margin-bottom: 20px;
        text-align: start;
    }
    footer .widgets p {
        font-size: 32px;
        font-weight: 500;
        letter-spacing: -0.96px;
        line-height: 40.3167px;
        text-align: start;
    }
    footer .widgets .socials a{
        margin: 10px;
        font-size: 20px;
        text-decoration: none;
        color: #000;
    }
    footer h5 {
        font-weight: 800;
        margin: 0 0 20px;
        font-weight: 500;
        letter-spacing: -0.32px;
        line-height: 28px;
        color: rgb(0, 0, 0);
        font-size: 20px;

    }
    footer ul {
        list-style: none;
        padding: 0;
    }
    footer li {
        font-size: 20px;
        font-weight: 400;
        line-height: 32px;
        margin-bottom: 12px;
    }
    footer li a{
        text-decoration: none;
        color: #000;
    }
    footer li a:hover{
        text-decoration: none;
        color: rgb(243, 95, 18);
    }
    footer .widgets img {
        max-width: 100%;
    }
    .copyrights {
        padding-top: 10px;
        margin-top: 0px;
        padding-right: 6%;
        padding-bottom: 10px;
        margin-bottom: 0px;
        padding-left: 6%;
    }
    .copyrights p {
        color:rgb(116, 116, 116);
        font-size: 12px;
        font-weight: 600;
        text-align: start;
        margin: 15px 0;
    }
    .copyrights p a{
        color: rgb(166, 166, 166);
        font-size: 12px;
        font-weight: 600;
        text-decoration: none;
    }
    
</style>