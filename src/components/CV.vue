<script setup>
    import avatar from '/src/assets/img/AVATAR.jpg';

</script>

<template>
    <div class="h-screen max-h-screen flex relative overflow-hidden">
        <aside class="lg:w-[35%] w-80 shadow-black shadow-lg ">
            <div class="flex justify-center flex-col lg:mb-28 mb-16 pt-12 h-[18em] bg-blue-800 text-white myBorder">
                <div class="lg:text-4xl lg:p-0 lg:font-normal font-semibold text-lg text-center">
                    <div>Alexis Jose</div> 
                    <div>Gonzalez Martinez</div>
                </div>
                <div class="mt-3 text-center lg:text-xl">INGENIERO EN INFORMATICA</div>
                <div class="flex justify-center relative h-32">
                    <div class="border-4 border-white lg:w-52 w-36 aspect-square rounded-full overflow-hidden absolute top-[20%]">
                        <img :src="avatar" alt="" class="w-full h-full">
                    </div>
                </div>
            </div>

            <div class=" lg:px-6  sm:h-full h-[22em] overflow-auto pl-3 pr-1 space-y-4">

                <!-- DATOS PERSONALES -->
                <div>
                    <div class="titulo">Datos Personales</div>
                    <div class="flex flex-col lg:pl-3 md:text-base text-sm">
                        <a href="wa.link/q2ud1t" class="">+58 424 368 16 83</a>
                        <div class="">alexjg.181@gmail.com</div>
                    </div>
                </div>

                <!-- COMPETENCIAS -->
                <div>
                    <div class="titulo">Competencias</div>
                    <div class="flex flex-col">
                        <div class="">Laravel</div>
                        <div class="">JavaScript</div>
                        <div class="">Vue 3</div>
                        <div class="">Tailwind CSS</div>
                        <div class="">Git</div>
                    </div>
                </div>

                <!-- IDIOMAS -->
                <div>
                    <div class="titulo">Idiomas</div>
                    <div class="flex flex-col">
                        <div class="">Ingles</div>
                    </div>
                </div>

                <!-- PROYECTOS -->
                <div >
                    <div class="titulo">Proyectos</div>
                    <div class="flex flex-col">
                        <a href="https://alexzalez.github.io/DolarWeb/" class=" inline-flex items-center">
                            <div class="text-lg tracking-wide text-blue-600 font-semibold">DolarWeb</div>
                            <div class="w-4 aspect-square ml-0.5 stroke-blue-600 ">
                                <svg xmlns="http://www.w3.org/2000/svg" class="w-full" viewBox="0 0 15 15" fill="none">
                                  <path fill-rule="evenodd" clip-rule="evenodd" d="M3 2C2.44772 2 2 2.44772 2 3V12C2 12.5523 2.44772 13 3 13H12C12.5523 13 13 12.5523 13 12V8.5C13 8.22386 12.7761 8 12.5 8C12.2239 8 12 8.22386 12 8.5V12H3V3L6.5 3C6.77614 3 7 2.77614 7 2.5C7 2.22386 6.77614 2 6.5 2H3ZM12.8536 2.14645C12.9015 2.19439 12.9377 2.24964 12.9621 2.30861C12.9861 2.36669 12.9996 2.4303 13 2.497L13 2.5V2.50049V5.5C13 5.77614 12.7761 6 12.5 6C12.2239 6 12 5.77614 12 5.5V3.70711L6.85355 8.85355C6.65829 9.04882 6.34171 9.04882 6.14645 8.85355C5.95118 8.65829 5.95118 8.34171 6.14645 8.14645L11.2929 3H9.5C9.22386 3 9 2.77614 9 2.5C9 2.22386 9.22386 2 9.5 2H12.4999H12.5C12.5678 2 12.6324 2.01349 12.6914 2.03794C12.7504 2.06234 12.8056 2.09851 12.8536 2.14645Z" fill="#000000"/>
                                </svg>
                            </div>
                        </a>
                    </div>
                </div>

            </div>
        </aside>
        <main class="w-full pb-3 pt-1 lg:overflow-hidden overflow-y-scroll">
            <section class="">

                <!-- PERFIL -->
                <div class="px-4">
                    <div class="titulo">Perfil</div>
                    <div class="flex flex-col pl-3">
                        <div class="">
                            Informático con 1 año de experiencia en desarrollo web y 3 años de conocimiento en soporte técnico y redes. 
                        </div>
                        <div class="">
                            Apasionado por el desarrollo web y la automatización de procesos.
                        </div>
                        <div class="">
                            Busco un puesto de Desarrollador Web Junior para desenvolver mis conocimientos.
                        </div>
                    </div>
                </div>

                <!-- FORMACION -->
                <div class="px-4">
                    <div class="titulo">Formación</div>
                    <div class="flex flex-col pl-3">
                        <div class="sub-section ">
                            <div class="sub-titulo">Ingeniería en Informática</div>
                            <div class="fecha">oct 2018 - nov 2023</div>
                        </div>
                        <div>Universidad Nacional Rómulo Gallegos</div>
                    </div>
                </div>

                <!-- EXPERIENCIAS -->
                <div class="px-4">
                    <div class="titulo">Experiencia</div>
                    <div class="flex flex-col pl-3 gap-4">
                        
                        <div>
                            <div class="sub-section ">
                                <div class="sub-titulo">Soporte Técnico</div>
                                <div class="fecha">jul 2019 - dic 2023</div>
                            </div>
                            <div class="text-blue-800">Tecnosoluciones C.A.</div>
                            <div>
                                <p class="text-sm">
                                    Mantenimiento de computadores y reparaciones con soldadura electrónica.
                                </p>
                                
                            </div>
                        </div>
                        
                        <div>
                            <div class="sub-section ">
                                <div class="sub-titulo">Instalador de CCTV con Camaras IP</div>
                                <div class="fecha">ene 2021 - feb 2022</div>
                            </div>
                            <div class="text-blue-800">Tecnosoluciones C.A.</div>
                            <div>
                                <div class="text-sm">
                                    Diseño e implementación de proyectos de instalación u/o renovación de CCTV en las empresas:
                                </div>
                                <ol class="pl-8 list-decimal text-sm">
                                    <li>Multiplast C.A.</li>
                                    <li>Multinacional de Sabores C.A.</li>
                                    <li>Maxiplast C.A. (2 sedes)</li>
                                    <li>Tubomax C.A.</li>
                                </ol>
                            </div>
                        </div>

                        <div>
                            <div class="sub-section ">
                                <div class="sub-titulo">Desarrollador Web Junior</div>
                                <div class="fecha">mar 2022 - jul 2022</div>
                            </div>
                            <div class="text-blue-800">Singularity C.A. (Agencia de Desarrollo Web) - Aragua</div>
                            <div>
                                <div class="text-sm">
                                    Desarrollo de funciones de web scraping para obtención de datos.
                                </div>                                
                            </div>
                        </div>

                        <div>
                            <div class="sub-section ">
                                <div class="sub-titulo">Desarrollador Web Junior</div>
                                <div class="fecha">jul 2023 - Actualidad</div>
                            </div>
                            <div class="text-blue-800">BNK Agencia Creativa (Agencia de Publicidad) -  Aragua.</div>
                            <div>
                                <div class="text-sm">
                                    Desarrollo de páginas web y mantenimiento de paginas wordpress.
                                </div>                                
                            </div>
                        </div>

                    </div>
                </div>

                <!-- REFERENCIAS -->
                <div class="px-4 ">
                    <div class="titulo">Referencias</div>
                    <div class="flex flex-wrap space-y-2 max-h-full pl-3 md:text-base text-sm  pt-2">
                        <div class=" w-full">
                            <div>Ing. Aylwin Córdova</div>
                            <div>+58 416 110 36 49</div>
                        </div>
                        <div class=" w-full">
                            <div>Ing. Ángel Araujo</div>
                            <div>+58 412 891 93 52</div>
                        </div>
                        <div class=" w-full">
                            <div>Dev. David López</div>
                            <div>+58 412 049 84 57</div>
                        </div>
                    </div>
                </div>

            </section>
        </main>
    </div>
</template>


<style  scoped>

.content-section{}

.titulo {
    @apply mb-2 border-b-2 border-blue-800 font-sans font-semibold lg:text-xl text-lg text-blue-900
}

.sub-section{
    @apply flex flex-wrap justify-between 
}
.sub-section .sub-titulo{
    @apply font-semibold md:w-fit w-full 
}

.fecha{
    @apply font-semibold text-blue-900
}

.myBorder{
    border-radius: 0px 0px 150px 150px / 0px 0px 25px 25px;
}
</style>