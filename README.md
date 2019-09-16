# tabs-on-the-native-JS

Variables.

tab - pass the child class.

info - pass the parent class.

tabContent - we pass the description of the tab.

Example.

let tab = document.querySelectorAll('.info-header-tab'), // pass the child class.
    info = document.querySelector('.info-header'), // pass the parent class.
    tabContent = document.querySelectorAll('.info-tabcontent'); // we pass the description of the tab.

    info.addEventListener('click', function(event) {
        let target = event.target;
        if (target && target.classList.contains('info-header-tab'))  // substitute child class.
