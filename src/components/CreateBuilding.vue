<template>
    <div class="container">
        <div class="header">
            <h3 class="title">{{ name }} Komponenta</h3>
            <span> {{ desc }} </span>
        </div>
        <div class="body">
            <div class="field">
                <label for="building-name">Naziv Zgrade</label>
                <div class="control">
                    <input class="input is-primary" type="text" name="building-name" id="building-name">
                </div>
            </div>
            <div class="input-form">
                <label for="tennants-no">Broj Stanara</label>
                <div class="control">
                    <input class="input is-primary" type="text" name="tennants-no" id="tennants-no">
                </div>
            </div>

            <button class="button" type="submit">Kreiraj zgradu</button>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'CreateBuilding',
        props: {
            name: String,
            desc: String,    
        }
    }
</script>

<style lang="css" scoped>
div {
    min-width: fit-content;
    max-width: 30vw;
}

.body{
    margin-top: 25px;
}
</style>