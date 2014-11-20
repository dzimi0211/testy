variables:
	{liczbawejsc} = 0
	{wejscia.%player%} = 0
on login:
	add 1 to {liczbawejsc}
	add 1 to {wejscia.%player%}
	send "&6Nasz serwer odwiedzany byl dotad &b&l%{liczbawejsc}% &6razy"
	send "&6Odwiedzasz nas &b&l%{wejscia.%player%}% &6raz"
