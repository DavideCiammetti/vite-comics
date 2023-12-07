<script>
    export default{
        name :'main-info', 
    }
</script>

<template>
     <!-- info -->
     <div class="info-container">
            <ul>
                <li class="list-info under-li">
                    <li class="list-info">3</li>
                    2
                </li>
                <li class="list-info">1</li>
                <li class="list-info">1</li>
                <li class="list-info">1</li>
            </ul>
        </div>
         <!-- info -->
</template>

<style scope lang="scss">
@use '../style/partials/variables.scss' as *;

.info-container{
    background-color: rgb(93, 93, 93);

        ul{
            display: $d-flex;
            list-style: none;
            margin-left: 5.5rem;

                .under-li{
                    display: $d-flex;
                    flex-direction: column;
                }
        }
}

</style>