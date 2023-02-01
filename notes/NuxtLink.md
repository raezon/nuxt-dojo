### Difference between nuxt link and a
1 a it's going to make a fresh request to the server for that about route
`<a href="/about">test</a>`
now the server is then going to accept that and pre-render the about page and it's going to send that pre-rendered page to the browser if you wanna to make it react like an spa nuxtLink will swap it still an anchor tag but it will have abilities that it intercepts any requests to the server then just swaps out the components for theses pages which is  good it's quicker

2 we get active class dynamickly 