
- intro allo studio della mente multidisciplinare
- definizioni di scienze cognitive (ci tengo per dare una definizione di partenza che non cada nel simbolista, perlomeno per avere un glossario "sicuro" su cui posso fare affidamento)
- breve ricapitolo di scienze cognitive pre-1950 (dovrei includerlo? se si, a che lunghezza dovrei puntare? non vorrei appesantire l'introduzione, ma allo stesso tempo penso sia rilevante il passato "simbolista" del ragionamento sulla mente)
- breve ricapitolo di AI pre-1950 (Boole, automata theory [non sono sicuro del livello di dettaglio; fondamenti di computazione potrebbero essere utili nelle parti avanzate, quindi magari dovrei parlarne almeno in uno dei gusti tra funzioni ricorsive (Church), produzioni logiche (Post, non mi ricordo niente) o macchine di Turing], cibernetica)
- comportamentismo in 50s
- 1956 pivotal year:
    - rilevanza degli studi di Miller e perché implicano qualche tipo di rappresentazione mentale, presentati September 11, 1956, the second day of a Symposiumon Information Theory at MIT (mention the HUGE number of people)
    - Dartmouth College workshop: principali figure e stato dell'arte
- risultato: shift delle scienze cognitive dal lato simbolico-rappresentazionalista (penso che sia importante parlare di 1957 Syntactic Structures e la review di verbal behavior, in un paragrafo chiamato Psycholinguistics [+Bates e cognitive interactionist]) e nascita di AI research come programmi simbolici. vorrei fare un'overview (informatica) del Logic Theorist


- 1960-70
Ross Quillian semantic network!!!!!!!


NEURO: neural network neurophysiologist Warren McCulloch and logician Walter Pitts; 
Donald Hebb fire together get stronger; Rosenblatt perceptron
INFO: LT to GPS; Ross Quillian semantic network; Minsky critique of NN 1969; Rosen team build shakey, Winograd SHRLDU (70s?). 
PSYCH: 1960 Miller-Bruner center for Cognitive Studies; 1968 Atkinson-Shiffrin integrate sensory memory (Sperling), short-term memory (Peterson),  and  the  distinction  between  short-term and long-term memory (William James; Waugh and Norman). Lynn Cooper and Jacqueline Metzler show that figuring out a rotation scales linearly with how rotated the figure is (mental model?). 1967, Ulric Neisser "cognitive psychology". 

- 1970-1985
- minsky
- expert systems, knowledge-based
AI: 
1976 Physical Symbol Systems Hypothesis newell-simon (important! we need later)
- AI winter 

    - connectionism? Minsky critique. 
    - large problems? SAT is NP (Cook 1971) so only exp. 
    - symbolic reasoning, sure, but sensorimotor? WAY harder (moravec's paradox).
    - Logic-based? not sure what the problem was)
    - Searle chinese room
    - ELIZA-weizenbaum -> Colby
- expert systems and connectionism reborn
    - definition and a couple examples
    - 1982 Hopfield proves NN learn, Hinton-Rumelhart popularize backpropagation (and hidden layers!), 1986 "Parallel Distributed Processing", 1988 Pinker and Prince eliminativism (symbolic theories are crude approximations of the brain and we must give way to connectionism)
    
COGSCI:
- 1977 journal "cognitive science" is born
- PSSH -> computational theory of mind
- classical cognitive science: cognitive modeling (1975-1985)
    - most prominent: Chomsky 1981 "CS research in fact fell short of the scope even its original symbol-processing framework provided."
A third researcher, Gordon Bower,
moved from mathematical models of learning towards
more cognitively oriented work on the nature of
mental representations. One of his students, John
Anderson, worked with Bower on a very influential
semantic network model (HAM), that was described
in their 1973 book, Human Associatie Memory. Later
Anderson combined it with a production system
component in ACT* and its predecessors.

- 1987-1993
- second AI winter
    - expert systems can't learn, too expensive, brittle. Japan's fifth generation concludes nothing.
    - embodied approach:
        AI -> robotics, Brooks against PSSH, rediscover cybernetics, Marr's vision plan.
        COGSCI -> embodied and situated cognition
            - Suchman 1987 and how people rely on environment
            
1993–2000s
AI: 
    - field becomes "rigorous"
    - new paradigm: intelligent agents (pearl, newell) from economics to AI, take into account environment.
    - probability comes in with pearl "Probabilistic Reasoning in Intelligent Systems" (bayesian networks, hidden markov models, stochastic modeling)
    - AI-derived work changes name
COGCI:
    - from "symbolic" system to situated cognition (environment) to social cognition (Lave 1988)
    - groups research, coopeartive work, knowledge engineering
intelligent agents and cooperation is common theme. integrated architectures with cognitive and social interaction in both fields.

2000-present
AI:
    - machine learning and NN prevalent
    - detailed descriptions of some modern architectures (LSTM, maybe GRU)
    - neuro-symbolic systems (new? not really: Connectionist-Symbolic Integration: From Unified to Hybrid Approaches 2002)

I cant find sources for COGSCI side of things. They're all old. Should I branch out into psychology + neurophysiology + linguistics or try to stick to "cognitive science"?

nunez cognitive science or not (topics in cognitive science)
still embodied cognition
cognitive science society
still: enactivism-anti representational-embodied/social
companion of cognitive science wiley

Dopo la parte "storica" (integrale e non considerata un'introduzione ma parte del contenuto) posso dedicarmi alle due riflessioni fondamentali (che però non so quanto saranno lunghe):
1. Analisi di come (a livello temporale) si siano influenzate le scienze cognitive e lo studio dell'intelligenza artificiale. Il fulcro dell'analisi sarà grafico: voglio disegnare due timeline a fasce colorate che mostrino, un paper per volta, come i due campi si siano mossi da una parte all'altra dello spettro per fermarsi su una visione intermedia (che poi, per le scienze cognitive ancora non lo so. lo assumo però).
2. Rappresentazioni tra simboli e subsimboli. La discussione era centrale dopo il paper di Fodor e Pylyshyn, e più recentemente con l'estrazione di simboli (cioè spiegazioni in termini di concetti) dagli schemi di attivazione delle reti neurali nelle ricerche di explainable AI, ma non sono sicuro se dovrei affrontarlo anche da un punto di vista filosofico o no. Non penso di averne gli strumenti.
Potrei anche fare una piccola appendice sui modelli di calcolo, e perché il riconoscimento sintattico è computazionale ma semantico no