# FrankenText
Dette program genererer tilfældige sætninger baseret på teksten fra Frankenstein (pg84.txt).  
Det bruger en simpel Markov-kæde, hvert ord husker hvilket ord der kom efter det i bogen.

# Funktioner
- Læser hele tekstfilen pg84.txt
- Fjerner underlige/usynlige tegn
- Deler teksten op i ord (tokens)
- Gemmer hvilke ord der kan komme efter hinanden
- Genererer:
  - Én sætning der slutter med ?
  - Én sætning der slutter med !