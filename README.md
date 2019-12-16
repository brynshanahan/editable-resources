# Experiments for schemaless editting

So far there are two options we could run with when doing schemaless editting

a) Scoped blocks. Field updates only bubble up to the closest block. Blocks can't access content of blocks nested inside them
b) Nested blocks. Block can access the content of blocks inside of them. Block updates bubble up through every component until it gets to the root of the page
