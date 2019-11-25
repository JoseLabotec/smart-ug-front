
<template height="100%" width="100%">

  <v-app id="inspire" height="100%" width="100%" >
     
 <v-parallax height="100%" width="100%"
     src="@/assets/back.png"
    >
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
         src="@/assets/logo1.png" 
          width="200"
        height="260" 
             
           ></v-img>

      </v-card-img>
      </v-layout>

        <v-spacer />

      <v-layout
          align-center
          justify-center
        >
          <v-flex
            xs8
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
                    solo
                    rounded
                    outlined
                  />

                  <v-text-field
                    id="password"
                    validate="required"
                    label="CONTRASEÑA"
                    name="password"
                    type="password"
                    solo
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

