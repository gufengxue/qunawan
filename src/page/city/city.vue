<template>
    <div class="city">
        <city-Header></city-Header>
    </div>
</template>

<script>
import axios from 'axios'
import cityHeader from "./components/header"
import citySerch from "./components/serch"
import cityList from "./components/list"
import cityAlphabet from "./components/alphabet"
export default {
    components: {
        cityHeader
    },
    data () {
        return {

        }
    }
}
</script>

<style lang="stylus" scoped>

</style>
