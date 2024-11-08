# Calipole

BuildingIcons/Magnificient Temples
  rotate: false
  xy: 836, 600
  size: 200, 200
  orig: 200, 200
  offset: 0, 0
  index: -1
TileSets/FantasyHex/Units/Siege Elephant
  rotate: false
  xy: 836, 1108
  size: 32, 28
  orig: 32, 28
  offset: 0, 0
  index: -1
ZZx one building gor all mods if so?
{
		"name": "Tsikhe",
		"replaces": "Walls",
		"uniqueTo": "Georgia",
		"cost": 260,
		"faith": 4,
		"cityStrength": 24,
		"cityHealth": 200,
		"uniques": [
			"[+4 Faith] [in this city] <during a Golden Age>",
			"Cannot be purchased"
		],
		"requiredTech": "Masonry"
	},
{
		"name": "Marae",
		"replaces": "Amphitheater",
		"uniqueTo": "The Maori",
        "hurryCostModifier": 25,
		"culture": 3,
		"requiredBuilding": "Monument",
		"maintenance": 0,
		"hurryCostModifier": 25,
		"specialistSlots": {"Artist": 1},
		"uniques": [
			"[+1 Culture, +1 Faith] from [Forest] tiles [in this city]",
			"[+1 Culture, +1 Faith] from [Jungle] tiles [in this city]",
			"[+1 Culture, +1 Faith] from [Marsh] tiles [in this city]",
			"[+1 Culture, +1 Faith] from [Oasis] tiles [in this city]",
			"[+1 Culture, +1 Faith] from [Atoll] tiles [in this city]",
			"[+1 Culture, +1 Faith] from [Flood plains] tiles [in this city]",
			"[+1 Culture, +1 Faith] from [Natural Wonder] tiles without [Mountain] [in this city]",
		"requiredTech": "Drama and Poetry"
		],
	},
	{
		"name": "Suguba",
		"replaces": "Market",
		"uniqueTo": "Mali",
		"cost": 57,
		"gold": 2,
		"greatPersonPoints": {
			"Great Merchant": 1
		},
		"specialistSlots": {"Merchant": 1},
		"hurryCostModifier": 25,
		"percentStatBonus": {"gold": 25},
		"maintenance": 1,
		"requiredTech": "Currency",
		"uniques": [
			"Unsellable",
			"Never destroyed when the city is captured",
"[Gold] cost of purchasing [All] buildings [-20]%",
"[Faith] cost of purchasing [All] units [-20]%"
		],
	},
  

BuildingIcons/Mekewap
  rotate: false
  xy: 1300, 1188
  size: 92, 100
  orig: 92, 100
  offset: 0, 0
  index: -1
TileSets/HexaRealm/Tiles/Mekewap
  rotate: false
  xy: 566, 268
  size: 32, 28
  orig: 32, 28
  offset: 0, 0
  index: -1
BuildingIcons/Kurgan
  rotate: false
  xy: 112, 1620
  size: 100, 100
  orig: 100, 100
  offset: 0, 0
  index: -1
TileSets/HexaRealm/Tiles/Kurgan
  rotate: false
  xy: 508, 198
  size: 32, 40
  orig: 32, 40
  offset: 0, 0
  index: -1
TileSets/HexaRealm/Tiles/Hacienda
  rotate: false
  xy: 760, 584
  size: 64, 56
  orig: 64, 56
  offset: 0, 0
  index: -1
TileSets/HexaRealm/Tiles/Chemamull
  rotate: false
  xy: 1472, 1232
  size: 32, 41
  orig: 32, 41
  offset: 0, 0
  index: -1
BuildingIcons/Chemamull
  rotate: false
  xy: 880, 957
  size: 100, 100
  orig: 100, 100
  offset: 0, 0
  index: -1
BuildingIcons/Suguba
  rotate: false
  xy: 528, 85
  size: 100, 100
  orig: 100, 100
  offset: 0, 0
  index: -1
BuildingIcons/Hacienda
  rotate: false
  xy: 1933, 441
  size: 100, 100
  orig: 100, 100
  offset: 0, 0
  index: -1
	
BuildingIcons/Hacienda
  rotate: false
  xy: 528, 85
  size: 100, 100
  orig: 100, 100
  offset: 0, 0
  index: -1
{
		"name": "Settler",
		"unitType": "Civilian",
		"requiredTech": "The Wheel",
		"movement": 2,
		"cost": 106,
		"uniques": ["Founds a new city <by consuming this unit>", "Excess Food converted to Production when under construction",
			"Requires at least [2] population"],
		"hurryCostModifier": 20
	},
