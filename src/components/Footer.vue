<template>
       <div class="footer-basic">
      <footer>
          <ul class="list-inline">
              <li class="list-inline-item"><router-link to="/">Home</router-link></li>
              <li class="list-inline-item"><router-link to="/About">About</router-link></li>
              <li class="list-inline-item"><router-link to="/Resume">Projects</router-link></li>
              <li class="list-inline-item"><router-link to="/Projects">Resume</router-link></li>
              <li class="list-inline-item"><router-link to="/Contact">Contact</router-link></li>
          </ul>
          <p class="copyright">Ashton Abrahams © 2022</p>
      </footer>
  </div> 
</template>
<script>
export default {
    components: {

 }
}
</script>
<style>
.footer-basic {
display: flex;
justify-content: center;
padding-top: 25px;   
color:#4b4c4d;
}
.footer-basic ul {
padding:0;
list-style:none;
text-align:center;
font-size:18px;
line-height:1.6;
margin-bottom:0;
}
.footer-basic li {
padding:0 10px;
}
.footer-basic ul a {
color:inherit;
text-decoration:none;
opacity:0.8;
}
.footer-basic ul a:hover {
opacity:1;
color: white;
}

.footer-basic .copyright {
text-align:center;
font-size:13px;
color:#aaa;
margin-bottom:0;
}    
</style>