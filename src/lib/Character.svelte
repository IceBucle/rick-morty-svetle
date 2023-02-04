<script>
    export let character;
</script>

<div class="character">
    <img src={character.image} alt={character.status} />
    <h1>{character.name}</h1>
    <h3>{character.species} · {character.gender}</h3>
</div>
