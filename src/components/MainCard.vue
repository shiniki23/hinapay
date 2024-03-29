<template>
    <div class="wrapper">
        <div class="main-container">
            <!-- Profile Section -->
            <div class="container-one">
                <div class="profile">
                    <img src="https://scontent.fceb3-1.fna.fbcdn.net/v/t39.30808-6/404235950_685336877032871_71300209099970083_n.jpg?_nc_cat=100&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeE5EAMVFG3QVXXdLc6n1iL6LxsqnRzu9wcvGyqdHO73B1WC5VJD628tSWa5DXHrRVRwpxMSvmR6FNxQIUQZ412P&_nc_ohc=W6ukgF6OOHwAX-Q6RoI&_nc_ht=scontent.fceb3-1.fna&oh=00_AfCYGjSTsdqBocAPUgwE0FjUQseKK0117upOZUDPgGaQUg&oe=660C8668" alt="Stefano Suan Profile Picture">
                    <h3>NIKKI HINACAY</h3>
                    <p>SOFTWARE DESIGNER</p>
                </div>
                <!-- Social Links -->
                <div class="social-link">
                    <div class="link">
                        <a href="https://github.com/join/recommended_plan" target="_blank">
                            <img src="../assets/nikki.jpg" alt="GitHub">
                            <h2>GITHUB</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.facebook.com/nikki.hinacay" target="_blank"> 
                            <img src="../assets/facebook.jpg" alt="Facebook">
                            <h2>FACEBOOK</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.instagram.com/23spetsnaz/" target="_blank">
                            <img src="../assets/instagram.jpg" alt="Instagram">
                            <h2>INSTAGRAM</h2>
                        </a>
                    </div>
                </div>
            </div>
            <!-- About Me Section -->
            <div class="container-two">
                <div class="about-me">
                    <h1>About Me</h1>
                    <p>Nikki Hinacay, a 23-year-old resident of Sudtonggan Basak LLC, is an optimistic and resilient software developer.</p>
                    <!-- Language Section -->
                    <div class="language-section">
                        <h1>LANGUAGE USES</h1>
                        <div class="logos">
                            <img src="../assets/japan.jpg" alt="Japanese">
                            <img src="../assets/english.jpg" alt="English">
                            <img src="../assets/bisaya.jpg" alt="Bisaya">
                        </div>
                        <!-- Contact Section -->
                        <div class="contact-section">
                            <div class="project-button">
                                <a href="tel:09276553374">Contact Number: 09276553374</a>
                            </div>
                            <div class="project-button">
                                <a href="mailto:nikkihinacay25@gmail.com">EMAIL: nikkihinacay@gmail.com</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
/* General Styles */
body {
    font-family: 'Roboto', sans-serif;
    background-color: #e9ecef;
}

.wrapper {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: linear-gradient(45deg, #667eea, #764ba2);
}

img {
    height: 100px;
    border-radius: 10px;
}

/* Main Container Styles */
.main-container {
    display: flex;
    flex-direction: column;
    background-color: #fff;
    border-radius: 15px;
    width: 90%;
    max-width: 900px;
    box-shadow: 0px 15px 30px rgba(0, 0, 0, 0.1);
    padding: 50px;
}

/* Container One Styles */
.container-one {
    background-color: #f8f9fa;
    padding: 40px;
    border-radius: 20px;
    margin-bottom: 40px;
    box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.1);
}

.profile img {
    height: 180px;
    border: 8px solid #fff;
    box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.1);
}

.link a {
    text-decoration: none;
    color: #495057;
    font-size: 20px;
    margin-bottom: 25px;
    display: flex;
    align-items: center;
    transition: 0.3s ease;
}

.link a:hover {
    color: #6c757d;
}

.link img {
    height: 60px;
    margin-right: 20px;
    border-radius: 15px;
    transition: 0.3s ease;
}

.link img:hover {
    transform: scale(1.05);
}

/* Container Two Styles */
.container-two {
    background-color: #f8f9fa;
    padding: 40px;
    border-radius: 20px;
    box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.1);
}

.about-me {
    text-align: center;
    margin-bottom: 50px;
}

.language-section h1 {
    margin-bottom: 30px;
    font-size: 26px;
    color: #343a40;
}

.logos img {
    height: 60px;
    margin-right: 20px;
    border-radius: 50%;
    transition: 0.3s ease;
}

.logos img:hover {
    transform: scale(1.05);
}

.contact-section {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.project-button {
    background-color: #28a745;
    color: #fff;
    border-radius: 30px;
    padding: 18px 28px;
    margin: 15px;
    box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.1);
    transition: 0.3s ease;
}

.project-button:hover {
    background-color: #218838;
}

.project-button a {
    color: #fff;
    text-decoration: none;
    font-size: 20px;
}
</style>
