<template>
    <footer class="footer">
        <div class="container">
            <div class="row">
                <div class="footer-col">
                    <img src="@/assets/logo-pens.png" class="img-footer">
                    <div class="company-name">
                        <p><b>DEPARTEMEN TEKNIK INFORMATIKA<br>DAN KOMPUTER POLITEKNIK<br>ELEKTRONIKA NEGERI SURABAYA</b></p>
                    </div>
                    <div class="company-address">
                        <p>Jl. Raya ITS, Sukolilo, Kota Surabaya, 60111</p>
                    </div>
                    <div class="company-contact">
                        <p><b>Phone</b> : 098<br><b>Email</b> : @pens.ac.id</p>
                    </div>
                </div>
                <div class="footer-col">
                    <form class="responsive-footer-form">
                        <div class="form-wrapper">
                            <div class="form">
                                <div class="form-item">
                                    <h4>Pesan</h4>
                                    <div class="footer-input">
                                        <input type="text" />
                                    </div>
                                    <textarea class="fill-vertical-space"></textarea>
                                </div>
                                <div class="kirim-pesan">
                                    <a href="#" class="button-kirim-pesan"><b>KIRIM PESAN</b></a>
                                </div>
                            </div>
                        </div> 
                    </form>       
                </div>
                <div class="footer-col">
                    <h4>Media Sosial</h4>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fa-brands fa-youtube"></i></a>
                    </div>
                </div>
            </div>
        </div>
  </footer>
</template>

<script>
export default {
    name : 'FooterApp'
}
</script>

<style>
*{
	margin:0;
	padding:0;
	box-sizing: border-box;
    font-family: 'Roboto', sans-serif;
}
.container{
	max-width: 1170px;
	margin:auto;
}
.row{
	display: flex;
	flex-wrap: wrap;
}
.footer{
	background-color: rgb(20, 72, 122);
    padding: 70px 0;
}
.footer-col{
   width: 25%;
   padding: 0 15px;
}

.company-name {
    padding-top: 20px;
}

.company-name p {
    color: #ffffff;
    font-size: 14px;
}

.company-address p {
    color: #ffffff;
    font-size: 14px;
}

.company-contact p {
    color: #ffffff;
    font-size: 14px;
}

.button-kirim-pesan {
  background-color: #F3C903;
  border: none;
  color: #14487A;
  padding: 5px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}

.footer-col h4{
	font-size: 18px;
	color: #F3C903;
	text-transform: capitalize;
	margin-bottom: 35px;
	font-weight: 500;
	position: relative;
}

.footer-col .social-links a{
	display: inline-block;
	height: 40px;
	width: 40px;
	background-color: rgba(255,255,255,0.2);
	margin:0 10px 10px 0;
	text-align: center;
	line-height: 40px;
	border-radius: 50%;
	color: #ffffff;
	transition: all 0.5s ease;
}

.footer-input {
    padding-bottom: 20px;
}

.footer-col .social-links a:hover{
	color: #24262b;
	background-color: #ffffff;
}

.form-wrapper { 
    display:flex;
    justify-content:space-between;
    align-items:flex-start;
    flex-wrap:wrap;
    position:relative;
}

.form {
  width:100%;
}
    
.form-item {
      margin-bottom:1em;
}
      
label {
    margin-bottom:0.5em;
    display:block;
    box-sizing:border-box;
    width:100%;
}

.footer-col input {
    display:block;
    box-sizing:border-box;
    width:100%;
}

.footer-col textarea {
    display:block;
    box-sizing:border-box;
    width:100%;
    border:0;
    height:100px;
    resize: vertical;
}

/*responsive*/
@media(max-width: 767px){
  .footer-col{
    width: 50%;
    margin-bottom: 30px;
}
}
@media(max-width: 574px){
  .footer-col{
    width: 100%;
}
}
</style>