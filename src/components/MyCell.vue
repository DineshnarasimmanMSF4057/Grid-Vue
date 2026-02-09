<template>
  <div>
 <button class="e-btn e-primary" >OK</button>
  </div>
</template>

<script>




import {
  ButtonComponent,

} from '@syncfusion/ej2-vue-buttons';


export default {
  components: {

    'ejs-button': ButtonComponent,

  },

  props: {
    rowData: {
   type: Object,
   required: true,
 },
},
  data() {
    
    return {
     
    };
  },
  methods: {
    btnClick: function () {
      alert()
    },
  },
};
</script>
