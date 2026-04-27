const agentes = [
    {
        nome: "Tayane Alves",
        codinome: "Raze",
        funcao: "Duelista de entry",
        idade_estimada: 20-25,
        nacionalidade: "Brasil",
        classe:"Duelista"


    },
    {
        nome: "Amir El Amari",
        codinome: "Cypher",
        funcao: "Lurker",
        idade_estimada: 35-40,
        nacionalidade: "Marrocos",
    
    },
    {
        nome:"Sasha Nokinov",
        codinome:"Sova",
        funcao:"Spot par pegar informação",
        idade_estimada: 30-35,
        nacionalidade:"Tundra da Rússia",
        classe:"iniciador",
    
    },
    {
        nome:"Mateo Armendáriz De la Fuente",
        codinome:"Gekko",
        fun: "Sentinela"

    },
    {
        nome:"Li Zhao Yu",
        codinome:"Iso",
        funcao:"Duelista de combate",
        idade_estimada: 20-22,
        nacionalidade:"China",
        classe:"Duelista",
    },
    {
        nome:"Fred",
        codinome:"Omen",
        funcao:"Smokar",
        idade_estimada: 28-32,
        nacionalidade:"desconhecida",
        classe:"Smoke",
    },
    {
        nome:"Yoru",
        codinome:"Yoru",
        funcao:"Duelista de entry",
        idade_estimada: 25-32,
        nacionalidade:"Japão",
        classe:"Duelista",
    },
    {
        nome:"Liam Byrne",
        codinome:"BrimStone",
        funcao:"smokar",
        idade_estimada: 45-50,
        nacionalidade:"Estados Unidos",
        classe:"Smoke",
    
    },
    {
        nome:"Sasha Nokinov",
        codinome:"Sova",
        funcao:"Spot par pegar informação",
        idade_estimada: 30-35,
        nacionalidade:"Tundra da Rússia",
        classe:"iniciador",
    
    },
    {
        nome:"Mateo Armendáriz De la Fuente",
        codinome:"Gekko",
        funcao:"plantar a spike e pegar informação",
        idade_estimada: 20-25,
        nacionalidade:"Los Angeles EUA",
        classe:"Iniciador",
    
    },
    {
        nome:"Adrijan Vidović",
        codinome:"Miks",
        funcao:"smokar e curar",
        idade_estimada: 20-25,
        nacionalidade:"Croácia",
        classe:"Smoke",
    
    },
    {
        nome:"Iselin",
        codinome:"DeadLock",
        funcao:"Lurker",
        idade_estimada: 20-25,
        nacionalidade:"Noruega",
        classe:"Sentinela",
    
    },
    {
        nome:"Zyanya Mondragón",
        codinome:"Reyna",
        funcao:"Duelista de combate",
        idade_estimada: 25-35,
        nacionalidade:"México",
        classe:"Duelista",
    
    },
    {
        nome:"KAY/0",
        codinome:"KAY/0",
        funcao:"Bangar e pegar Informacao",
        idade_estimada: "é um robo",
        nacionalidade:"desconhecido",
        classe:"Iniciador",
    
    },
    ]

const agentesJSON = JSON.stringify(agentes)
const fs = require("fs")
fs.writeFilesSync("agentes_valorant.json", agentesJSON)







const agenteinfo = require("./agentes_valorant.json")
