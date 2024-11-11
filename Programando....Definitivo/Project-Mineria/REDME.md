<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=ç, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div class="container-fluid">
        <nav class="navbar navbar-expand-lg navbar-dark justify-content-between">
            <a href="#" class="navbar-brand">
            <img 
            src="../images/logotipo-ficticio-removebg-preview.png" 
            alt="We share"  
            loading="lazy" 
            class="navbar-brand__img">
            Terramin 
            </a>
            <button 
            class="navbar-toggler me-3"
            type="button"
            data-bs-toggle="collapse" 
            data-bs-target="#contenido-nav" 
            aria-controls="contenido-nav" 
            aria-expanded="false"
            aria-label="Toggle navegation"
            >
            <span class="navbar-toggler-icon"></span>
            </button>
            
            <div class="collapse navbar-collapse ms-auto" id="contenido-nav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a href="#" class="nav-link nav-link-custom"><i class="fas fa-home"></i> Inicio</a>
                    </li>
                    <li class="nav-item">
                        <a href="#" class="nav-link nav-link-custom"><i class="fas fa-info-circle"></i> Nosotros</a>
                    </li>
                
                    <li class="nav-item">
                        <a href="#" class="nav-link nav-link-custom"><i class="fas fa-leaf"></i> Sustentabilidad</a>
                    </li>

                    <li class="nav-item">
                        <a href="#" class="nav-link nav-link-custom"><i class="fas fa-briefcase"></i> Trabaja con nosotros</a>
                    </li>

                    <li class="nav-item">
                        <a href="#" class="nav-link nav-link-custom"><i class="fas fa-envelope"></i> Contactos</a>
                    </li>
           
                </ul>


        <!--Iconos de redes sociales-->
                <ul class="navbar-nav d-flex flex-row align-items-center me-3 ml-auto">
                    <li class="nav-item">
                        <a href="https://www.facebook.com" target="_blank" class="nav-link"><i class="fab fa-facebook-f"></i></a>
                    </li>
            
                    <li class="nav-item">
                        <a href="https://www.instagram.com" target="_blank" class="nav-link"><i class="fab fa-instagram"></i></a>
                    </li>
            
                    <li class="nav-item">
                        <a href="https://www.twitter.com" target="_blank" class="nav-link"><i class="fab fa-twitter"></i></a>
                    </li>
                </ul>


            </div>
        </nav>
    </div>

    


    <!--Inclusion de Javascript con Bootraps-->

    <script src="../bootstrap/js/bootstrap.bundle.min.js"></script>


    <!--
    <div class="container">
        <div class="row row-cols-1">
            <!-Menu de navegacion -->
            <!--
            <nav class="nav justify-content-end nav-tabs" id="navegation" role="tablist">
                

                <li class="nav-item">
                    <a href="#contenido-inicio" class="nav-link active" data-bs-toggle="tab" role="tab" aria-selected="true" id="inicio-tab" aria-controls="contenido-inicio">Inicio</a>
                </li>

                <li class="nav-item">
                    <a href="#contenido-about" class="nav-link" data-bs-toggle="tab" role="tab" aria-selected="false" id="about-tab" aria-controls="contenido-about">Nosotros</a>
                </li>

                <li class="nav-item">
                    <a href="#contenido-sustentabilidad" class="nav-link" data-bs-toggle="tab" role="tab" aria-selected="false" id="sustentabilidad-tab" aria-controls="contenido-sustentabilidad">Sustentabilidad</a>
                </li>

                <li class="nav-item">
                    <a href="#contenido-rrhh" class="nav-link" data-bs-toggle="tab" role="tab" aria-selected="false" id="rrhh-tab" aria-controls="contenido-rrhh">Trabaja con nosotros</a>
                </li>
    
                <li class="nav-item">
                    <a href="#contenido-contacto" class="nav-link" data-bs-toggle="tab" role="tab" aria-selected="false" id="contacto-tab" aria-controls="contenido-contactos">Contactos</a>
                </li>
            </nav>
            <!-Contenido de pestaña-->
            <!--
            <div class="tab-content" id="contenido-nav">
                <!Inicio--> 
                <!--
                <div class="tab-pane fade show active" role="tabpanel" id="contenido-inicio" aria-labelledby="inicio-tab" >
                    <h1>Inicio</h1>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit harum animi adipisci. Distinctio, non voluptatum voluptas odio officia perferendis est illo, at quod assumenda reiciendis esse doloribus excepturi laborum amet.</p>
                </div>
                
              
                <div class="tab-pane fade" role="tabpanel" id="contenido-about" aria-labelledby="about-tab" >
                    <h2>Noostros</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero aliquam perferendis reprehenderit, facere veniam eius, dolorem aut iure, vitae enim sapiente tempore quis nostrum ipsa voluptatem! Dolore nemo recusandae iste?</p>
                </div>

           
                <div class="tab-pane fade" role="tabpanel" id="contenido-sustentabilidad" aria-labelledby="sustentabilidad-tab">
                    <h2>Sustentabilidad</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi tempore necessitatibus quas? Iusto, qui. Amet ut dolor reprehenderit accusantium aliquid, ex vero cupiditate beatae provident in iusto nam quos similique.</p>

                </div>

                
                <div class="tab-pane fade" role="tabpanel" id="contenido-rrhh" aria-labelledby="rrhh-tab" >
                    <h1>Trabaja con nostoros </h1>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Maiores reprehenderit earum architecto facere nemo, accusantium tempora non dicta laborum velit. Asperiores dolorum assumenda accusantium quo, itaque inventore molestias quisquam porro?</p>
                </div>

                
                <div class="tab-pane fade" role="tabpanel" id="contenido-contacto" aria-labelledby="contacto-tab">
                    <h2>Contacto</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut beatae sit inventore fuga maxime porro eos officiis harum, neque ad voluptatum ab voluptatem in quaerat, architecto ipsam accusantium laboriosam quam?</p>
                </div>

                

           
            </div>

        </div>
    </div>
-->
