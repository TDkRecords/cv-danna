<script>
    import danna from "$lib/images/danna (1-1).jpg";
    import "$lib/css/style.css";
</script>

<svelte:head>
    <title>CV - Danna</title>
</svelte:head>

<div class="container">
    <div class="row">
        <div class="pt-4 col-md-4 text-center bg-primary">
            <img
                src={danna}
                alt="danna.jpg"
                class="img-fluid rounded-circle border border-4 border-success p-2"
                width="360px"
            />
            <h2 class="fw-bold">Danna Gabriela Betancourt</h2>
            <p class="text-muted">C.C. 1.081.055.963</p>
            <section class="container">
                <div class="hr-class rounded-5 bg-success"></div>
                <h4 class="mt-2">Contacto</h4>
                <div class="text-start icons-info mb-4">
                    <div>
                        <i class="fa-solid fa-phone"></i>
                        <span>(+57) 322 5326824</span>
                    </div>
                    <div>
                        <i class="fa-solid fa-envelope"></i>
                        <a href="mailto:danagabrielabetancourt@gmail.com">
                            danagabrielabetancourt@gmail.com
                        </a>
                    </div>
                    <div>
                        <i class="fa-brands fa-whatsapp"></i>
                        <a href="https://wa.me/+573225326824" target="_blank">
                            (+57) 322 5326824
                        </a>
                    </div>
                </div>

                <div class="hr-class rounded-5 bg-success"></div>
                <h4 class="mt-2">Idiomas</h4>
                <ul class="text-start">
                    <li>Español - <small>nativo</small></li>
                    <li>Ingles - <small>B2</small></li>
                </ul>
            </section>
        </div>
        <div class="col-md-8 p-0 mt-5">
            <section class="mb-4">
                <h3 class="text-dark bg-primary px-4 rounded-end-5">Perfil</h3>
                <p class="px-4">
                    Cuento con sólidas habilidades en atención al cliente,
                    brindando un trato cordial, eficiente y enfocado en resolver
                    necesidades de manera oportuna. Me caracterizo por ser una
                    persona receptiva, con alta capacidad para seguir
                    indicaciones y adaptarme rápidamente a diferentes entornos
                    de trabajo. Además, destaco por mi actitud proactiva y mi
                    disposición para colaborar en diversas tareas, aportando al
                    trabajo en equipo y contribuyendo a un ambiente laboral
                    positivo. Mi compromiso, responsabilidad y enfoque en la
                    mejora continua me permiten desempeñar mis funciones con
                    eficacia y aportar valor a la organización.
                </p>
            </section>

            <section class="mb-4">
                <h3 class="text-dark bg-primary px-4 rounded-end-5">
                    Historial Académico
                </h3>
                <div class="px-4">
                    <h5>San Francisco de Asís - Pasto</h5>
                    <p>Primaria <small class="text-muted">2017</small></p>
                    <h5>San Nicolás - Pasto</h5>
                    <p>Secundaria <small class="text-muted">2024</small></p>
                    <h5>Lenguas - Vipri</h5>
                    <p>Segundo Nivel <small class="text-muted">2024</small></p>
                </div>
            </section>

            <section class="mb-4">
                <h3 class="text-dark bg-primary px-4 rounded-end-5">
                    Referencia Familiar
                </h3>
                <div class="px-4">
                    <h5>Carolina Astris Chamorro Yela</h5>
                    <ul>
                        <li>Técnico en desarrollo empresarial</li>
                        <li>Asesora Comercial - Laboratorios Lissia</li>
                        <small>
                            <i class="fa-solid fa-phone"></i>
                            (+57) 311 775 0911
                        </small>
                    </ul>

                    <h5>Diana Catalina Santracruz</h5>
                    <ul>
                        <li>Licenciada en Primera Infancia</li>
                        <small>
                            <i class="fa-solid fa-phone"></i>
                            (+57) 323 521 1780
                        </small>
                    </ul>
                </div>
            </section>

            <section class="mb-4">
                <h3 class="text-dark bg-primary px-4 rounded-end-5">
                    Referencia Laboral
                </h3>
                <div class="px-4">
                    <h5>Johnatan David Santacruz</h5>
                    <ul>
                        <li>Abogado</li>
                        <li>Propietario - Shot Me (Plaza Norte)</li>
                        <small>
                            <i class="fa-solid fa-phone"></i>
                            (+57) 316 360 0769
                        </small>
                    </ul>

                    <h5>Alcira Rodrigues</h5>
                    <ul>
                        <li>Vendedora - Tienda El Descuentaso</li>
                        <small>
                            <i class="fa-solid fa-phone"></i>
                            (+57) 318 328 3940
                        </small>
                    </ul>
                </div>
            </section>

            <section class="mb-4">
                <h3 class="text-dark bg-primary px-4 rounded-end-5">
                    Experiencia Laboral
                </h3>
                <div class="px-4">
                    <h5>Vendedora</h5>
                    <ul>
                        <li>Tienda El Descuentaso</li>
                        <li>
                            <small class="text-muted"
                                >Enero 2024 - Marzo 2024</small
                            >
                        </li>
                    </ul>

                    <h5>Cajera</h5>
                    <ul>
                        <li>Shot Me - Plaza Norte</li>
                        <li>
                            <small class="text-muted"
                                >Octubre 2024 - Noviembre 2024</small
                            >
                        </li>
                    </ul>
                </div>
            </section>
        </div>
    </div>
</div>
