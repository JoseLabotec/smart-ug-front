<template >
    <v-app id="inspire"  >
           <v-parallax height="700" src="@/assets/back2.png">
            <v-layout column>
                <div class="row">
                    <div class="col-lg-6">
                        <div class="col-ma-12">
                            <v-img
                                src="@/assets/logo4.png" 
                                width="120">
                            </v-img>
                        </div>
                    </div>
                    <div class="col-lg-2" style="margin-top:25%">
                        <v-btn text color="#FFFFFF">DISCIPLINA OPERATIVA</v-btn>
                    </div>
                    <div class="col-lg-2" style="margin-top:20%">
                        <v-img
                            src="@/assets/imagen4.png" 
                            width="200">
                        </v-img>
                    </div>
                    <div class="col-lg-2" style="margin-top:20%" >
                         <v-btn text color="#FFFFFF">EFICIENCIAS</v-btn>
                         <div class="col-lg-2" style="margin-top:40%" >
                         <v-btn text color="#FFFFFF">PROCESOS</v-btn>
                          </div>
                    </div>
                    
                </div>
            <div class="col-ma-12" style="margin-left:10%">
                <h1 class="subheading">www.epc-groupe.com</h1>
            </div>
           </v-layout>
           
            
            
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