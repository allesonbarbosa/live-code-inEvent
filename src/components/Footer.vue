<template>
    <div id="container-footer">
        <div id="content-footer">
            <img src="../assets/InEvent-Logo-original.svg" alt="logo-inevent" id="logo-inevent">
            <div id="company-links">
                <ul>
                    <li><b>Company</b></li>
                    <li><a href="">About</a></li>
                    <li><a href="">Solutions</a></li>
                    <li><a href="">Library</a></li>
                    <li><a href="">Cases</a></li>
                    <li><a href="">Plans</a></li>
                    <li><a href="">Support</a></li>
                </ul>
            </div>
            <div id="solutions-links">
                <ul>
                    <li><b>Solutions</b></li>
                    <li><a href="">Start</a></li>
                    <li><a href="">Live</a></li>
                    <li><a href="">Registration</a></li>
                    <li><a href="">Compliance</a></li>
                    <li><a href="">Hospitality</a></li>
                    <li><a href="">Pass</a></li>
                </ul>
            </div>
            <div id="more-links">
                <ul>
                    <li><b>More</b></li>
                    <li><a href="">Start</a></li>
                    <li><a href="">EventMarket</a></li>
                    <li><a href="">Partnership</a></li>
                    <li><a href="">Eventhub</a></li>
                    <li><a href="">Global</a></li>
                    <li><a href="">Security</a></li>
                </ul>
            </div>
            <div id="other-links">
                <ul>
                    <li><a href="">Login</a></li>
                    <li><a href="">Blog</a></li>
                    <li><a href="">FAQ</a></li>
                    <li><a href="">Jobs</a></li>
                    <li><a href="">API Docs</a></li>
                    <li><a href="">Integrations</a></li>
                    <li><a href="">System Status</a></li>
                </ul>
            </div>
            <div id="icons-social-links">
                <a href="">
                    <img src="https://inevent.com/images/social-media/linkedin-gray.svg" alt="logo-linkedin">
                </a>
                <a href="">
                    <img src="https://inevent.com/images/social-media/instagram-gray.svg" alt="logo-instagram">
                </a>
                <a href="">
                    <img src="https://inevent.com/images/social-media/twitter-gray.svg" alt="logo-twitter">
                </a>
                <a href="">
                    <img id="youtube-logo" src="https://inevent.com/images/social-media/youtube-ico.svg" alt="logo-youtube">
                </a>
            </div>
        </div>
        <div id="content-copyright">
            <p> © InEvent, Inc.2022</p>
        </div>
        <div id="links-footer">
            <a href="">Terms of Service</a>
            <span class="divider">
                •
            </span>
            <a href="">Privacy Policy</a>
            <span class="divider">
                •
            </span>
            <a href="">Cookie Policy</a>
            <span class="divider">
                •
            </span>
            <a href="">GDPR</a>
            <span class="divider">
                •
            </span>
            <a href="">Business Continuity Plan</a>
            <span class="divider">
                •
            </span>
            <a href="">sales@inevent.com</a>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style scoped>
    #container-footer{
        width: 100vw;
        height: 350px;
        background-color: #F9F9F9;
        padding-top: 35px;
        display: flex;
        flex-direction: column;
        align-items: center;
        border-top: 2px solid #CCCCCC;
        gap: 40px;
    }
    #content-footer{
        width: 80%;
        display: flex;
        flex-direction: row;
        align-items: flex-start;
        justify-content: space-around;
    }
    a{
        color: #333333;
        font-size: 17px;
    }
    b{
        font-size: 19px;
        margin-bottom: 15px;
        text-transform: uppercase;
    }
    li{
        margin: 10px 0;
    }
    #youtube-logo{
        background-color: #7F8C8D;
        width: 22px;
        border-radius: 50%;
    }
    #links-footer{
        display: flex;
        align-items: center;
        gap: 10px;
    }
</style>