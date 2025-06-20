<script>
    import danna from "$lib/images/danna (1-1).jpg";
</script>

<svelte:head>
    <title>CV - Danna</title>
    <link
        href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
        rel="stylesheet"
        integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7z1p1rU9zrjG1lKo5i5v6AScXn/tWtIaxVXM"
        crossorigin="anonymous"
    />
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
        </div>

        <div class="col-md-8 p-0">
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
                        <li>📞 (+57) 311 775 0911</li>
                    </ul>

                    <h5>Diana Catalina Santracruz</h5>
                    <ul>
                        <li>Licenciada en Primera Infancia</li>
                        <li>📞 (+57) 323 521 1780</li>
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
                        <li>📞 (+57) 316 360 0769</li>
                    </ul>

                    <h5>Alcira Rodrigues</h5>
                    <ul>
                        <li>Vendedora - Tienda El Descuentaso</li>
                        <li>📞 (+57) 318 328 3940</li>
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
