<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Family Speed Wagons</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        /* Header Styles */
        header {
            background: url('https://car-images.bauersecure.com/wp-images/165769/c53m3rs4_115.jpg') no-repeat center center;
            background-size: cover;
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }

        header h1 {
            font-family: 'Impact', 'Arial Black', sans-serif;
            font-size: 50pt;
            margin: 0;
        }

        nav {
            background-color: #333;
            color: white;
        }

        nav ul {
            list-style: none;
            padding: 10px;
            margin: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        /* Divider */
        .divider {
            height: 5px;
            background-color: #007BFF;
            margin: 0;
        }

        /* Section Styles */
        .section {
            padding: 20px;
            margin: 20px auto;
            max-width: 800px;
            background: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        /* Footer Styles */
        footer {
            text-align: center;
            padding: 10px;
            background: #333;
            color: white;
        }

        /* Hide Sections Initially */
        .section-content {
            display: none;
        }

        .section-content.active {
            display: block;
        }

        /* Gallery Image Section */
        .gallery-section {
            padding: 20px;
        }

        .gallery-section h2 {
            text-align: center;
        }

        #gallery img {
            width: 30%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
            margin: 10px;
        }

        .car-model-section {
            margin-bottom: 20px;
        }

        .car-model-section h3 {
            color: #007BFF;
        }

        .car-model-section p {
            font-size: 16px;
            color: #333;
        }

    </style>
</head>
<body>
    <header>
        <h1>Family Speed Wagons</h1>
    </header>
    <nav>
        <ul>
            <li><a href="javascript:void(0);" onclick="showSection('home')">Home</a></li>
            <li><a href="javascript:void(0);" onclick="showSection('about')">About</a></li>
            <li><a href="javascript:void(0);" onclick="showSection('models')">Models</a></li>
            <li><a href="javascript:void(0);" onclick="showSection('gallery')">Gallery</a></li>
            <li><a href="javascript:void(0);" onclick="showSection('contact')">Contact</a></li>
        </ul>
    </nav>
    <div class="divider"></div> <!-- Divider -->

    <!-- Home Section -->
    <section id="home" class="section section-content active">
    <h2>Home</h2>
    <p>Welcome, car enthusiasts, to the world of Family Speed Wagons! Whether you're a seasoned station wagon fan or new to the scene, this website is the perfect place for you. Here, we explore everything about these versatile and performance-driven cars that have captured the hearts of car lovers around the globe. From high-performance models to unique estate builds, you'll find content that caters to all your wagon-related interests.</p>
	<p>For the JS section what i managed to do is i made that when each section gets reloaded it doesn't keep going back to the home page.</p>
    <p>Join us as we delve into a growing community of car aficionados, sharing stories, specs, and personal experiences of the best family-friendly speed wagons!</p>
</section>


    <!-- About Section -->
    <section id="about" class="section section-content">
    <h2>About Us</h2>
    <p>This website is a personal project created by a university student who has a deep admiration for cars, especially station wagons and estate builds. As part of an academic assignment, I developed this site to showcase my passion for these unique vehicles that combine performance, style, and practicality. The goal of this project is not only to demonstrate my web development skills but also to connect with fellow car enthusiasts who share the same appreciation for family wagons.</p>
    <p>From classic models to the latest high-performance variants, I aim to offer an insightful platform for all things related to wagons. Join me on this journey as I continue to build and improve this site, sharing information, opinions, and discussions on the cars that define a niche yet passionate community.</p>
</section>


    <!-- Models Section -->
    <section id="models" class="section section-content">
        <h2>Station Wagon Models Over 170 Horsepower (2017 and Up)</h2>

        <div class="car-model-section">
            <h3>Audi RS 6 Avant</h3>
            <p><strong>Horsepower:</strong> 591 Horsepower</p>
            <p><strong>Details:</strong> The Audi RS6 Avant is a high-performance sports wagon that blends power, luxury, and practicality. Powered by a 4.0-liter twin-turbocharged V8 engine, it produces around 591 horsepower and 590 lb-ft of torque, allowing the car to accelerate from 0 to 60 mph in just about 3.5 seconds. It features Audi's Quattro all-wheel drive system and an 8-speed automatic transmission, ensuring superior handling and stability.

The RS6 Avant is equipped with a dynamic, sporty exterior design, characterized by wide wheel arches, a bold front grille, and aggressive air intakes. Inside, it offers a luxurious and tech-rich cabin with high-quality materials, advanced infotainment systems, and ample space for passengers and cargo. With adaptive suspension and cutting-edge driver assistance features, the RS6 Avant offers both thrilling driving performance and everyday practicality.






</p>
        </div>

        <div class="car-model-section">
            <h3>BMW M3 Competition Touring (2025)</h3>
            <p><strong>Horsepower:</strong> 543 Horsepower</p>
            <p><strong>Details:</strong> The 2025 BMW M3 Competition Wagon, also known as the M3 Touring, brings both enhanced performance and design updates. Powered by a 3.0-liter twin-turbo inline-six engine, it delivers 523 horsepower (up from 503 hp), paired with a robust 650 Nm of torque, allowing the Touring to reach 0-100 km/h in just 3.6 seconds. 

The M3 Competition Wagon is equipped with BMW's M xDrive all-wheel drive system, ensuring improved traction and stability under various driving conditions. A standout feature is the adaptive suspension, which offers multiple settings for personalized ride and handling. 

Styling updates include new LED headlights, redesigned alloy wheels, and a more aggressive front end. Inside, BMW has introduced a fresh three-spoke M leather steering wheel and enhanced multimedia with the latest iDrive 8.5 system. The wagon's sleek yet practical design makes it a direct competitor to rivals like the Audi RS4 Avant, combining track-worthy performance with everyday usability.</p>
        </div>

        <div class="car-model-section">
            <h3>Mercedes-Benz E63s Estate (2025)</h3>
            <p><strong>Horsepower:</strong> 603 horsepower</p>
            <p><strong>Details:</strong> The 2025 Mercedes-AMG E63 S Touring combines power, luxury, and practicality, making it an exceptional superwagon. This high-performance estate boasts a hand-crafted 4.0L V8 biturbo engine producing 603 horsepower and 627 lb-ft of torque. With a 0-60 mph acceleration in just 3.4 seconds, it's as quick as it is versatile. The AMG Performance 4MATIC+ all-wheel drive system ensures exceptional grip and agility, while the AMG SPEEDSHIFT MCT 9-speed sports transmission contributes to seamless power delivery. 

Externally, the E63 S Touring features a dynamic, muscular design with flared wheel arches, a wide front bumper, and an aggressive rear diffuser, all designed to enhance its performance. Inside, it blends luxury with cutting-edge technology, offering a high-tech infotainment system and premium finishes. The E63 S Touring is engineered for both exhilarating driving dynamics and high utility, offering plenty of cargo space for practical use, while maintaining the thrill of a high-performance AMG vehicle.</p>
        </div>
		
		<div class="car-model-section">
            <h3>Mercedes-Benz C63s Estate (2025)</h3>
            <p><strong>Horsepower:</strong> 671 horsepower</p>
            <p><strong>Details:</strong> The 2025 Mercedes-AMG C63 S Estate takes a bold leap into hybrid territory, moving away from the traditional V8 engine to adopt a Formula 1-inspired plug-in hybrid setup. This powertrain combines a 2.0-liter turbocharged inline-four engine with an electric motor, delivering an impressive total output of 671 horsepower and 752 lb-ft of torque. The car accelerates from 0 to 60 mph in just 3.3 seconds, with a top speed of up to 174 mph when equipped with the AMG Performance Package.

The hybrid system includes a 6.1 kWh battery that offers limited electric-only range (around 8–15 km depending on conditions), emphasizing performance over efficiency. Key features include an advanced four-wheel-drive system, adaptive damping, and rear-axle steering, all contributing to agility and control despite the car's increased weight of 4,817 lbs. 

Inside, the C63 S Estate is equipped with AMG-specific drive modes, from Electric and Comfort to Sport+ and Race, allowing drivers to tailor the car's behavior for different scenarios. The hybrid system also supports a drift mode for rear-wheel-drive-style performance. While it sacrifices the raw V8 soundtrack for a refined, hybridized driving experience, the car excels in delivering seamless torque and cutting-edge engineering.</p>
        </div>

        <div class="car-model-section">
            <h3>Porsche Taycan Cross Turismo</h3>
            <p><strong>Horsepower:</strong> 375 to 616 horsepower</p>
            <p><strong>Details:</strong> The Porsche Taycan Cross Turismo is a dynamic and versatile all-electric vehicle, blending high performance with practicality. As an evolution of the Taycan sedan, it features a sporty design, including an elongated roofline and elevated ride height for crossover utility. It offers multiple powertrain options, including models that generate up to 750 horsepower and accelerate from 0 to 60 mph in just 2.7 seconds. The advanced 800-volt battery system ensures rapid charging, achieving 5-80% in about 22.5 minutes, and a range of up to 270 miles, depending on the configuration.

Inside, the cabin combines luxury and technology, featuring premium materials, customizable ambient lighting, and advanced infotainment systems with multi-screen displays, wireless smartphone integration, and robust voice controls. The Taycan Cross Turismo also boasts a spacious cargo area with foldable rear seats, making it ideal for everyday use or adventurous getaways.

This electric crossover maintains Porsche's commitment to high performance and driving dynamics, supported by features like adaptive air suspension, all-wheel drive, and cutting-edge driver assistance systems for enhanced safety and comfort.</p>
        </div>

        <div class="car-model-section">
            <h3>Volvo V60 Polestar (2024)</h3>
            <p><strong>Horsepower:</strong> 415 horsepower</p>
            <p><strong>Details:</strong> The Volvo V60 Polestar Engineered is a high-performance plug-in hybrid wagon that blends Scandinavian design with cutting-edge technology. Powered by a 2.0-liter turbocharged engine and a rear electric motor, it delivers a combined 455 horsepower and 523 lb-ft of torque. This setup allows for all-wheel drive and a brisk 0-60 mph in 4.4 seconds. With an 18.8 kWh battery, it offers up to 41 miles of electric-only range and a total range of 530 miles. 

The interior features luxurious materials, Google-based infotainment, and advanced driver-assistance systems. The sporty aesthetics are complemented by adjustable Ohlins dampers, Brembo brakes, and Polestar-specific styling details. It’s a practical, eco-friendly choice with a dynamic edge</p>
        </div>

        <div class="car-model-section">
            <h3>Subaru Outback XT (2025)</h3>
            <p><strong>Horsepower:</strong> 260 horsepower</p>
            <p><strong>Details:</strong> The Subaru Outback XT is a rugged and practical crossover wagon designed for adventure and everyday functionality. Powered by a turbocharged 2.4-liter flat-four engine, it delivers 260 horsepower and 277 lb-ft of torque, offering smooth performance with standard all-wheel drive. While its CVT can sometimes feel slow to respond, it provides ample power for highway cruising and light off-road use. Fuel economy is respectable, averaging about 25 MPG combined.

Inside, the Outback XT blends utility and comfort. Higher trims, like the Touring XT, feature upscale materials such as Nappa leather, heated and ventilated front seats, and a large 11.6-inch vertically-oriented touchscreen. However, the infotainment system, powered by Subaru's Starlink, can be prone to glitches. Safety is a priority, with Subaru's EyeSight driver assistance suite offering adaptive cruise control, lane centering, and pre-collision braking.

The Outback XT excels as a versatile family car with 32.6 cubic feet of cargo space, expanding to 75.6 cubic feet with the rear seats folded. It’s an ideal choice for road trips or light trail exploration, offering a comfortable and surefooted ride.</p>
        </div>

        <div class="car-model-section">
            <h3>Mini Clubman John Cooper Works</h3>
            <p><strong>Horsepower:</strong> 301 horsepower</p>
            <p><strong>Details:</strong> The 2025 Mini Clubman John Cooper Works (JCW) continues to deliver exhilarating performance and distinctive style, making it a standout in the hot hatch and compact wagon segment. This model is equipped with a 2.0-liter turbocharged four-cylinder engine producing 228 horsepower and 280 lb-ft of torque, paired with Mini's ALL4 all-wheel-drive system. It accelerates from 0 to 60 mph in just 5.9 seconds, showcasing its quick and nimble nature.

The exterior design retains Mini's classic silhouette, enhanced with JCW-specific details such as a bold grille, aerodynamic accents, and optional contrasting roof colors. Inside, the cabin blends retro charm with modern updates, including a 9-inch circular OLED infotainment system that supports Apple CarPlay and Android Auto. Premium materials, ambient lighting, and sport seats with improved bolstering make the interior as engaging as its performance.

With its dynamic handling, advanced safety features like adaptive cruise control and lane-keeping assist, and enhanced comfort amenities, the 2025 Mini Clubman JCW is both a practical and thrilling option for those seeking a versatile yet sporty ride.</p>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="section section-content">
    <div class="gallery-section">
        <h2>Gallery</h2>

        <!-- Audi RS 6 Avant Gallery -->
        <div class="car-gallery">
            <h3>Audi RS 6 Avant</h3>
            <div class="car-images">
                <img src="https://hips.hearstapps.com/hmg-prod/images/2025-audi-rs6-avant-gt-motion-103-65bbc522aae10.jpg?crop=0.488xw:0.366xh;0.158xw,0.395xh&resize=1200:*">
                <img src="https://hips.hearstapps.com/hmg-prod/images/2025-audi-rs6-avant-gt-motion-101-65bbc523b0d59.jpg?crop=0.545xw:0.499xh;0.280xw,0.352xh&resize=980:*">
                <img src="https://hips.hearstapps.com/hmg-prod/images/2025-audi-rs6-avant-gt-interior-detail-101-65bbc41a04e77.jpg">
            </div>
        </div>

        <!-- BMW M3 Competition Touring Gallery -->
        <div class="car-gallery">
            <h3>BMW M3 Competition Touring (2025)</h3>
            <div class="car-images">
                <img src="https://www.auto-data.net/images/f95/BMW-M3-Touring-G81-LCI-facelift-2024.jpg">
                <img src="https://www.bmw-m.com/content/dam/bmw/marketBMW_M/www_bmw-m_com/all-models/m-automobile/m3-touring/2024/bmw-m3-touring-m-xdrive-hd-15.jpg">
                <img src="https://www.autocar.co.uk/sites/autocar.co.uk/files/bmw-m3-touring-review-202306-interior.jpg">
            </div>
        </div>

        <!-- Mercedes-Benz E63s Estate Gallery -->
        <div class="car-gallery">
            <h3>Mercedes-Benz E63s Estate (2025)</h3>
            <div class="car-images">
                <img src="https://hips.hearstapps.com/hmg-prod/images/2024-mercedes-benz-e-class-wagon-106-6491b8f7643e5.jpg?crop=0.553xw:0.467xh;0.250xw,0.319xh&resize=640:*">
                <img src="https://www.motortrend.com/uploads/2023/07/009-2024-mercedes-benz-e-class-wagon-euro-e1690381140387.jpg?w=768&width=768&q=75&format=webp">
                <img src="https://www.motortrend.com/uploads/2023/02/2024-Mercedes-Benz-E-Class-Interior-11-scaled.jpg">
            </div>
        </div>

		<!-- Mercedes-Benz C63s Estate Gallery -->
        <div class="car-gallery">
            <h3>Mercedes-Benz C63s Estate</h3>
            <div class="car-images">
                <img src="https://images.pistonheads.com/nimg/48728/blobid0.jpg" alt="Mercedes-Benz C63s Estate">
                <img src="https://jesmb.de/wp-content/uploads/2022/09/mercedes-c63e-9.jpg" alt="Mercedes-Benz C63s Estate Side View">
                <img src="https://media.drive.com.au/obj/tx_q:50,rs:auto:1920:1080:1/driveau/upload/cms/uploads/kyusivwe7vmqaw93xz3b" alt="Mercedes-Benz C63s Estate Interior">
            </div>
        </div>

        <!-- Additional Car Galleries (Add more car sections here) -->
    </div>
	<div class="car-gallery">
            <h3>More pictures coming soon...</h3>
</section>
        <!-- Additional Car Galleries -->
        <!-- Add similar blocks for other cars -->

    </div>
</section>


    <!-- Contact Section -->
    <section id="contact" class="section section-content">
        <h2>Contact</h2>
        <p>Have any inquiries? Reach us at <a href="mailto:s23229018@al.tiu.ac.jp">s23229018@al.tiu.ac.jp</a>.</p>
    </section>

    <footer>
        <p>&copy; 2024 Josh Xander Avindra. 23229018.</p>
    </footer>

   <script>
    // Show the selected section and save it to localStorage
    function showSection(sectionId) {
        // Hide all sections
        const sections = document.querySelectorAll('.section-content');
        sections.forEach(section => {
            section.classList.remove('active');
        });

        // Show the selected section
        const selectedSection = document.getElementById(sectionId);
        selectedSection.classList.add('active');

        // Save the selected section to localStorage
        localStorage.setItem('activeSection', sectionId);
    }

    // Load the active section from localStorage on page load
    window.onload = function () {
        const savedSection = localStorage.getItem('activeSection') || 'home'; // Default to 'home'
        showSection(savedSection);
    };
</script>

