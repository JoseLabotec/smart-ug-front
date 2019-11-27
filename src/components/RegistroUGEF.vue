<template>
  <v-card>
    <v-card-title>
      <v-btn color="success">Nuevo Registro</v-btn>
      <v-spacer></v-spacer>
      <v-text-field
        v-model="search"
        label="Buscar"
        append-icon="search"
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
            text: 'Mes',
            align: 'left',
            sortable: false,
            value: 'mes',
            
          },
          { text: 'Año', value: 'anio' },
          { text: 'Residente', value: 'resid' },
          { text: 'Semana', value: 'semana' },
          { text: 'Fecha', value: 'fecha' },
          { text: 'Turno', value: 'turno' },
          { text: 'Guardia', value: 'guardia' },
          { text: 'Seccion', value: 'seccion' },
          { text: 'Ancho', value: 'ancho' },
          { text: 'Altura', value: 'altura' },
          { text: 'Tipo de Disparo', value: 'tDisparo' },
          { text: 'Equipo', value: 'equ' },
          { text: 'COD. Equipo', value: 'codequi' },
          { text: 'Operador JUMBO', value: 'opJumbo' },
          { text: 'DNI Operador', value: 'dniop' },
          { text: 'Perforista', value: 'perfor' },
          { text: 'DNI Perforista', value: 'dniper' },
          { text: 'Perforista', value: 'perfor' },
          { text: 'Labor', value: 'labor' },
          { text: 'Long.Perforacion', value: 'longperfo' },
          { text: 'Eficacia', value: 'eficacia' },
          { text: 'Causa asignable Longitud Perforacion', value: 'causa' },
          { text: 'AVANCE Diario', value: 'avance' },
          { text: '>=2.9', value: 'mayor' },
          { text: '<2.9', value: 'menor' },
          { text: 'LEI', value: 'lei' },
          { text: 'Objetivo', value: 'obj' },
          { text: 'N° Taladros', value: 'Ntal' },
          { text: 'Kg Explosivo', value: 'kgExplo' },
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
            mes:  <v-text-field 
                    type="text"
                    regular
                  />,
            anio: <v-text-field 
                    type="text"
                    regular
                  />,
            resid:<v-text-field 
                    type="text"
                    regular
                  />,
            semana: <v-text-field 
                    type="text"
                    regular
                  />,
            fecha: <v-text-field 
                    type="text"
                    regular
                  />,
            turno:<v-text-field 
                    type="text"
                    regular
                  />,
            guardia: <v-text-field 
                    type="text"
                    regular
                  />,
            seccion: <v-text-field 
                    type="text"
                    regular
                  />,
            ancho: <v-text-field 
                    type="text"
                    regular
                  />,
            altura: <v-text-field 
                    type="text"
                    regular
                  />,
            tDisparo: <v-text-field 
                    type="text"
                    regular
                  />,
            equ: <v-text-field 
                    type="text"
                    regular
                  />,
            codequi: <v-text-field 
                    type="text"
                    regular
                  />,
            opJumbo: <v-text-field 
                    type="text"
                   regular
                  />,
            dniop: <v-text-field 
                    type="text"
                    regular
                  />,
            perfor: <v-text-field 
                    type="text"
                    regular
                  />,
            dniper: <v-text-field 
                    type="text"
                    regular
                  />,
            labor: <v-text-field 
                    type="text"
                    regular
                  />,
            longperfo: <v-text-field 
                    type="text"
                    regular
                  />,
            eficacia: <v-text-field 
                    type="text"
                    regular
                  />,
            causa: <v-text-field 
                    type="text"
                    regular
                  />,                        
            avance: <v-text-field 
                    type="text"
                    regular
                  />,
            mayor: <v-text-field 
                    type="text"
                    regular
                  />,
            menor: <v-text-field 
                    type="text"
                    regular
                  />,
            lei: <v-text-field 
                    type="text"
                    regular
                  />,
            obj: <v-text-field 
                    type="text"
                    regular
                  />,
            Ntal: <v-text-field 
                    type="text"
                    regular
                  />,
            kgExplo: <v-text-field 
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