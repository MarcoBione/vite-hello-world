:<template>
    <div>
        <p class="_myparagraph">{{ paragraph }}</p>
    </div>
</template>

<script>
    export default {
        name:'AppHero',
        data(){
            return{
                paragraph: 'Il mio primo progetto Vue con componenti!'
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>