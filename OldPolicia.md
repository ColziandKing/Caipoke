

        {
            "name": "Trade Unions",
            "uniques": [
		    "Provides [3] [Nutmeg]","Provides [3] [Cloves]","Provides [3] [Pepper]","Provides [1] [Policies]"
            ],
            "row": 2,
            "column": 1
        },
            {
                "name": "Free Religion",
                "uniques": ["[-10]% Culture cost of adopting new Policies","Provides [1] [Policies]"],
                "row": 2,
                "column": 5
            },
	{
        "name": "Democracy",
        "era": "Modern era",
        "uniques": [
			"Adopt [Constitution]","Free Social Policy","Only available <before adopting [World]>","Provides [1] [Policies]"
        ],
        "policies": [
            {
                "name": "Merchant Confederacy",
                "uniques": [
			"Gain a free [Grocer] [in all cities]","Provides [3] [Glass]",
		    "Provides [3] [Jewelry]","Provides [3] [Porcelain]" 
		],
                "row": 1,
                "column": 1
            },
            {
                "name": "Merchant Navy",
                "uniques": [
            "Gain a free [Harbor] [in all coastal cities]","Gain a free [Military Base] [in all coastal cities]","Land units may cross [Mountain] tiles after the first [Great General] is earned","Comment [Units ending their turn on [Mountain] tiles take [50] damage]"
                ],
                "row": 1,
                "column": 5
            },
		{
                "name": "Constitution",
                "uniques": [
                    
			"[+1 Food, +1 Production] from every specialist [in all cities]"
                ],
                "row": 1,
                "column": 3
            },
            {
                "name": "Their Finest Hour",
                "uniques": ["[+44]% Strength for cities <when defending>"],
                "requires": ["Constitution"],
                "row": 2,
                "column": 2
            },
        {
            "name": "Distributed Sovereignty",
            "uniques": [
            "[+1 Production, +1 Science] from every [Amphitheater]",
            "[+1 Production, +1 Science] from every [Museum]",
            "[+1 Production, +1 Science] from every [Opera House]",
            "[+1 Production, +1 Science] from every [Broadcast Tower]",
            "[+1 Production, +1 Science] from every [Great Work]",
            "[+50]% Production when constructing [Amphitheater] buildings [in all cities]",
            "[+50]% Production when constructing [Opera House] buildings [in all cities]",
            "[+50]% Production when constructing [Museum] buildings [in all cities]",
            "[+50]% Production when constructing [Broadcast Tower] buildings [in all cities]"
            ],
            "requires": ["Constitution"],
            "row": 2,
            "column": 4
        },
		{
                "name": "Optimization Imperative",
                "uniques": [
			"[+5 Science] [in all cities]",
			"[+50]% Yield from every [Land Trade Route (Food)]",
            "[+50]% Yield from every [Land Trade Route (Production)]",
			"Provides [1] [Policies]",
            "[+50]% Yield from every [Sea Trade Route (Food)] <hidden from users>",
            "[+50]% Yield from every [Sea Trade Route (Production)] <hidden from users>"
                ],
                "requires": ["Their Finest Hour","Distributed Sovereignty"],
                "row": 3,
                "column": 3
            },
            {
                "name": "Democracy Complete",
                "uniques": [
                    "[+10]% [Food] [in all cities]","Earn [100]% of killed [Military] unit's [Strength] as [Science]",
                    "[+3 Production, +3 Gold, +3 Food] from every [Courthouse]",
                    "May buy [Great General] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
                ]
            }
        ]
    },
	{
        "name": "World",
        "era": "Modern era",
        "uniques": [
			"Adopt [Sharia]","Free Social Policy","Only available <before adopting [Democracy]>","Provides [1] [Policies]"
        ],
        "policies": [
		{
                "name": "Populism",
                "uniques": [
                    "[+15]% Strength <for [Military] units> <in [Friendly Land] tiles>",
                    "Free [Worker] appears"
                ],
                "row": 1,
                "column": 1
            },
	{
            "name": "Planned Economy",
            "uniques": [
                "[+100]% unhappiness from the number of cities",
            "[-50]% Unhappiness from [Population] [in all cities]"
            ],
            "row": 1,
            "column": 5
        },
            {
                "name": "Sharia",
                "uniques": [
			"[-50 Happiness] per [5] population [in all cities]"
		],
                "row": 1,
                "column": 3
            },
		{
                "name": "Nazism",
                "uniques": [
			"[+20]% Strength <for [All] units> <when fighting in [Enemy Land] tiles>","[Faith] cost of purchasing [Inquisitor] units [-80]%"
                ],
                "requires": ["Populism"],
                "row": 2,
                "column": 2
            },
        {
            "name": "Dictatorship of the Proletariat",
            "uniques": [
                "Free [Atomic Bomb] appears","Empire enters golden age <upon conquering a city>","Provides [1] [Policies]"
            ],
            "requires": ["Planned Economy"],
            "row": 2,
            "column": 4
        },
        {
            "name": "Scorched Earth",
            "uniques": [
                "[-100]% maintenance costs <for [Mounted] units>",
            "[-100]% maintenance costs <for [Armor] units>",
            "[Mounted] units gain the [Volley] promotion",
            "[Armor] units gain the [Volley] promotion",
		    "Provides [1] [Policies]"
            ],
            "requires": ["Nazism","Sharia","Dictatorship of the Proletariat"],
            "row": 3,
            "column": 3
        },
            {
                "name": "World Complete",
                "uniques": [
                    "[+10]% [Food] [in all cities]","Earn [100]% of killed [Military] unit's [Strength] as [Science]",
                    "[+3 Production, +3 Gold, +3 Food] from every [Courthouse]",
                    "May buy [Great General] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
                ]
            }
        ]
	
            {
                "name": "Their Finest HourFree Religion",
                "uniques": ["[+44]% Strength for cities <when defending>","[-10]% Culture cost of adopting new Policies"],
                "requires": ["Populism"],
                "row": 2,
                "column": 1
            },
	    rapid deployment is their finest hour "[+33]% Strength for cities <when defending>", you may add
Diplomatic Marriage, MerchantConfederacy, "[+3 Happiness, +1 Faith, +2 Food] from every [Palace]","Only available <in cities with a [Kingdom Hall]>",
,
    "Starts with [Order] adopted","Starts with [Party Leadership] adopted","Starts with [Socialist Realism] adopted","Starts with [Patriotic War] adopted",
    "Starts with [Double Agents] adopted","Starts with [Young Pioneers] adopted",
    "Starts with [Freedom] adopted","Starts with [Avant Garde] adopted","Starts with [Creative Expression] adopted","Starts with [Civil Society] adopted",
    "Starts with [Volunteer Army] adopted","Starts with [Covert Action] adopted""[+4 Gold] from each Trade Route",
    
    {
        "name": "Haciendo",
        "replaces": "Colosseum",
        "uniqueTo": "Gran Colombia",
        "production": 2,
        "gold": 3,
        "culture": 1,
        "hurryCostModifier": 25,
        "requiredTech": "Construction",
        "uniques": [
            "[+3 Production, +2 Gold] <after discovering [Industrialization]>"
        ]
    },
,
    "Starts with [Autocracy] adopted","Starts with [Militarism] adopted","Starts with [Fascism] adopted","Starts with [Mobilization] adopted",
    "Starts with [Futurism] adopted","Starts with [Industrial Espionage] adopted"

    {
        "name": "Itinerant Preachers",
        "type": "Enhancer",
        "uniques": ["Religion naturally spreads to cities [+3] tiles away",
            "Only available <after adopting [Reformation]>"]
    },

    {
        "name": "Religious Settlements",
        "type": "Pantheon",
        "uniques": [
            "[+25]% Production when constructing [Settler] units [in this city]",
            "[-15]% Culture cost of natural border growth [in this city]",
            "Only available <after adopting [Mysticism]>"
        ]
    },
			"Grants [Water of Life] ([+10 HP when healing]) to adjacent [Land] units for the rest of the game"
	/*
	{
		"name": "Atoll",
		"type": "TerrainFeature",
		"movementCost": 1,
		"food": 1,
		"production": 1,
		"occursOn": ["Coast"],
		"uniques": ["Rare feature"]
	},

	// Natural Wonders
	{
		"name": "Great Barrier Reef",
		"type": "NaturalWonder",
		"food": 2,
		"production": 1,
		"gold": 1,
		"science": 2,
		"occursOn": ["Ocean"],
		"uniques": ["Must be adjacent to [1] to [6] [Coast] tiles",
			"Must be adjacent to [6] [Water] tiles",
			"Occurs on latitudes from [10] to [70] percent of distance equator to pole",
			"Occurs in groups of [2] to [2] tiles"],
		"turnsInto": "Coast",
		"impassable": true,
		"unbuildable": true,
		"weight": 10
	},
	{
		"name": "Old Faithful",
		"type": "NaturalWonder",
		"science": 2,
		"happiness": 3,
		"occursOn": ["Grassland","Plains","Tundra","Mountain"],
		"uniques": ["Must be adjacent to [0] [Coast] tiles",
			"Must be adjacent to [0] to [4] [Mountain] tiles",
			"Must be adjacent to [3] to [6] [Elevated] tiles",
			"Must be adjacent to [0] to [3] [Desert] tiles",
			"Must be adjacent to [0] to [3] [Tundra] tiles"],
		"turnsInto": "Mountain",
		"impassable": true,
		"unbuildable": true,
		"weight": 10
	},
	{
		"name": "El Dorado",
		"type": "NaturalWonder",
		"culture": 5,
		"overrideStats": true,
		"occursOn": ["Plains"],
		"turnsInto": "Plains",
		"impassable": true,
		"unbuildable": true,
		"uniques": ["Must be adjacent to [0] [Coast] tiles",
			"Must be adjacent to [1] to [6] [Jungle] tiles",
			"Grants 500 Gold to the first civilization to discover it"],
		"weight": 2
	},
	{ 
		"name": "Fountain of Youth",
		"type": "NaturalWonder",
		"happiness": 10,
		"overrideStats": true,
		"occursOn": ["Plains"],
		"turnsInto": "Plains",
		"impassable": true,
		"unbuildable": true,
		"uniques": ["Must be adjacent to [0] [Coast] tiles",
			"Grants [Rejuvenation] ([all healing effects doubled]) to adjacent [{Military} {Land}] units for the rest of the game",
			"Tile provides yield without assigned population"],
		"weight": 1
	},
	{
		"name": "Grand Mesa",
		"type": "NaturalWonder",
		"production": 2,
		"gold": 3,
		"occursOn": ["Plains","Desert","Tundra"],
		"uniques": ["Must be adjacent to [0] [Coast] tiles",
			"Must be adjacent to [0] [Grassland] tiles",
			"Must be adjacent to [2] to [6] [Hill] tiles",
			"Must be adjacent to [0] to [2] [Mountain] tiles"],
		"turnsInto": "Mountain",
		"impassable": true,
		"unbuildable": true,
		"weight": 10
	},
	{
		"name": "Mount Fuji",
		"type": "NaturalWonder",
		"gold": 2,
		"culture": 3,
		"faith": 3,
		"occursOn": ["Grassland","Plains"],
		"uniques": ["Must be adjacent to [0] [Coast] tiles",
			"Must be adjacent to [0] [Tundra] tiles",
			"Must be adjacent to [0] [Desert] tiles",
			"Must be adjacent to [0] [Mountain] tiles",
			"Must be adjacent to [0] [Marsh] tiles",
			"Must be adjacent to [0] to [2] [Hill] tiles",
			"Must not be on [1] largest landmasses"],
		"turnsInto": "Mountain",
		"impassable": true,
		"unbuildable": true,
		"weight": 10
	},
	{
		"name": "Krakatoa",
		"type": "NaturalWonder",
		"science": 5,
		"occursOn": ["Ocean"],
		"uniques": ["Must be adjacent to [1] to [6] [Coast] tiles",
			"Must be adjacent to [0] [Ice] tiles",
			"Neighboring tiles will convert to [Coast]"],
		"turnsInto": "Mountain",
		"impassable": true,
		"unbuildable": true,
		"weight": 10
	},
	{
		"name": "Rock of Gibraltar",
		"type": "NaturalWonder",
		"food": 2,
		"gold": 5,
		"occursOn": ["Grassland"],
		"uniques": ["Must be adjacent to [1] to [5] [Coast] tiles",
			"Must be adjacent to [1] [Mountain] tiles",
			"Neighboring tiles except [Mountain] will convert to [Coast]"],
		"turnsInto": "Mountain",
		"impassable": true,
		"unbuildable": true,
		"weight": 10
	},
	{
		"name": "Cerro de Potosi",
		"type": "NaturalWonder",
		"gold": 10,
		"occursOn": ["Plains","Mountain"],
		"uniques": ["Must be adjacent to [0] [Coast] tiles",
			"Must be adjacent to [1] to [6] [Hill] tiles"],
		"turnsInto": "Mountain",
		"impassable": true,
		"unbuildable": true,
		"weight": 5
	},
	{
		"name": "Barringer Crater",
		"type": "NaturalWonder",
		"gold": 2,
		"science": 3,
		"occursOn": ["Desert","Tundra"],
		"uniques": ["Must be adjacent to [0] [Coast] tiles",
			"Must be adjacent to [0] [Grassland] tiles",
			"Must be adjacent to [0] to [2] [Mountain] tiles",
			"Must be adjacent to [0] to [4] [Elevated] tiles"],
		"turnsInto": "Mountain",
		"impassable": true,
		"unbuildable": true,
		"weight": 10
	},
	// G&K Wonders
	{
		"name": "Mount Kailash",
		"type": "NaturalWonder",
		"faith": 6,
		"happiness": 2,
		"occursOn": ["Plains","Grassland"],
		"uniques": ["Must be adjacent to [0] [Coast] tiles",
			"Must be adjacent to [0] [Marsh] tiles",
			"Must be adjacent to [0] to [1] [Desert] tiles",
			"Must be adjacent to [4] to [6] [Elevated] tiles"],
		"turnsInto": "Mountain",
		"impassable": true,
		"unbuildable": true,
		"weight": 10
	},
	{
		"name": "Mount Sinai",
		"type": "NaturalWonder",
		"faith": 8,
		"occursOn": ["Desert","Plains"],
		"uniques": ["Must be adjacent to [0] [Coast] tiles",
			"Must be adjacent to [0] [Grassland] tiles",
			"Must be adjacent to [0] [Tundra] tiles",
			"Must be adjacent to [0] [Marsh] tiles",
			"Must be adjacent to [3] to [6] [Desert] tiles"],
		"turnsInto": "Mountain",
		"impassable": true,
		"unbuildable": true,
		"weight": 10
	},
	{
		"name": "Sri Pada",
		"type": "NaturalWonder",
		"food": 2,
		"faith": 4,
		"happiness": 2,
		"occursOn": ["Plains","Grassland"],
		"uniques": ["Must be adjacent to [0] [Tundra] tiles",
			"Must be adjacent to [0] [Desert] tiles",
			"Must be adjacent to [0] [Marsh] tiles",
			"Must not be on [1] largest landmasses"],
		"turnsInto": "Mountain",
		"impassable": true,
		"unbuildable": true,
		"weight": 10
	},
	{
		"name": "Uluru",
		"type": "NaturalWonder",
		"food": 2,
		"faith": 6,
		"occursOn": ["Plains","Desert"],
		"uniques": ["Must be adjacent to [0] [Coast] tiles",
			"Must be adjacent to [0] [Grassland] tiles",
			"Must be adjacent to [0] [Tundra] tiles",
			"Must be adjacent to [0] [Marsh] tiles",
			"Must be adjacent to [3] to [6] [Plains] tiles"],
		"turnsInto": "Mountain",
		"impassable": true,
		"unbuildable": true,
		"weight": 10
	},

	// BNW wonders
	{
		"name": "King Solomon's Mines",
		"type": "NaturalWonder",
		"production": 6,
		"overrideStats": true,
		"occursOn": ["Plains","Desert"],
		"uniques": ["Must be adjacent to [0] [Coast] tiles",
			"Must be adjacent to [0] to [2] [Mountain] tiles"],
		"turnsInto": "Plains",
		"impassable": true,
		"unbuildable": true,
		"weight": 4
	},
	{
		"name": "Lake Victoria",
		"type": "NaturalWonder",
		"food": 6,
		"occursOn": ["Plains"],
		"turnsInto": "Mountain",
		"impassable": true,
		"unbuildable": true,
		"uniques": ["Fresh water","Must be adjacent to [0] [Coast] tiles"],
		"weight": 10
	},
	{
		"name": "Mount Kilimanjaro",
		"type": "NaturalWonder",
		"food": 3,
		"culture": 2,
		"occursOn": ["Plains","Grassland"],
		"turnsInto": "Mountain",
		"impassable": true,
		"unbuildable": true,
		"uniques": ["Must be adjacent to [0] [Coast] tiles",
			"Must be adjacent to [2] to [6] [Hill] tiles",
			"Must be adjacent to [0] to [2] [Mountain] tiles",
			"Grants [Altitude Training] ([double movement and +10% Strength in hills]) to adjacent [Land] units for the rest of the game"],
		"weight": 10
	}
	{
        "name": "Holy Order",
        "type": "Enhancer",
        "uniques": ["[Faith] cost of purchasing [Missionary] units [-30]%", "[Faith] cost of purchasing [Inquisitor] units [-30]%"]
    },
    {
        "name": "Itinerant Preachers",
        "type": "Enhancer",
        "uniques": ["Religion naturally spreads to cities [+3] tiles away"]
    },
    {
        "name": "Just War",
        "type": "Enhancer",
        "uniques": ["[+20]% Strength <for [All] units> <when fighting in [Enemy Land] tiles>"]
        // ToDo: Should only be enemy territory of cities that follow this religion
    },
    {
        "name": "Messiah",
        "type": "Enhancer",
        "uniques": ["[+25]% Spread Religion Strength <for [Great Prophet] units>", "[-25]% Faith cost of generating Great Prophet equivalents"]
    },
    {
        "name": "Missionary Zeal",
        "type": "Enhancer",
        "uniques": ["[+25]% Spread Religion Strength <for [Missionary] units>"]
    },
    {
        "name": "Religious Texts",
        "type": "Enhancer",
        "uniques": ["[+34]% Natural religion spread [in all cities]", "[+34]% Natural religion spread [in all cities] <after discovering [Printing Press]>"]
    },
    {
        "name": "Religious Unity",
        "type": "Enhancer",
        "uniques": ["[+100]% Natural religion spread [in City-State cities]"]
    },
    {
        "name": "Reliquary",
        "type": "Enhancer",
        "uniques": ["Gain [50] [Faith] <upon expending a [Great Person] unit> <(modified by game speed)>"]
    }
    "[+2 Gold] [in capital]",
			"[+4 Culture] from each Trade Route","[+2 Culture] [in capital]","Gain a free [Palengke] [in capital]",
  {
 "All cities provide 1 copy of [Porcelain] luxury resource,"[+2 Food] [in capital]","[+4 Production] from [All] tiles [in capital]",
			"[+2 Gold] from [All] tiles [in all cities]",
    "Starts with [Autocracy] adopted","Starts with [Freedom] adopted","Starts with [Ideology] adopted","Starts with [Order] adopted",
    "Starts with [Tradition] adopted","Starts with [Liberty] adopted","Starts with [Patronage] adopted","Starts with [Commerce] adopted",
    "Starts with [Piety] adopted","Starts with [Rationalism] adopted","Starts with [Honor] adopted",
                    //"[+15]% Production when constructing [Hotel] buildings [in all cities]",
                    //"[-20]% Gold cost of upgrading <for [Military] units>",
                    //"[+33]% Production when constructing [National Visitor's Center] wonders [in all cities]",
{
		"name": "Carnival",
		"happiness": 2,
		"faith": 2,
		"maintenance": 4,
		"requiredTech": "Plastics"
	},
	{
        	"name": "Hypermarket",
        	"cost": 400,
		"food": 3,
		"production": 2,
		"maintenance": 4,
		"percentStatBonus": {"gold": 10},
		"requiredTech": "Replaceable Parts"
   	},
	{
        	"name": "Mall",
		"uniqueTo": "Colziand",
        	"cost": 400,
		"food": 2,
		"culture": 2,
		"maintenance": 4,
		"percentStatBonus": {"gold": 20},
    		"replaces": "Hypermarket",
		"requiredTech": "Replaceable Parts"
   	},
	{
		"name": "Department Store",
		"production": 2,
		"gold": 2,
		"requiredTech": "Electronics"
		"maintenance": 4,
	},
	{
		"name": "Aquarium",
		"happiness": 2,
		"science": 2,
		"requiredTech": "Plastics"
		"maintenance": 4,
	},
    {
        "name": "Alnwick ",
        "cost": 150,
        "replaces": "Castle",
        "uniqueTo": "India",
        "cityStrength": 7,
        "cityHealth": 25,
        "culture": 4,
        "happiness": 2,
        "hurryCostModifier": 25,
        "uniques": [
            "[+2 Culture] [in this city] <after discovering [Flight]>",
            "Destroyed when the city is captured"
        ],
        "requiredTech": "Chivalry"
    },
{
        "name": "Ideology",
        "era": "Modern era",
        "uniques": [
            "Free Social Policy",
            "Unavailable"
        ],
        "policies": [
            {
                "name": "Ideology Complete",
                "uniques": [
                    "Comment [Report as error if you adopt this]"
                ]
            }
        ]
//aa

	///City-Nations
	//Cultured
	{
        "name": "Baku",
        "adjective": ["Azerbaijani"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [
			249,
			249,
			249
		],
		"innerColor": [
			10,
			105,
			36
		],

	"leaderName": "Ayaz Mutallibov",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Culture] from each Trade Route","[+2 Culture] [in capital]"],
        "cities": ["Baku","Luxembourg"]
    },
    {
        "name": "Chaco Canyon",
        "adjective": ["Chacoan"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [255, 217, 143],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Culture] from each Trade Route","[+2 Culture] [in capital]"],
        "cities": ["Chaco Canyon","Monaco"]
    },
    {
        "name": "Djibouti",
        "adjective": ["Djiboutian"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [230, 166, 82],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Culture] from each Trade Route","[+2 Culture] [in capital]"],
        "cities": ["Djibouti","Kyzyl"]
    },
    {
        "name": "Kuwait City",
        "adjective": ["Kuwati"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [230,230,230],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Culture] from each Trade Route","[+2 Culture] [in capital]"],
        "cities": ["Kuwait City","Kuala Lumpur"]
    },
    {
        "name": "Ljubljana",
        "adjective": ["Slovenian"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [18,204,245],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Culture] from each Trade Route","[+2 Culture] [in capital]"],
        "cities": ["Ljubljana","Montevideo"]
    },
    {
        "name": "Nicosia",
        "adjective": ["Nicosia"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [172, 30, 185],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Culture] from each Trade Route","[+2 Culture] [in capital]"],
        "cities": ["Nicosia","Reykjavik"]
    },
    {
        "name": "Thimphu",
        "adjective": ["Thimphuan"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [54, 102, 255],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Culture] from each Trade Route","[+2 Culture] [in capital]"],
        "cities": ["Thimphu","Teheran"]
    },
	//Maritime
    {
        "name": "Bangkok",
        "adjective": ["Bangkokian"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [179, 154, 255],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Food] from each Trade Route","[+2 Food] [in capital]"],
        "cities": ["Bangkok","Islamabad"]
    },
    {
        "name": "Kampala",
        "adjective": ["Kampalan"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [172, 30, 185],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Food] from each Trade Route","[+2 Food] [in capital]"],
        "cities": ["Kampala","Mogadishu"]
    },
    {
        "name": "Lima",
        "adjective": ["Liman"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [196, 87, 255],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Food] from each Trade Route","[+2 Food] [in capital]"],
        "cities": ["Lima","Cape Town"]
    },
    {
        "name": "Lusaka",
        "adjective": ["Lusakan"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [125, 224, 0],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Food] from each Trade Route","[+2 Food] [in capital]"],
        "cities": ["Lusaka","Ormus"]
    },
    {
        "name": "Panama City",
        "adjective": ["Panamanian"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [255, 255, 128],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Food] from each Trade Route","[+2 Food] [in capital]"],
        "cities": ["Panama City","Paramaribo"]
    },
    {
        "name": "Phnom Penh",
        "adjective": ["Phnom Penher"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [25,75,235],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Food] from each Trade Route","[+2 Food] [in capital]"],
        "cities": ["Phnom Penh","Riga"]
    },
    {
        "name": "Port-au-Prince",
        "adjective": ["Haitian"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [128, 255, 128],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Food] from each Trade Route","[+2 Food] [in capital]"],
        "cities": ["Port-au-Prince","Cahokia"]
    },
	//Mercantile
    {
        "name": "Dubai",
        "adjective": ["Emirati"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [248,
			217,
			2],
        "innerColor": [21,
			108,
			49],
	"leaderName": "Rashid bin Saeed Al Maktoum",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Gold] from each Trade Route","[+2 Gold] [in capital]"],
        "cities": ["Dubai","Gaborone"]
    },
    {
        "name": "Lagos",
        "adjective": ["Lagosian"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [128, 255, 128],
	"leaderName": "Bola Tinubu",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Gold] from each Trade Route","[+2 Gold] [in capital]"],
        "cities": ["Lagos","Hong Kong"]
    },
    {
        "name": "Malacca",
        "adjective": ["Malacca"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [18, 204, 245],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Gold] from each Trade Route","[+2 Gold] [in capital]"],
        "cities": ["Malacca","Maseru"]
    },
    {
        "name": "Tallinn",
        "adjective": ["Tallinner"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [0, 163, 181],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Gold] from each Trade Route","[+2 Gold] [in capital]"],
        "cities": ["Tallinn","Trieste"]
    },
    {
        "name": "Vaduz",
        "adjective": ["Liechtensteiner"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [196, 87, 255],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Gold] from each Trade Route","[+2 Gold] [in capital]"],
        "cities": ["Vaduz","Zurich"]
    },
	//Militaristic
    {
        "name": "Andorra",
        "adjective": ["Andorran"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [230, 166, 82],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Happiness] from each Trade Route","[+2 Happiness] [in capital]"],
        "cities": ["Andorra","Colchis"]
    },
    {
        "name": "Cyrene",
        "adjective": ["Cyreni"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [18, 204, 245],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Happiness] from each Trade Route","[+2 Happiness] [in capital]"],
        "cities": ["Cyrene","Tirana"]
    },
    {
        "name": "Harappa",
        "adjective": ["Harappan"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [179, 154, 255],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Happiness] from each Trade Route","[+2 Happiness] [in capital]"],
        "cities": ["Harappa","Valletta"]
    },
    {
        "name": "Havana",
        "adjective": ["Habanero"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [128, 255, 128],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Happiness] from each Trade Route","[+2 Happiness] [in capital]"],
        "cities": ["Havana","Troy"]
    },
	//Religious
    {
        "name": "Qufu",
        "adjective": ["Qufu"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [255, 255, 128],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Faith] from each Trade Route"],
        "cities": ["Qufu","Taipei"]
    },
    {
        "name": "Sarajevo",
        "adjective": ["Sarajlija"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [128, 255, 128],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Faith] from each Trade Route"],
        "cities": ["Sarajevo","Kathmandu"]
    },
    {
        "name": "Wittenberg",
        "adjective": ["Wittenberg"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [179, 154, 255],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Faith] from each Trade Route"],
        "cities": ["Wittenberg","Geneva"]
    },
	//ProductionScience
	
    {
        "name": "Santo Domingo",
        "adjective": ["Dominican"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [0,163,181],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Production] from each Trade Route","[+2 Production] [in capital]"],
        "cities": ["Santo Domingo","Colombo"]
    },
    {
        "name": "Singapore",
        "adjective": ["Singaporean"],
        "declaringWar": "We have wanted this for a LONG time. War it shall be.",
        "attacked": "Very well, we will kick you back to the ancient era!",
        "defeated": "This isn't how it is supposed to be!",
        "outerColor": [0, 0, 0],
        "innerColor": [255, 255, 128],
	"leaderName": "Unknown",
        "startIntroPart1": " ",
        "startIntroPart2": " ",
        "introduction": "Welcome, mighty leader.",
        "neutralHello": "Greetings.",
        "hateHello": "What do you want?",
        "tradeRequest": "Better hurry, I may change my mind.",
        "uniqueName": "Same Decree",
        "uniques": ["[+4 Science] from each Trade Route","[+2 Science] [in capital]"],
        "cities": ["Singapore","Mohenjo-Daro"]
    },
 //aa
	{
		"name": "Hacienda",
		"uniqueTo": "Gran Colombia",
		"production": 1,
		"gold": 2,
		"turnsToBuild": 7,
		"terrainsCanBeBuiltOn": [
			"Grassland",
			"Plains",
			"Hill"
		],
		"uniques": [
			"[+1 Food] <with [2] to [3] neighboring [Plantation] tiles> <before discovering [Replaceable Parts]>",
			"[+2 Food] <with [4] to [5] neighboring [Plantation] tiles> <before discovering [Replaceable Parts]>",
			"[+3 Food] <with [6] to [6] neighboring [Plantation] tiles> <before discovering [Replaceable Parts]>",
			"[+1 Food] for each adjacent [Plantation] <after discovering [Replaceable Parts]>",
			"[+1 Production] <with [2] to [3] neighboring [Hacienda] tiles> <before adopting [Mercantilism]>",
			"[+2 Production] <with [4] to [5] neighboring [Hacienda] tiles> <before adopting [Mercantilism]>",
			"[+3 Production] <with [6] to [6] neighboring [Hacienda] tiles> <before adopting [Mercantilism]>",
			"[+1 Production] for each adjacent [Hacienda] <after adopting [Replaceable Parts]>",
			"Cannot be built on [Grassland] tiles <before adopting [Mercantilism]>",
			"Cannot be built on [Plains] tiles <before adopting [Mercantilism]>",
			"Cannot be built on [Hill] tiles <in [{Grassland} {Hill}] tiles> <before adopting [Mercantilism]>",
			"Cannot be built on [Hill] tiles <in [{Plains} {Hill}] tiles> <before adopting [Mercantilism]>",
			"Cannot be built on [Hill] tiles <in [{Desert} {Hill}] tiles>",
			"Cannot be built on [Hill] tiles <in [{Tundra} {Hill}] tiles>",
			"Cannot be built on [Hill] tiles <in [{Snow} {Hill}] tiles>",
		]
	},
	{
		"name": "Kurgan",
		"uniqueTo": "Scythia",
		"faith": 1,
		"gold": 3,
		"turnsToBuild": 7,
		"techRequired": "Animal Husbandry",
		"terrainsCanBeBuiltOn": [
			"Grassland",
			"Plains",
			"Desert",
			"Tundra",
			"Snow"
		],
		"uniques": [
			"[+1 Faith] for each adjacent [Pasture]",
			"[+1 Faith] for each adjacent [Pasture] <after discovering [Horseback Riding]>",
			"Cannot be built on [Hill] tiles",
		]
	},
	{
		"name": "Mekewap",
		"uniqueTo": "The Cree",
		"production": 1,
		"gold": 2,
		"turnsToBuild": 7,
		"techRequired": "Pottery",
		"terrainsCanBeBuiltOn": [
			"Grassland",
			"Plains",
			"Desert",
			"Hill",
			"Tundra",
			"Snow"
		],
		"uniques": [
			"[+1 Food, +1 Production] <after adopting [Civil Service]>",
			"[+2 Gold] for each adjacent [Luxury resource] <after discovering [Navigation]>",
			"[+1 Food] <with [2] to [3] neighboring [Bonus resource] tiles> <before adopting [Mercantilism]>",
			"[+2 Food] <with [4] to [5] neighboring [Bonus resource] tiles> <before adopting [Mercantilism]>",
			"[+3 Food] <with [6] to [6] neighboring [Bonus resource] tiles> <before adopting [Mercantilism]>",
			"[+1 Food] for each adjacent [Bonus resource] <after adopting [Mercantilism]>",
			"Cannot be built on [All] tiles <with [1] to [6] neighboring [Mekewap] tiles>",
			"Cannot be built on [All] tiles <with [0] to [0] neighboring [Bonus resource] tiles>",
			"Cannot be built on [All] tiles <with [0] to [0] neighboring [Luxury resource] tiles>",
		]
	},
	{
		"name": "Chemamull",
		"uniqueTo": "The Mapuche",
		"production": 1,
		"turnsToBuild": 7,
		"terrainsCanBeBuiltOn": [
			"Grassland",
			"Plains",
			"Desert",
			"Hill",
			"Tundra",
			"Snow"
		],
		"uniques": [
			"[+2 Culture] for each adjacent [Natural Wonder]",
			"[+1 Culture] for each adjacent [Mountain]",
			"[+1 Culture] for each adjacent [Forest]",
			"[+1 Culture] for each adjacent [Coast]",
			"[+1 Culture] for each adjacent [Oasis]",
			"[+1 Culture] for each adjacent [Holy site]",
			"[+1 Culture] for each adjacent [Landmark]",
			"[-1 Culture] for each adjacent [Citadel]",
			"[-1 Culture] for each adjacent [Manufactory]",
			"[-1 Culture] for each adjacent [Mine]",
			"[-1 Culture] for each adjacent [Quarry]",
			"[-1 Culture] for each adjacent [Oil well]",
			"[-1 Culture] for each adjacent [Jungle]",
			"[-1 Culture] for each adjacent [Marsh]",
		],
	},
 
 [
	{
		"name": "Tradition",
		"era": "Ancient era",
		"uniques": ["[+3 Culture] [in capital]", "[-25]% Culture cost of natural border growth [in all cities]","Unlocks building the Hanging Gardens"],
		"policies": [
			{
				"name": "Aristocracy",
				"uniques": ["[+15]% Production when constructing [All] wonders [in all cities]", "[+1 Happiness] per [10] population [in all cities]"],
				"row": 1,
				"column": 2
			},
			{
				"name": "Oligarchy",
				"uniques": ["Units in cities cost no Maintenance", "[+50]% Strength for cities <with a garrison> <when attacking>"],
				"row": 1,
				"column": 4
			},
			{
				"name": "Theocracy",
				"uniques": ["[+25]% [Gold] from every [Temple]","[+3 Gold] from every [Holy site]"],
				"requires": ["Aristocracy"],
				"row": 2,
				"column": 2
			},
						{
				"name": "Legalism",
				"uniques":["Provides a [Aqueduct] in your first [4] cities for free"],
				"requires": ["Oligarchy"],
				"row": 2,
				"column": 4
			},
			{
				"name": "Landed Elite",
				"uniques": ["[+10]% growth [in capital]", "[+2 Food] [in capital]"],
				"requires": ["Legalism"],
				"row": 3,
				"column": 3
			},
			{
				"name": "Monarchy",
				"uniques": ["[+1 Gold, +1 Happiness] per [2] population [in capital]"],
				"requires": ["Legalism"],
				"row": 3,
				"column": 5
			},
			{
				"name": "Tradition Complete",
				"uniques": ["[+15]% growth [in all cities]","Provides the cheapest [Culture] building in your first [8] cities for free","May buy [Great Engineer] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"]
			}
		]
	},
	{
		"name": "Liberty",
		"era": "Classical era",
		"uniques": ["[+1 Culture] [in all cities]", "Unlocks building the Pyramids"],
		"policies": [
			{
				"name": "Republic",
				"uniques": ["[+1 Production] [in all cities]", "[+5]% Production when constructing [All] buildings [in all cities]"],
				"row": 1,
				"column": 1
			},
			{
				"name": "Citizenship",
				"uniques": ["[-25]% construction time for [All] improvements", "Free [Worker] appears"],
				"row": 1,
				"column": 4
			},
			{
				"name": "Collective Rule",
				"uniques": ["[+50]% Production when constructing [Worker] units [in capital]", "Free [Settler] appears"],
				"requires": ["Republic"],
				"row": 2,
				"column": 1
			},
			{
				"name": "Representation",
				"uniques": ["Each city founded increases culture cost of policies [33]% less than normal", "Empire enters golden age"],
				"requires": ["Citizenship"],
				"row": 2,
				"column": 3
			},
			{
				"name": "Meritocracy",
				"uniques": ["[+1 Happiness] [in all cities connected to capital]", "[-5]% Unhappiness from [Population] [in all non-occupied cities]"],
				"requires": ["Citizenship"],
				"row": 2,
				"column": 5
			},
			{
				"name": "Free Religion",
				"uniques": ["[-10]% Culture cost of adopting new Policies"],
				"requires": ["Citizenship","Representation"],
				"row": 3,
				"column": 3
			},
			{
				"name": "Liberty Complete",
				"uniques": ["Free Great Person"]
			}
		]
	},
	{
		"name": "Honor",
		"era": "Ancient era",
		"uniques": ["[+33]% Strength <vs [Barbarian] units>", "Earn [100]% of killed [Barbarian] unit's [Strength] as [Culture]",
			"Notified of new Barbarian encampments", "Unlocks building the Statue of Zeus"],
		"policies": [
			{
				"name": "Warrior Code",
				"uniques":["[+15]% Production when constructing [Melee] units [in all cities]", "Free [Great General] appears","[Great General] is earned [50]% faster"],
				"row": 1,
				"column": 2
			},
			{
				"name": "Discipline",
				"uniques":["[+15]% Strength <for [Melee] units> <when adjacent to a [Military] unit>"],
				"row": 1,
				"column": 4
			},
			{
				"name": "Military Tradition",
				"uniques":["[+50]% XP gained from combat <for [Military] units>"],
				"requires": ["Warrior Code"],
				"row": 2,
				"column": 2
			},
			{
				"name": "Military Caste",
				"uniques": ["[+1 Happiness, +2 Culture] [in all cities with a garrison]"],
				"requires": ["Discipline"],
				"row": 2,
				"column": 4
			},
			{
                		"name": "United Front",
				"requires": ["Military Tradition"],
                		"uniques": [
                    		"Militaristic City-States grant units [2] times as fast when you are at war with a common nation","[-100]% weight to this choice for AI decisions"
                			],
                			"row": 3,
                			"column": 2
            		},
			{
				"name": "Professional Army",
				"uniques": ["[-33]% Gold cost of upgrading <for [Military] units>","[+50]% Production when constructing [Barracks] buildings [in all cities]"
				,"[+50]% Production when constructing [Armory] buildings [in all cities]","[+50]% Production when constructing [Military Academy] buildings [in all cities]"
				],
				"requires": ["Military Caste"],
				"row": 3,
				"column": 4
			},
			{
				"name": "Honor Complete",
				"uniques": ["Earn [10]% of killed [Military] unit's [Cost] as [Gold]","May buy [Great General] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"]
			}
		]
	},
	{
		"name": "Piety",
		"era": "Ancient era",
		"uniques": ["Only available <before adopting [Rationalism]>","[+100]% Production when constructing [Shrine] buildings [in all cities]", "[+100]% Production when constructing [Temple] buildings [in all cities]", "Unlocks building the Great Mosque of Djenne"],
		"policies": [
			{
				"name": "Organized Religion",
				"uniques": ["[+1 Faith] from every [Shrine]","[+1 Faith] from every [Temple]"],
				"row": 1,
				"column": 2
			},
			{
				"name": "Mandate Of Heaven",
				"uniques": ["[Faith] cost of purchasing items in cities [-20]%"],
				"row": 1,
				"column": 5
			},
			{
				"name": "Sharia",
				"requires": ["Organized Religion"],
				"uniques": ["[-2 Science] [in all cities]","[Faith] cost of purchasing [Inquisitor] units [-15]%"],
				"row": 2,
				"column": 1
			},
			{
				"name": "Reformation",
				"uniques": ["[+33]% [Culture] [in all cities with a world wonder]", "Empire enters golden age"],
				"requires": ["Organized Religion"],
				"row": 2,
				"column": 3
			},
			{
                		"name": "Planned Economy",
				"requires": ["Reformation"],
                		"uniques": [
                    			"[-15]% [Science] from every [Shrine]","[-15]% [Science] from every [Temple]"
                			],
                		"row": 3,
                		"column": 2
            		},
			{
				"name": "Jihad",
				"requires": ["Reformation","Mandate Of Heaven"],
				"uniques": [
					"[-2 Happiness] [in all cities]","Free [Inquisitor] appears",
					"[+15]% Strength <for [All] units> <when fighting in [Desert] tiles>",
					"[+15]% Strength <for [All] units> <when fighting in [Hill] tiles>"
				],
				"row": 3,
				"column": 4
			},
			{
				"name": "Piety Complete",
				"uniques": ["Free [Great Prophet] appears", "[+3 Culture] from every [Holy site]"]
			}
		]
	},
	{
		"name": "Patronage",
		"era": "Classical era",
		"uniques": ["[-25]% City-State Influence degradation", "Unlocks building the Forbidden Palace"],
		"policies": [
			{
				"name": "Philantropy",
				"uniques":["Gifts of Gold to City-States generate [25]% more Influence"],
				"row": 1,
				"column": 2
			},
			{
				"name": "Consulates",
				"uniques":["Resting point for Influence with City-States is increased by [20]"],
				"row": 1,
				"column": 4
			},
			{
				"name": "Scholasticism",
				"uniques":["Allied City-States provide [Science] equal to [25]% of what they produce for themselves"],
				"requires": ["Philantropy"],
				"row": 2,
				"column": 2
			},
			{
				"name": "Cultural Diplomacy",
				"uniques": ["[+100]% resources gifted by City-States",
					"[+50]% Happiness from luxury resources gifted by City-States"],
				"requires": ["Scholasticism"],
				"row": 3,
				"column": 1
			},
			{
				"name": "Educated Elite",
				"requires": ["Scholasticism","Consulates"],
				"uniques": ["Allied City-States will occasionally gift Great People"],
				"row": 3,
				"column": 3
			},
			{
            			"name": "Trade Unions",
				"requires": ["Consulates"],
            			"uniques": [
                			"[+1 Gold] from every [Trading post]","[+2 Culture] from each Trade Route","[+1 Food] from every [Trading post]"
            				],
            			"row": 3,
            			"column": 5
        		},
			{
				"name": "Patronage Complete",
				"uniques": ["Influence of all other civilizations with all city-states degrades [33]% faster", 
					"Triggers the following global alert: [Our influence with City-States has started dropping faster!]"]
			} 
		]
	},
	{
		"name": "Commerce",
		"uniques": ["Only available <after adopting [Patronage]>","[+25]% [Gold] [in capital]", "Unlocks building Big Ben"],
		"era": "Medieval era",
		"policies": [
			{
				"name": "Wagon Trains",
				"uniques": ["[-50]% maintenance on road & railroads", "[+2 Gold] from each Trade Route"
				],
				"row": 1,
				"column": 1
			},
			{
				"name": "Capitalism",
				"uniques": ["[+1 Happiness] from every [Mint]","[+1 Happiness] from every [Bank]","[+1 Happiness] from every [Stock Exchange]"],
				"row": 1,
				"column": 3
			},
			{
				"name": "Mercenary Army",
				"uniques": ["May buy [Landsknecht] units with [Gold] for [5] times their normal Production cost"],
				"row": 1,
				"column": 5
			},
			{
				"name": "Entrapreneurship",
				"uniques": [ "[+100]% Gold from Great Merchant trade missions","[Great Merchant] is earned [25]% faster"],
				"requires": ["Capitalism"],
				"row": 2,
				"column": 1
			},
			{
				"name": "Mercantilism",
				"requires": ["Capitalism"],
				"uniques": ["[Gold] cost of purchasing items in cities [-25]%", "[+1 Science] from every [Mint]", "[+1 Science] from every [Market]",
					"[+1 Science] from every [Bank]", "[+1 Science] from every [Stock Exchange]"],
				"row": 2,
				"column": 3
			},
			
			{
				"name": "Protectionism",
				"uniques": ["[+2] Happiness from each type of luxury resource"],
				"requires": ["Mercenary Army"],
				"row": 2,
				"column": 5
			},
			{
				"name": "Commerce Complete",
				"uniques": ["[+1 Gold] from every [Customs house]",
					"May buy [Great Merchant] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
				]
			}
		]
	},
	{
		"name": "Exploration",
		"uniques": ["[+1] Movement <for [{Military} {Water}] units>",
			"[+1] Sight <for [{Military} {Water}] units>","Unlocks building the Louvre"],
		"era": "Medieval era",
		"policies": [
			{
				"name": "Maritime Infrastructure",
				"uniques": ["[+3 Production] [in all coastal cities]"],
				"row": 1,
				"column": 2
			},
						{
				"name": "Naval Tradition",
				"uniques": ["[+1 Happiness] from every [Lighthouse]","[+1 Happiness] from every [Harbor]","[+1 Happiness] from every [Seaport]"],
				"row": 1,
				"column": 4
			},
			{
				"name": "Merchant Navy",
				"uniques": ["[+1 Gold] from every [Lighthouse]","[+1 Gold] from every [Harbor]","[+1 Gold] from every [Seaport]","[+4 Production, +4 Culture] from every [East India Company]"],
				"requires": ["Maritime Infrastructure","Naval Tradition"],
				"row": 2,
				"column": 3
			},
			{
				"name": "Navigation School",
				"uniques": ["[+2 Science] [in all coastal cities]"],
				"requires": ["Naval Tradition"],
				"row": 2,
				"column": 5
			},
			{
				"name": "Fortune Wheel",
				"uniques": ["[+2 Production, +2 Faith] from each Trade Route","[+22]% [Culture] from every [Harbor]"],
				"row": 3,
				"column": 1
			},
			{
				"name": "Treasure Fleets",
				"uniques": ["[+4 Gold] from each Trade Route"],
				"requires": ["Navigation School"],
				"row": 3,
				"column": 3
			},
			{
				"name": "Exploration Complete",
				"uniques": ["[+3 Culture] [in all coastal cities]"]
			}
		]
	},
	{
		"name": "Aesthetics",
		"era": "Classical era",
		"uniques": ["[Great Artist] is earned [33]% faster","Unlocks building the Uffizi"],
		"policies": [
			{
				"name": "Cultural Centers",
				"uniques": ["[+100]% Production when constructing [Monument] buildings [in all cities]",
					"[+100]% Production when constructing [Amphitheater] buildings [in all cities]",
					"[+100]% Production when constructing [Opera House] buildings [in all cities]",
					"[+100]% Production when constructing [Museum] buildings [in all cities]",
					"[+100]% Production when constructing [Broadcast Tower] buildings [in all cities]"],
				"row": 1,
				"column": 2
			},
			{
				"name": "Fine Arts",
				"uniques": ["[50]% of excess happiness converted to [Culture]"],
				"row": 1,
				"column": 4
			},
			{
                		"name": "Populism",
				"requires": ["Cultural Centers"],
                		"uniques": ["[+25]% Great Person generation [in all cities]","[+100]% weight to this choice for AI decisions"],
                		"row": 2,
                		"column": 1
            		},
						{
				"name": "Flourishing of the Arts",
				"uniques": ["[+33]% [Culture] [in all cities with a world wonder]","Empire enters golden age"],
				"requires": ["Cultural Centers", "Fine Arts"],
				"row": 2,
				"column": 3
			},
						{
				"name": "Artistic Genius",
				"uniques": ["Free [Great Artist] appears"],
				"requires": ["Fine Arts"],
				"row": 2,
				"column": 5
			},
			{
				"name": "Cultural Exchange",
				"uniques": ["[+20]% [Culture] from every [Museum]","[+20]% [Culture] from every [Opera House]","[+20]% [Culture] from every [Broadcast Tower]"],
				"requires": ["Flourishing of the Arts"],
				"row": 3,
				"column": 3
			},
			{
				"name": "Aesthetics Complete",
				"uniques": ["[+4 Culture] from every [Landmark]","Free Social Policy","May buy [Great Artist] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"]
			}
		]
	},
	 {
		"name": "Rationalism",
		"era": "Renaissance era",
		"uniques": ["Only available <before adopting [Piety]>","[+10]% [Science] <while the empire is happy>", "Unlocks building the Porcelain Tower"],
		"policies": [
			{
				"name": "Secularism",
				"uniques": ["[+2 Science] from every specialist [in all cities]"],
				"row": 1,
				"column": 3
			},
				{
				"name": "Sovereignty",
				"uniques": ["[+1 Gold] from all [Science] buildings"],
				"row": 2,
				"column": 1
			},
			{
				"name": "Humanism",
				"uniques": ["[Great Scientist] is earned [25]% faster"],
				"requires": ["Secularism"],
				"row": 2,
				"column": 3
			},
			{
				"name": "Free Thought",
				"uniques": ["[+1 Science] from every [Trading post]", "[+17]% [Science] from every [University]"],
				"row": 2,
				"column": 5
			},
			{
				"name": "Scientific Revolution",
				"uniques": ["Science gained from research agreements [+50]%"],
				"requires": ["Sovereignty","Humanism"],
				"row": 3,
				"column": 1
			},
			{
				"name": "Christ",
				"uniques": ["[+2 Production, +2 Food, +2 Gold, +2 Faith, +2 Culture, +2 Science, +2 Happiness] per [5] population [in all cities]",
					"[Faith] cost of purchasing [Missionary] units [-20]%","[2] free [Missionary] units appear"],
				"requires": ["Humanism"],
				"row": 3,
				"column": 3
			},
			{
				"name": "Weather Engineering",
				"requires": ["Humanism","Free Thought"],
				"uniques": [
					"[+2 Gold, +2 Science] [in all cities]",
					"[+10]% growth [in all cities] <during a Golden Age>"
				],
				"row": 3,
				"column": 5
			},
			{
				"name": "Rationalism Complete",
				"uniques": ["[1] Free Technologies","[-10]% unhappiness from the number of cities",
					"May buy [Great Scientist] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
				]
			}
		]
	},
	{
		"name": "Freedom",
		"era": "Modern era",
		"uniques": ["[+25]% Great Person generation [in all cities]", "Unlocks building the Statue of Liberty", "Only available <before adopting [Autocracy]>", 
			"Only available <before adopting [Order]>","Only available <after adopting [Rationalism]>"],
		"policies": [
			{
				"name": "Civil Society",
				"uniques": ["[-50]% Food consumption by specialists [in all cities]"],
				"row": 1,
				"column": 1
			},
			{
				"name": "Promised Land",
				"uniques": [
					"[+15]% Strength <for [All] units> <when fighting in [Plains] tiles>",
					"[+15]% Strength <for [All] units> <when fighting in [Jungle] tiles>",
					"[+15]% Strength <for [All] units> <when fighting in [Hill] tiles>",
					"[+15]% Strength <for [All] units> <when fighting in [Forest] tiles>",
					"[+15]% Strength <for [All] units> <when fighting in [Grassland] tiles>"
				],
				"row": 1,
				"column": 3
			},
			
						{
				"name": "Universal Healthcare",
				"uniques": ["[+1 Happiness] from every [National Wonder]"],
				"row": 1,
				"column": 5
			},
			{
				"name": "Volunteer Army",
				"uniques": ["[6] units cost no maintenance", "[6] free [Foreign Legion] units appear"],
				"requires": ["Civil Society","Promised Land","Universal Healthcare"],
				"row": 2,
				"column": 2
			},
			{
				"name": "Urbanization",
				"uniques": ["[+1 Happiness] from every [Water Mill]","[+1 Happiness] from every [Hospital]","[+1 Happiness] from every [Medical Lab]"],
				"requires": ["Universal Healthcare","Promised Land"],
				"row": 2,
				"column": 4
			},
			{
                		"name": "Democracy",
                		"uniques": [
                    			"[-50]% Unhappiness from [Specialists] [in all cities]"
                				],
                		"requires": ["Volunteer Army","Urbanization"],
                		"row": 3,
                		"column": 3
            		},
			{
				"name": "Freedom Complete",
				"uniques": ["[+100]% Yield from every [Great Improvement]", "[+50]% Golden Age length","[-20]% unhappiness from the number of cities"]
			}
		]
	},
	{
		"name": "Autocracy",
		"era": "Industrial era",
		"uniques": ["[Gold] cost of purchasing [All] units [-33]%", "Only available <after adopting [Piety]>", "[+1]% [Production] from every follower, up to [15]%",
				"Only available <before adopting [Order]>", "Only available <before adopting [Freedom]>", "Unlocks building the Prora"],
		"policies": [
			{
				"name": "Nazism",
				"uniques": ["[+100]% Production when constructing [Constabulary] buildings [in all cities]",
					"[+100]% Production when constructing [Police Station] buildings [in all cities]",
					"[-3 Food,-3 Science] [in annexed cities]","[-3 Food,-3 Science] [in puppeted cities]"],
				"row": 1,
				"column": 1
			},
			{
				"name": "Elite Forces",
				"uniques": ["[+25]% Strength <for [Wounded] units>"],
				"row": 1,
				"column": 3
			},
			{
				"name": "Fortified Borders",
				"uniques": ["[+1 Happiness] from every [Castle]","[+1 Happiness] from every [Arsenal]","[+1 Happiness] from every [Military Base]"],
				"row": 1,
				"column": 5
			},
			{
				"name": "Militarism",
				"uniques": ["[+2 Happiness] from every [Barracks]","[+2 Happiness] from every [Armory]","[+2 Happiness] from every [Military Academy]"]
				"requires": ["Nazism","Elite Forces"],
				"row": 2,
				"column": 2
			},
			{
				"name": "Police State",
				"uniques": ["[+3 Happiness] from every [Courthouse]", "[+100]% Production when constructing [Courthouse] buildings [in all cities]"],
				"requires": ["Elite Forces","Fortified Borders"],
				"row": 2,
				"column": 4
			},
			{
				"name": "Scorched Earth",
				"requires": ["Nazism","Militarism"],
				"uniques": [
					"[+15]% Strength <vs cities>",
					"Cities are razed [2] times as fast",
					"No movement cost to pillage <for [Melee] units>",
					"[+2] Movement <for [Great General] units>"
				],
				"row": 3,
				"column": 1
			},
			{
                		"name": "Fascism",
                		"uniques": [
                   		"Quantity of strategic resources produced by the empire +[100]%",
                    		"[+2] Movement <for [Great General] units>"
                		],
                		"requires": ["Militarism","Elite Forces","Police State"],
                		"row": 3,
                		"column": 3
            		},
			{
				"name": "Total War",
				"uniques": ["[+25]% Production when constructing [Military] units [in all cities]", "New [Military] units start with [15] Experience [in all cities]"],
				"requires": ["Fortified Borders","Police State"],
				"row": 3,
				"column": 5
			},
			
			{
				"name": "Autocracy Complete",
				"uniques": ["[+25]% Strength <when attacking> <for [Military] units> <for [50] turns>","[+20]% unhappiness from the number of cities"]
			}
		]
	},
	{
    "name": "Order",
    "era": "Industrial era",
	"uniques": ["[+2 Happiness] from every [Monument]", "Unlocks building the Kremlin", "Only available <before adopting [Autocracy]>", "Only available <before adopting [Freedom]>"],
    "policies": [
        {
            "name": "Young Pioneers",
			"uniques": ["[+1 Happiness] from every [Workshop]","[+1 Happiness] from every [Factory]","[+1 Happiness] from every [Nuclear Plant]","[+1 Happiness] from every [Hydro Plant]","[+1 Happiness] from every [Solar Plant]"],
            "row": 1,
            "column": 2
        },
		{
			"name": "Patriotic War",
			"uniques": ["[+15]% Strength <for [All] units> <when fighting in [Friendly Land] tiles>"],
			"row": 1,
			"column": 4
		},
				{
			"name": "Workers' Faculties",
			"uniques": ["[+25]% [Science] from every [Factory]", "[+100]% Production when constructing [Factory] buildings [in all cities]"],
			"requires": ["Young Pioneers"],
			"row": 2,
			"column": 1
		},
        {
            "name": "Academy of Sciences",
            "requires": ["Patriotic War"],
			"uniques": ["[+1 Happiness] from every [Observatory]","[+1 Happiness] from every [Public School]","[+1 Happiness] from every [Research Lab]"],
            "row": 2,
            "column": 5
        },
	{
                "name": "Socialism",
                "requires": ["Patriotic War", "Young Pioneers"],
                "uniques": [
                    "[-15]% maintenance cost for buildings [in all cities]"
                ],
                "row": 2,
                "column": 3
            },
        {
            "name": "Five-Year Plan",
            "requires": ["Workers' Faculties"],
			"uniques": ["[+2 Production] [in all cities]", "[+1 Production] from every [Mine]", "[+1 Production] from every [Quarry]"],
            "row": 3,
            "column": 4
        },
            {
                "name": "Communism",
                "requires": ["Socialism"],
                "uniques": [
                    "[+2 Production] [in all cities]",
                    "[+1 Production] from every [Mine]",
                    "[+1 Production] from every [Quarry]"
                ],
                "row": 3,
                "column": 2
            },
        {
            "name": "Order Complete",
			"uniques": ["[+1 Food, +1 Production, +1 Science, +1 Gold, +1 Culture] [in all cities]","[+10]% unhappiness from the number of cities"]
        }
    ]
}
		]
