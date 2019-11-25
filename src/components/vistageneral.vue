<template height="100%" width="100%">
    <v-app id="inspire" height="1000" width="1000" >
           <v-parallax height="100%" width="100%" src="@/assets/back.png">
            <v-content height="1000" width="1000">
                <v-container    
                    fill-height>
                    <v-layout
                        class="fill-height ma-0 ">
                        <card>
                            <v-card-img >
                                <v-img
                                    width="20%"
                                    height="30%">
                                </v-img>
                            </v-card-img>
                            <v-card-img >
                                <v-img
                                    src="@/assets/logo3.png" 
                                    max-width="400"
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
                                <div  style="margin:15%">
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

                                 <div  style="margin:15%">
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

                                 <div class="m-50" style="margin:15%">
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
        </v-parallax>
    </v-app>
</template>




<script>
   export default {
    props: {
      source: String,
    },
  }
</script>