<script setup>
import semillero from "../data/dataSemilleros.json";	const props = defineProps({
    semillero: Object
});
let estudiante = ref(semillero[0].programa[0]);	

</script>	