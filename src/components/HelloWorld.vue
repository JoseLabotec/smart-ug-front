
<template>

  <v-app id="inspire" >
     
  <div :style="{'height':'100%','background-image':'url(https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg)'}">
    <v-content >

      <v-container
        class="fill-height"
         >
         <v-layout
          align-center
          justify-center
        >
         <v-flex
            xs100%
            sm100%
            md100%
          >
         
      <v-layout
          align-center
          justify-center
        >
        
      <v-card-img class="justify-center">
          <v-img
         src="@/assets/EPC-Groupe-Logo2.png" 
          max-width="120"
        max-height="250" 
             
           ></v-img>

      </v-card-img>
      </v-layout>

        <v-spacer />

      <v-layout
          align-center
          justify-center
        >
          <v-flex
            xs6
            sm4
            md4
          >
         
        <v-card-text class="text-center">
              
              <v-form>
                  
                  <v-text-field
                    id="login"
                    label="NOMBRE DE USUARIO"
                    validate="required"
                    name="login"
                    type="text"
                    filled
                    rounded
                    outlined
                  />

                  <v-text-field
                    id="password"
                    validate="required"
                    label="CONTRASEÑA"
                    name="password"
                    type="password"
                    filled
                    rounded
                    outlined
                  />
              </v-form>
             
              </v-card-text>
              </v-flex>
              </v-layout>

            <v-layout
          align-center
          justify-center
        >
            <v-card-actions class="justify-center">
                <v-btn rounded color="#6A0218" dark large>INICIAR SESION</v-btn>
            </v-card-actions>
          </v-layout>
          
          <v-layout
          align-center
          justify-center
          >
          <v-card-actions class="justify-center">
                <v-btn text>¿OLVIDO SU CONTRASEÑA?</v-btn>
            </v-card-actions>
          </v-layout>

          <v-layout class="text-end">
            <v-card-text>
              ENERGIA CONCENTRADA
            </v-card-text>
            </v-layout>
          <v-layout class="text-end">
            <v-card-text>
              Pioneros de la Industria del Explosivo desde 1893
            </v-card-text>
            </v-layout>
            </v-flex>
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


.back{
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
    background: url( 'https://cdn.pixabay.com/photo/2016/03/26/13/09/organic-1280537_1280.jpg') no-repeat center center;
    background-size: cover;
    background-color: red;
    transform: scale(1.1);
  }

