<template>
    <div>
        <b-nav tabs>
            <b-nav-item disabled><b>Fancy Quiz App</b></b-nav-item>
            <b-nav-item disabled>Counters: {{ numCorrect }}/{{ numTotal }}</b-nav-item>
        </b-nav>
    </div>
</template>

<script>
export default{
    props: [
        'numCorrect',
        'numTotal'
    ]
}
</script>