<script>
    export let items;

</script>


<style>
    ul{
        list-style: none;
        margin: 1rem;
        padding:0;
    }

    li{
        font-size:1.5rem;
        margin: 1rem;
    }

</style>

<ul>
    {#each books as book}
    <li> {book.title} - {book.price}}</li>
    {/each}
</ul>

<h1> Total : #... </h1>