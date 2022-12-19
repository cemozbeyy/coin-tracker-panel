<template>
    <div>
        Benim adım: {{ name }}
    </div>
</template>
<script lang="ts">
import { Vue } from 'vue-class-component';
import { Prop } from 'vue-property-decorator'

export default class Dashboard extends Vue {
    public test = 0;

    @Prop() name!: string;

}
</script>
<style lang="scss">

</style>