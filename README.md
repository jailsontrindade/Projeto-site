<!DOCTYPE html>
<html>
     <head>
           <meta charset="uf-8">
           <title>Site Institucional</title>
           <link rel="stylesheet" type="text/css" href="./reset.css">
           <link rel="stylesheet" type="text/css" href="./styles.css">
           <link rel="stylesheet" href="https://kit.fontawesome.com/67726d44bf.js" crossorigin="anonymous"></script>

     </head>
     <bory>
          <div class="container">
               <!--banner-->
               <header>
                  <div class="banner">
                        <div class="box-container">
                             <div class="box-background"></div>
                             <div class="box-banner-title">
                                  <h1>Agência X</h1>
                                  <p>Desenvolvendo seus sitemas</p>                       
                            </div>
                        </div>
                        <div class="company-info-container">
                             <div class="company-info-background"></div>
                             <div class="company-info-titlebox">
                                  <h2>Seja bem-vindo ao noso site</h2>
                                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
                                  Proin vel mollis erat, nec semper magna. Donec vitae sapien 
                                  in ligula venenatis tincidunt.</p>.
                              </div>
                        </div>
                  </div>
               </header>
               <!--seção de serviços-->
               <section>
                    <div class="services-container">
                         <div class="service-box">
                              <div class="service-title" id="gerenciamento-box">
                                   <p>Gerenciamento de Projetos</p>
                              </div>
                              <div class="service-description">
                                    <h3 id="gerenciamento-title">Lorem ipsum</h3>
                                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
                                        Proin vel mollis erat, nec semper magna. Donec vitae sapien 
                                        in ligula venenatis tincidunt.</p>
                              </div>
                         </div>
                         <div class="service-box">
                              <div class="service-title" id="dev-box">
                                   <p>Desenvolvimento</p>
                              </div>
                              <div class="service-description">
                                    <h3 id="dev-title">Lorem ipsum</h3>
                                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
                                        Proin vel mollis erat, nec semper magna. Donec vitae sapien 
                                        in ligula venenatis tincidunt.</p>
                              </div>
                         </div>
                         <div class="service-box">
                              <div class="service-title" id="design-box">
                                   <p>Design UX/UI</p>
                              </div>
                              <div class="service-description">
                                    <h3 id="design-title">Lorem ipsum</h3>
                                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
                                        Proin vel mollis erat, nec semper magna. Donec vitae sapien 
                                        in ligula venenatis tincidunt.</p>
                              </div>
                         </div>
                    </div>
               </section>
               <!--Seção sobre a empresa-->
               <div class="footer-container">
                    <section>
                         <div class="about-container">
                              <div class="about-card">
                                   <i class="fas fa-service"></i>
                                   <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
                                   Proin vel mollis erat, nec semper magna. Donec vitae sapien 
                                   in ligula venenatis tincidunt.</p>
                              </div>
                              <div class="about-card middle-card">
                                   <i class="fas fa-briefcase"></i>
                                   <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
                                   Proin vel mollis erat, nec semper magna. Donec vitae sapien 
                                   in ligula venenatis tincidunt.</p>
                              </div>
                              <div class="about-card">
                                   <i class="fas fa-tablet-alt"></i>
                                   <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
                                   Proin vel mollis erat, nec semper magna. Donec vitae sapien 
                                   in ligula venenatis tincidunt.</p>
                              </div>
                         </div>
                    </section>
                    <footer>
                         <div class="form-container">
                              <div class="form-background"></div>
                              <form>
                                   <input type="text" name="name" id="name" placeholder="Nome">
                                   <input type="email" name="email" id="email" placeholder="E-mail">
                                   <textarea name="message" id="message" placeholder="Sua mensagem"></textarea>
                                   <input type="submit" class="submit" value="Enviar">
                              </form>                        
                         </div>
                         <div class="copyright">
                              <p>Copyright 2022 - Jailson Trindade</p>
                         </div>
                    </footer>  
               </div>
     </bory>

</html>

_____________________________________________________________________________________________________________________________________________________________________

/* general */
html {
    font-family: Helvetica, sans-serif;
}

/* header */
.banner {
    width: 100%;
    height: 600px;
    background-image: url('../capa.jpg');
    position: relative;
    background-position: center;
    border: 2px solid black;
}

