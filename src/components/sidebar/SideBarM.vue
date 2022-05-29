<template>
    <ul>
        <li><span><img alt="SIDE" src="../../assets/images/side_e.png" width="64"></span></li>
        <li><a class="active" href="#">S</a></li>
        <li><a href="#">P</a></li>
        <li><a href="#">W</a></li>
        <li><a href="#">N</a></li>
    </ul>
</template>

<script>
    export default {
        props: [
            'j',
        ]
    }
</script>
<style scoped>
    ul {
        list-style-type: none;
        margin: 0;
        padding: 0;
        width: 3.6em;
        background-color: #272744;
        height: 100%; /* Full height */
        position: fixed; /* Make it stick, even on scroll */
        overflow: auto; /* Enable scrolling if the sidenav has too much content */
        font-size: 1.2em;
    }
    li:first-child {
        margin: 1em 0;
    }
    li a {
        display: block;
        color: rgb(255, 255, 255);
        padding: 1.2em 1.4em;
        text-decoration: none;
    }

    li a.active {
        background-color: #282844;
        color: white;
    }

    li a:hover {
        background-color: #292949;
        color: white;
    }
</style>