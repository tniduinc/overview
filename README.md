# TNIDU Inc.

## About TNIDU Inc.

![TNIDU Inc.](./logo.png)

TNIDU Inc. is a leading company specializing in software development, web development, graphic design, marketing, and game development. Our team of experts is dedicated to delivering high-quality solutions that meet the unique needs of our clients. We pride ourselves on our innovative approach and commitment to excellence.

## Animations and Beautiful UI

At TNIDU Inc., we believe that a beautiful user interface and smooth animations are key to creating an engaging user experience. Our design team focuses on crafting visually stunning interfaces that are not only aesthetically pleasing but also intuitive and user-friendly. We use the latest technologies and design principles to ensure that our animations are seamless and enhance the overall user experience.

### Key Features
- **Smooth Transitions:** We implement smooth transitions to provide a fluid and enjoyable user experience.
- **Interactive Elements:** Our designs include interactive elements that respond to user actions, making the interface more engaging.
- **Consistent Design Language:** We maintain a consistent design language across all platforms to ensure a cohesive user experience.
- **Performance Optimization:** Our animations are optimized for performance, ensuring that they run smoothly on all devices.

Let us help you create a beautiful and engaging user interface that will captivate your audience and set your product apart from the competition.

## Live Demo

To see our animations and beautiful UI in action, check out the live demo below:

```html
<div id="animation-demo">
    <img src="./demo-image.png" alt="Demo Image" class="animated-image">
</div>

<script src="./animation.js"></script>

<style>
    #animation-demo {
        text-align: center;
        margin: 20px 0;
    }

    .animated-image {
        width: 300px;
        height: auto;
        transition: transform 0.5s ease-in-out;
    }

    .animated-image:hover {
        transform: scale(1.1);
    }
</style>
```

## Our Services with Animations

<div class="service" id="software-development">
    <h3>Software Development</h3>
    <p>We create custom software solutions tailored to your business needs.</p>
</div>

<div class="service" id="web-development">
    <h3>Web Development</h3>
    <p>Our team builds responsive and modern websites to help you stand out online.</p>
</div>

<div class="service" id="graphic-design">
    <h3>Graphic Design</h3>
    <p>We provide creative graphic design services to make your brand visually appealing.</p>
</div>

<div class="service" id="marketing">
    <h3>Marketing</h3>
    <p>Our marketing strategies will help you reach a wider audience and grow your business.</p>
</div>

<div class="service" id="game-development">
    <h3>Game Development</h3>
    <p>We develop engaging and immersive games for various platforms.</p>
</div>

<script>
    document.querySelectorAll('.service').forEach(service => {
        service.style.opacity = 0;
        service.style.transform = 'translateY(20px)';
        service.style.transition = 'opacity 0.6s ease-out, transform 0.6s ease-out';
    });

    window.addEventListener('scroll', () => {
        document.querySelectorAll('.service').forEach(service => {
            const rect = service.getBoundingClientRect();
            if (rect.top < window.innerHeight) {
                service.style.opacity = 1;
                service.style.transform = 'translateY(0)';
            }
        });
    });
</script>

<style>
    .service {
        margin: 20px 0;
        padding: 20px;
        border: 1px solid #ddd;
        border-radius: 8px;
        background-color: #f9f9f9;
    }
    .service p {
        margin: 10px 0;
    }

    .service:hover {
        background-color: #e0f7fa;
        transform: scale(1.02);
        transition: background-color 0.3s ease, transform 0.3s ease;
    }
    .service h3 {
        margin-top: 0;
    }
</style>

### Software Development
We create custom software solutions tailored to your business needs.

### Web Development
Our team builds responsive and modern websites to help you stand out online.

### Graphic Design
We provide creative graphic design services to make your brand visually appealing.

### Marketing
Our marketing strategies will help you reach a wider audience and grow your business.

### Game Development
We develop engaging and immersive games for various platforms. TNIDU Inc.

