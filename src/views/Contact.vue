<template>
    <div class="container-fluid">
        <div class="row">
        <div class="col">
            <h1 id="contact">Contact Me</h1>
            <div class="social">
                        <i class="fa fa-facebook"></i>
                        <i class="fa fa-github"></i>
                        <i class="fa fa-instagram"></i>
                        <i class="fa fa-linkedin"></i>
                    </div>
                    <p class="text-light mt-4">If you have something you want to discuss, contact me or leave your details.</p>
                    <form class>
                        <input type="text" name="name" placeholder=" your name">
                        <input type="email" name="email" placeholder="your email">
                        <input type="tel" name="phone" placeholder="your phone">
                        <input type="text" name="subject" placeholder="subject">
                        <textarea placeholder="your message"></textarea>
                        <button>send</button>
                    </form>
                </div>
                <div class="col">
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3308.2675928504113!2d18.490509915821583!3d-33.985659832565865!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1dcc433bedd50e81%3A0x9c746d268c8e0ad9!2sLife%20Choices!5e0!3m2!1sen!2sza!4v1658296857775!5m2!1sen!2sza" width="600" height="600" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                </div>
                </div>
    </div>
</template>

<script>
export default {
    
}
</script>
<style scoped>
.container-fluid {
    text-align: center;

}
#contact {
    color: white;
    margin-top: 150px;
    text-decoration: underline 3px;
    text-decoration-color: blue;
}
.container-fluid .social {
    margin-top: 40px;
    display: flex;
    justify-content: center; 
}
.container-fluid .social i {
    width: 55px;
    color: blue;
    height: 55px;
    border-radius: 50%;
    border: 1px solid blue;
    line-height: 55px;
    font-size: 25px;
    transition: .5s ease;
    margin-right: 20px;
}
.container-fluid .social i:last-child {
    margin-right: 0;
}
.container-fluid .social i:hover {
    border-color: blue;
    box-shadow: 0 0 20px blue;
    transform: scale(1.2)
}
.container-fluid form {
    width: 80%;
    margin: 60px auto;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}
.container-fluid form input {
    height: 40px;
    background-color: transparent;
    padding: 5px 0px;
    border: 0;
    border-bottom: 1px solid #ccc;
    margin-bottom: 30px;
    color: #fff;
}
.container-fluid form textarea {
    background-color: transparent;
    padding: 5px 0px;
    border: 0;
    border-bottom: 1px solid #ccc;
    margin-bottom: 30px;
    height: 40px;
    width: 100%;
  color: #fff;
}
.container-fluid form input::-webkit-input-placeholder,
.container-fluid form textarea::-webkit-input-placeholder {
    color: blue;
    text-transform: capitalize;
}
.container-fluid form [name="name"],
.container-fluid form [name="email"],
.container-fluid form [name="phone"] {
    width: 31%;
}
.container-fluid form [name="subject"] {
    width: 100%;
    margin-bottom: 80px;
}
.container-fluid form button {
    background-color: transparent;
    padding: 10px 0;
    width: 100%;
    border: 1px solid blue;
    color: blue;
    text-transform: uppercase;
    overflow: hidden;
}
.container-fluid form button:hover {
    color: blue;
    border-color: blue;
    box-shadow: 0 0 20px blue;
}
iframe {
    margin-top: 150px;
}
</style>