.box-container {
    width: 400px;
    height: 200px;
    text-align: center;
    position: absolute;
    right: 100px;
    bottom: 250px;
}
.box-background {
    width: 100%;
    height: 100%;
    background-color: #000;
    opacity: .8;
    position: relative;
}

.box-banner-title {
    position: absolute;
    width: 100%;
    text-align: center;
    top: 0;
    color: aqua;
    padding-top: 65px;
}

.box-banner-title h1 {
    font-size: 32px;
    margin-bottom: 25px;
}

.box-banner-title p {
    font-size: 20px;
}
.company-info-container {
    position: absolute;
    bottom: 0px;
    width: 100%;
    height: 175px;
}

.company-info-background {
    width: 100%;
    height: 100%;
    background-color: #DDD;
    opacity: .9;
}

.company-info-titlebox {
    background-color: #DDD;
    position: absolute;
    padding-left: 10%;
    top: 0px;
    width: 500px;
}

.company-info-titlebox h2, .company-info-titlebox p {
    color: #222;
}

.company-info-titlebox h2 {
    margin-bottom: 30px;
    font-size: 24px;
}

/*Serviços*/

.services-container {
     max-width: 1200px;
     padding: 30px 10%;
     padding-bottom: 0;
}

.service-box {
    width: 100%;
    position: relative;
    clear: both;
    height: 150px;
    margin-bottom: 30px;
}

.service-box:last {
    margin-bottom: 0;
}

.service-title {
    width: 20%;
    height: 150px;
    background-color: #DDD;
    float: left;
    text-align: center;
    line-height: 150px;
    padding: 20px;
    box-sizing: border-box;
}

.service-title p {
    padding-top: 35px;
    color: #fff;
    font-size: 18px;
    line-height: 24px;
}

.service-description {
    width: 80%;
    float: left;
    padding: 30px;
    box-sizing: border-box ;
}

.service-description h3 {
    font-size: 20px;
    margin-bottom: 15px;
    font-weight: bold;
}

.service-description p {
    font-size: 14px;
    line-height: 22px;
}

#gerenciamento-title {
    color: #2364AA;

}

#dev-title {
    color: #3DA5D9;

}

#design-title {
    color: #73BFB8;

}

#gerenciamento-box {
    background-color: #2364AA;

}

#dev-box {
    background-color: #3DA5D9;

}

#design-box {
    background-color: #73BFB8;

}

/* Sobre a empresa*/
.footer-container {
    background-image: url('../rodape.jpg');
    background-position: center;
}

.about-container {
    max-width: 1200px;
    padding: 30px 10%;
    position: relative;
    clear: both;
}

.about-card {
    float: left;
    width: 30%;
    padding: 30px;
    background-color: #fff;
    text-align: center;
    box-sizing: border-box;
}

.middle-card {
    margin-left: 5%;
    margin-right: 5%;
}

.about-card i {
    font-size: 50px;
    color: #AAA;
}

.about-card p {
    margin-top: 50px;
    font-size: 14px;
    line-height: 22px;
    color: blueviolet;
    text-align: left;
}

/* Footer */
footer {
    clear: both;
    max-width: 1200px;
    height: 500px;
    padding: 30px 10%;
    position: relative;
}

.form-container {
    width: 65%;
    height: 375px;
    position: relative;
    display: block;
}

.form-background {
    width: 100%;
    height: 100%;
    background-color: #fff;
    opacity: .5;
}

.form-container form {
    position: absolute;
    top: 30px;
    left: 30px;
    height: 300px;
}

.form-container input, .form-container textarea {
    width: 400px;
    display: block;
    border: none;
    padding: 10px;
    margin-bottom: 15px;
    border-bottom: 1px solid #AAA;
    border-radius: 0;
    background-color: transparent;
}

.form-container textarea {
    height: 120px;
}

.form-container input::placeholder, .form-container textarea::placeholder {
    font-size: 20px;
    font-weight: bold;
}

.form-container .submit {
    background-color: #222;
    color: #fff;
    border: 1px solid transparent;
    width: 100px;
    position: relative;
    float: right;
    cursor: pointer;
    transition: .5s;
}

.form-container .submit:hover {
    background-color: #fff;
    color: #222;
    border: 1px solid #222;
}

.copyright {
    color: #222;
    font-size: 14px;
    font-weight: bold;
    text-align: center;
    position: absolute;
    left: 0;
    right: 0;
    bottom: 30px;
    margin-left: auto;
    margin-right: auto;
}
