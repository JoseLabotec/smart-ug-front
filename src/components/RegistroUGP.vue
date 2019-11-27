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
          { text: 'Labor', value: 'labor' },
          { text: 'Guardia', value: 'guardia' },
          { text: 'Turno', value: 'turno' },
          { text: 'Operador', value: 'oper' },
          { text: 'Equipo', value: 'eq' },
          { text: 'COD', value: 'cod' },
          { text: 'COD DET', value: 'codet' },
          { text: 'Cumpli', value: 'cump' },
          { text: 'Detalle', value: 'detalle' },
          { text: 'Longitud Perf (m)', value: 'long' },
          { text: 'Hora Inicio', value: 'Hinicio' },
          { text: 'HI', value: 'hi' },
          { text: 'Hora Final', value: 'Hfinal' },
          { text: 'HF', value: 'hf' },
          { text: 'Tiempo(hr)', value: 'tiempo' },
          { text: 'Cumplimiento', value: 'cumplimiento' },
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
 },
 {
            fecha:  <v-text-field 
                    type="text"
                    regular
                  />,
            labor: <v-text-field 
                    type="text"
                    regular
                  />,
            guardia:<v-text-field 
                    type="text"
                    regular
                  />,
            turno: <v-text-field 
                    type="text"
                    regular
                  />,
            oper: <v-text-field 
                    type="text"
                    regular
                  />,
            eq:<v-text-field 
                    type="text"
                    regular
                  />,
            cod: <v-text-field 
                    type="text"
                    regular
                  />,
            codet: <v-text-field 
                    type="text"
                    regular
                  />,
            cump: <v-text-field 
                    type="text"
                    regular
                  />,
            detalle: <v-text-field 
                    type="text"
                    regular
                  />,
            long: <v-text-field 
                    type="text"
                    regular
                  />,
            Hinicio: <v-text-field 
                    type="text"
                    regular
                  />,
            HI: <v-text-field 
                    type="text"
                    regular
                  />,
            Hfinal: <v-text-field 
                    type="text"
                   regular
                  />,
            HF: <v-text-field 
                    type="text"
                    regular
                  />,
            tiempo: <v-text-field 
                    type="text"
                    regular
                  />,
            cumplimiento: <v-text-field 
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