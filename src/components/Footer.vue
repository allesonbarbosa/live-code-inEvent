<template>
    <div id="container-footer">
        <div id="content-footer">
            <img src="../assets/InEvent-Logo-original.svg" alt="logo-inevent" id="logo-inevent">
            <div id="company-links">
                <ul>
                    <li><b>Company</b></li>
                    <li><a href="https://inevent.com/en/about.php">About</a></li>
                    <li><a href="https://inevent.com/en/about.php">Solutions</a></li>
                    <li><a href="https://inevent.com/en/library.php">Library</a></li>
                    <li><a href="https://inevent.com/en/case-studies.php">Cases</a></li>
                    <li><a href="https://inevent.com/en/pricing.php">Plans</a></li>
                    <li><a href="https://inevent.com/en/support.php">Support</a></li>
                </ul>
            </div>
            <div id="solutions-links">
                <ul>
                    <li><b>Solutions</b></li>
                    <li><a href="https://inevent.com/en/start-data-management.php">Start</a></li>
                    <li><a href="https://inevent.com/en/live-event-mobile-app.php">Live</a></li>
                    <li><a href="https://inevent.com/en/registration-forms-rsvp-invites.php">Registration</a></li>
                    <li><a href="https://inevent.com/en/management-budget-briefing-suppliers.php">Compliance</a></li>
                    <li><a href="https://inevent.com/en/hospitality-logistics-roomlist.php">Hospitality</a></li>
                    <li><a href="https://inevent.com/en/pass-event-quick-checkin.php">Pass</a></li>
                </ul>
            </div>
            <div id="more-links">
                <ul>
                    <li><b>More</b></li>
                    <li><a href="https://inevent.com/en/start-data-management.php">Start</a></li>
                    <li><a href="https://inevent.com/en/eventmarket.php">EventMarket</a></li>
                    <li><a href="https://inevent.com/en/referral-partnerships.php">Partnership</a></li>
                    <li><a href="https://inevent.com/en/event-hub-inevent-data-platform.php">Eventhub</a></li>
                    <li><a href="https://inevent.com/en/global-international-worldwide-software.php">Global</a></li>
                    <li><a href="https://inevent.com/en/security-data-privacy.php">Security</a></li>
                </ul>
            </div>
            <div id="other-links">
                <ul>
                    <li><a href="https://inevent.com/en/company.php">Login</a></li>
                    <li><a href="https://inevent.com/blog">Blog</a></li>
                    <li><a href="https://faq.inevent.com/l/en">FAQ</a></li>
                    <li><a href="https://inevent.com/en/work-with-us.php">Jobs</a></li>
                    <li><a href="https://inevent.com/en/developer.php">API Docs</a></li>
                    <li><a href="https://inevent.com/en/partners-integrations.php">Integrations</a></li>
                    <li><a href="https://inevent.com/en/trust.php">System Status</a></li>
                </ul>
            </div>
            <div id="icons-social-links">
                <a href="https://www.linkedin.com/company/ineventapp" target="_blank">
                    <img src="https://inevent.com/images/social-media/linkedin-gray.svg" alt="logo-linkedin">
                </a>
                <a href="https://www.instagram.com/ineventapp" target="_blank">
                    <img src="https://inevent.com/images/social-media/instagram-gray.svg" alt="logo-instagram">
                </a>
                <a href="https://twitter.com/ineventapp" target="_blank">
                    <img src="https://inevent.com/images/social-media/twitter-gray.svg" alt="logo-twitter">
                </a>
                <a href="https://www.youtube.com/channel/UC3C2GrWpjXVjG21Arrtwi4Q" target="_blank">
                    <img id="youtube-logo" src="https://inevent.com/images/social-media/youtube-ico.svg" alt="logo-youtube">
                </a>
            </div>
        </div>
        <div id="content-copyright">
            <p> © InEvent, Inc.2022</p>
        </div>
        <div id="links-footer">
            <a href="https://inevent.com/en/terms.php">Terms of Service</a>
            <span class="divider">
                •
            </span>
            <a href="https://inevent.com/en/privacy.php">Privacy Policy</a>
            <span class="divider">
                •
            </span>
            <a href="https://inevent.com/en/cookies.php">Cookie Policy</a>
            <span class="divider">
                •
            </span>
            <a href="https://inevent.com/en/gdpr-general-data-protection-regulation.php">GDPR</a>
            <span class="divider">
                •
            </span>
            <a href="https://inevent.com/en/business-continuity-plan.php">Business Continuity Plan</a>
            <span class="divider">
                •
            </span>
            <a href="mailto:sales@inevent.com">sales@inevent.com</a>
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