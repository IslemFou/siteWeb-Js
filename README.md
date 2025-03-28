// active element js
const URL = window.location.href;
  navMenu = document.querySelectorAll(".nav-link"); // NodeList(6) [a.nav-link, a.nav-link, a.nav-link, a.nav-link, a.nav-link, a.nav-link]
for (let i = 0; i < navMenu.length; i++) {
    if (navMenu[i].getAttribute("href") === URL) {
        navMenu[i].classList.add("navColor");
    }
}

// CSS
 .navColor
{
    color : #bf0cd3 !important;
    fill: #bf0cd3 !important;
}

