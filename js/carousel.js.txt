// carousel.js

// Wait for the document to be ready and then initialize the carousel
document.addEventListener('DOMContentLoaded', function () {
    var carouselElement = document.querySelector('#carouselExample');
    var carousel = new bootstrap.Carousel(carouselElement, {
        interval: 2000, // Auto-slide every 2 seconds (2000 ms)
        wrap: true       // Allow carousel to cycle infinitely
    });
});
