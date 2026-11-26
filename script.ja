// LIPX Blog - JavaScript

document.addEventListener("DOMContentLoaded", function () {

    // MOBILE NAVIGATION MENU
    const menuToggle = document.querySelector(".menu-toggle");
    const navigation = document.querySelector(".primary-nav");

    if (menuToggle && navigation) {

        menuToggle.addEventListener("click", function () {
            navigation.classList.toggle("open");

            // Update the menu button state
            const isOpen = navigation.classList.contains("open");
            menuToggle.setAttribute("aria-expanded", isOpen);
        });

        // Close the menu after clicking a navigation link
        const navLinks = navigation.querySelectorAll("a");

        navLinks.forEach(function (link) {
            link.addEventListener("click", function () {
                navigation.classList.remove("open");
                menuToggle.setAttribute("aria-expanded", "false");
            });
        });
    }


    // BLOG CATEGORY FILTER
    const categoryButtons = document.querySelectorAll(".category-button");
    const storyCards = document.querySelectorAll(".story-card");

    categoryButtons.forEach(function (button) {

        button.addEventListener("click", function () {

            // Get the selected category
            const selectedCategory = button.textContent
                .trim()
                .toLowerCase();

            // Highlight the selected button
            categoryButtons.forEach(function (btn) {
                btn.classList.remove("selected");
            });

            button.classList.add("selected");

            // Show or hide blog posts
            storyCards.forEach(function (card) {

                const categoryElement = card.querySelector(".post-category");

                const cardCategory = (
                    card.dataset.category ||
                    (categoryElement ? categoryElement.textContent : "")
                ).trim().toLowerCase();

                if (
                    selectedCategory === "all" ||
                    selectedCategory === "all posts" ||
                    cardCategory.includes(selectedCategory) ||
                    (selectedCategory.includes("everyday") &&
                     cardCategory.includes("personal"))
                ) {
                    card.style.display = "";
                } else {
                    card.style.display = "none";
                }

            });

        });

    });

});



Before you submit
