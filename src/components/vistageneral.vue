<template>
    <v-app id="inspire">
        <div :style="{'height':'100%','background-image':'url(https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg)'}">
          
            <v-content>
                <v-container    
                    fill-height>
                    <v-layout
                        class="fill-height ma-0 ">
                        <card>
                            <v-card-img >
                                <v-img
                                    width="10%"
                                    height="20%">
                                </v-img>
                            </v-card-img>
                            <v-card-img >
                                <v-img
                                    src="@/assets/EPC-Groupe-Logo2.png" 
                                    max-width="250"
                                   >
                                    </v-img>
                            </v-card-img>
                        </card>
                    </v-layout>
                    <v-layout
                        class="fill-height ma-0 "

                        >
                        <card>
                            <div class="col-lg-12">
                                <div class="m-50" style="margin:10%" @click="clickMethod">
                                    <v-card-img >
                                        <a href="#">
                                            <v-img
                                                src="@/assets/Imagen1.png" 
                                                width="140"
                                                height="33%">
                                            </v-img>
                                        </a>
                                    </v-card-img>
                                    <div id="example-3">
                                        <button v-on:click="voladuras">Gestion de Voladuras</button>
                                    </div>
                                </div>

                                 <div class="m-50" style="margin:10%">
                                    <v-card-img >
                                    <a href="#">
                                        <v-img
                                            src="@/assets/Imagen2.png" 
                                            width="140"
                                            height="33%">
                                        </v-img>
                                        </a>
                                    </v-card-img>
                                   <div id="example-3">
                                        <button v-on:click="procesos">Gestion de Procesos</button>
                                        
                                    </div>
                                </div>

                                 <div class="m-50" style="margin:10%">
                                    <v-card-img >
                                    <a href="#">
                                        <v-img
                                            src="@/assets/Imagen3.png" 
                                            width="140"
                                            height="33%">
                                        </v-img>
                                        </a>
                                    </v-card-img>
                                     <div id="example-3">
                                        <button v-on:click="operativa">Gestion de Disciplina Operativa</button>
                                        
                                    </div>
                                </div>
                            </div>
                        </card>
                            
                    </v-layout>
                </v-container>
            </v-content> 
        </div>
    </v-app>
</template>




<script>
   export default {
    props: {
      source: String,
    },
  }
</script>