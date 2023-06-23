<template>
    <div class=" d-flex justify-content-between flex-wrap flex-md-nowrap align-items-center pt-0 pb-0 mb-0 border-bottom p-0">
        <h1 class="h2">Agenda tu cita</h1>
        <div class="btn-toolbar mb-2 mb-md-0" id="agenda">
         <!--    <div class="btn-group me-2">
                <button type="button" class="btn btn-sm btn-outline-secondary rounded-4  me-2">Cancelar</button>
                <button type="button" class="btn btn-sm btn-outline-secondary rounded-4">
                    <router-link class="nav-link active" to="/"> Salir</router-link></button>
            </div>
 -->
        </div>
    </div>
    <agenda-l-fcom></agenda-l-fcom>
</template>


<script>
import AgendaLFcom from '../DashboardaprendizEnfermera/AgendaLFcom.vue';
export default {
    name: 'CitasAprendizComp',
    components:{
        AgendaLFcom
    }
}
</script>



<style scoped>

</style>