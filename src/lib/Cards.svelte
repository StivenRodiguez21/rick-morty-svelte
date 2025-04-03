<script>
    export let caracter;
</script>
<div class="subcard">
<img src={caracter.image} alt={caracter.name}/>
<h2>{caracter.name}</h2>
<h2>{caracter.species}</h2>
<h2>{caracter.status}</h2>
</div>