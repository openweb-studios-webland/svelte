<div class='animated'>animated</div>
<div class='also-animated'>also animated</div>

<style>
	@keyframes why {
		0% { color: red; }
		100% { color: blue; }
	}

	@-webkit-keyframes why {
		0% { color: red; }
		100% { color: blue; }
	}

	@-moz-keyframes why {
		0% { color: red; }
		100% { color: blue; }
	}

	@-o-keyframes why {
		0% { color: red; }
		100% { color: blue; }
	}

	.animated {
		-webkit-animation: why 2s;
		animation: why 2s;
	}

	.also-animated {
		-webkit-animation: not-defined-here 2s;
		animation: not-defined-here 2s;
	}
</style>
