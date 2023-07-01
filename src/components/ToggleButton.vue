<template>
    <div class="toggle">
        <div class="item1">
            
        </div>
        <div class="item2">

        </div>
    </div>
</template>


<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'ToggleButton '
})


</script>
<style lang="scss">
.toggle {
    display: none;

    .item1{
        width: 28px;
        height: 28px;
        border: 1px solid #91eef3;
        border-radius: 5px;
    }
    .item2{
        margin-top: -33px;
        margin-left: 3px;
        border-radius: 5px;
        width: 28px;
        height: 28px;
        border: 1px solid #46c2d8;
    }


}




</style>