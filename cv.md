1. Serhii Tokariev
2. Contacts:
   1. **Email:** sergey.v.tokareff@gmail.com
   1. **Telegram:** @sergeytokareff
   1. **Skype:** liamparishowlett
3. I have no work experience. I have the ability to learn quickly and learn new things.
4. My skills: **JavaScript, HTML, CSS, SCSS, Git, Gulp, Webpack.**
5. My example code:

   ```
    const openMenu = function () {
        const burger = document.querySelector('.hamburger');
        const fullScreenMenu = document.querySelector('.fullscreen-menu');
        const body = document.querySelector('body');
        const links = $('.fullscreen-menu__link');

        burger.addEventListener('click', function(e) {
        e.preventDefault();
        burger.classList.toggle('hamburger--active');
        body.classList.toggle('body-active-menu');
        fullScreenMenu.classList.toggle('fullscreen-menu--active');
        });

        $(links).each((link) => {
        links.click(e => {
            $('.fullscreen-menu').removeClass('fullscreen-menu--active');
            $(body).removeClass('body-active-menu');
            $(burger).removeClass('hamburger--active');
        });
        });
    }();
   ```
6. I have not projects.
7. I finished a course from Loftschool 'Web development for beginners'.
8. I have a level of English Beginners.
