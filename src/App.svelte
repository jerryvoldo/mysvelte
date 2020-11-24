<script>
	let people = [
		{name: 'yoshi', beltColour: 'black', age: 25, id: 1},
		{name: 'mario', beltColour: 'orange', age: 45, id: 2},
		{name: 'luigi', beltColour: 'brown', age: 35, id: 3},
	];
</script>

<main>
	<div>
		<h4>{people[0].name}</h4>
		<p>{people[0].beltColour}</p>
	</div>
	<div>
		<h4>{people[1].name}</h4>
		<p>{people[1].beltColour}</p>
	</div>
	<div>
		<h4>{people[2].name}</h4>
		<p>{people[2].beltColour}</p>
	</div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>