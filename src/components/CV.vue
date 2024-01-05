<script setup>
    import avatar from '/src/assets/img/AVATAR.jpg';

</script>

<template>
    <div class="h-screen flex relative">
        <aside class="lg:w-[35%] w-80 max-h-full overflow-hidden shadow-black shadow-lg ">
            <div class="flex justify-center flex-col mb-28 pt-12 h-1/3 bg-blue-800 text-white">
                <div class="lg:text-4xl lg:p-0 lg:font-normal font-semibold text-lg text-center">
                    <div>Alexis Jose</div> 
                    <div>Gonzalez Martinez</div>
                </div>
                <div class="mt-3 text-center">INGENIERO EN INFORMATICA</div>
                <div class="flex justify-center relative h-32">
                    <div class="border-4 border-white lg:w-52 w-36 aspect-square rounded-full overflow-hidden absolute top-[20%]">
                        <img :src="avatar" alt="" class="w-full h-full">
                    </div>
                </div>
            </div>
            <div class="h-full lg:px-6 pl-3 pr-1 space-y-4">
                <div>
                    <div class="titulo">Datos Personales</div>
                    <div class="flex flex-col lg:pl-3">
                        <div class="">+58 424 368 16 83</div>
                        <div class="text-base">alexjg.181@gmail.com</div>
                    </div>
                </div>
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
                <div>
                    <div class="titulo">Idiomas</div>
                    <div class="flex flex-col">
                        <div class="">Ingles</div>
                    </div>
                </div>
                <div >
                    <div class="titulo">Proyectos</div>
                    <div class="flex flex-col">
                        <div class="">DolarWeb</div>
                    </div>
                </div>

            </div>
        </aside>
        <main class="w-full pb-3 pt-1 lg:overflow-hidden overflow-y-scroll">
            <section class="">
                <div class="px-4">
                    <div class="titulo">Perfil</div>
                    <div class="flex flex-col pl-3">
                        <div class="">
                            Informático con 1 año de experiencia en desarrollo web y 3 años de conocimiento en soporte técnico y redes. 
                        </div>
                        <div class="">
                            Apasionado por el desarrollo de frontend y automatización de procesos.
                        </div>
                        <div class="">
                            Busco un puesto de trabajo para desenvolver mis conocimientos.
                        </div>
                    </div>
                </div>

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

                
                <div class="px-4 ">
                    <div class="titulo">Referencias</div>
                    <div class="flex flex-wrap space-y-2 max-h-full pl-3  pt-2">
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
</style>