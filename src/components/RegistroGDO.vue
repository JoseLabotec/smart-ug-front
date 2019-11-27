<template>
  <v-card>
    <v-card-title>
      <v-btn color="success">Nuevo Registro</v-btn>
      <v-spacer></v-spacer>
      <v-text-field
        v-model="search"
        append-icon="search"
        label="Buscar"
        single-line
        hide-details
      ></v-text-field>
    </v-card-title>
    <v-data-table
      :headers="headers"
      :items="desserts"
      :search="search"
    ></v-data-table>
  </v-card>
</template>


<script>
  export default {
    data () {
      return {
        search: '',
        headers: [
          {
            text: 'Fecha',
            align: 'left',
            sortable: false,
            value: 'fecha',
            
          },
          { text: 'Apellidos y Nombres', value: 'datos' },
          { text: 'DNI', value: 'dni' },
          { text: 'Antigüedad', value: 'antiguedad' },
          { text: 'Capacitacion', value: 'capacitacion' },
          { text: 'Horas de Capacitacion', value: 'hcapacitacion' },
          { text: 'ET', value: 'et' },
          { text: 'META', value: 'meta' },
          { text: 'Saldo', value: 'saldo' },
          { text: 'EP', value: 'ep' },
          { text: 'P1', value: 'p1' },
          { text: 'P2', value: 'p2' },
          { text: 'P3', value: 'p3' },
          { text: 'P4', value: 'p4' },
          { text: 'P5', value: 'p5' },
          { text: 'Registro', value: 'registro' },
          { text: 'Estado', value: 'estado' },
          
        ],
        desserts: [
          {
            fecha: '12/11/19',
            datos: 'TINTAYA CHACNAMA JULIO',
            dni: 43979726 ,
            antiguedad: 2.8 ,
            capacitacion: 'Secuencia de iniciación',
            hcapacitacion: 0.5,
            et: 45,
            meta: 100,
            saldo: 55,
            ep: 0,
            p1: 0,
            p2: 0,
            p3: 0,
            p4: 0,
            p5: 0,
            registro: 'ETV-01-19',
            estado: <v-btn color="warning">Guardar</v-btn>, 
          },
           {
            fecha:  <v-text-field 
                    type="text"
                    regular
                  />,
            datos: <v-text-field 
                    type="text"
                    regular
                  />,
            dni:<v-text-field 
                    type="text"
                    regular
                  />,
            antiguedad: <v-text-field 
                    type="text"
                    regular
                  />,
            capacitacion: <v-text-field 
                    type="text"
                    regular
                  />,
            hcapacitacion:<v-text-field 
                    type="text"
                    regular
                  />,
            et: <v-text-field 
                    type="text"
                    regular
                  />,
            meta: <v-text-field 
                    type="text"
                    regular
                  />,
            saldo: <v-text-field 
                    type="text"
                    regular
                  />,
            ep: <v-text-field 
                    type="text"
                    regular
                  />,
            p1: <v-text-field 
                    type="text"
                    regular
                  />,
            p2: <v-text-field 
                    type="text"
                    regular
                  />,
            p3: <v-text-field 
                    type="text"
                    regular
                  />,
            p4: <v-text-field 
                    type="text"
                   regular
                  />,
            p5: <v-text-field 
                    type="text"
                    regular
                  />,
            registro: <v-text-field 
                    type="text"
                    regular
                  />,
            estado: <v-btn color="warning">Guardar</v-btn>, 
          },
          
        ],
      }
    },
  }
</script>