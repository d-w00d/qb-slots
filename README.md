# qb-slots
qb-slots for the casino updated to the latest version of QBCore

DEPENDECIES: https://github.com/BerkieBb/qb-target




-------- HOW TO INSTALL -----------

Drag And Drop The qb-slots Folder *NOT ZIP* Into Your Server Resource Folder.
Add ensure qb-slots To Your Sever.cfg 
add this to qb-target/init.lua under targetmodels

["qb-slots"] = {
		models = {
			`ch_prop_casino_slot_01a`,
			`ch_prop_casino_slot_02a`,
			`ch_prop_casino_slot_03a`,
			`ch_prop_casino_slot_04a`,
			`ch_prop_casino_slot_04b`,
			`ch_prop_casino_slot_05a`,
			`ch_prop_casino_slot_06a`,
			`ch_prop_casino_slot_07a`,
			`ch_prop_casino_slot_08a`,
			`vw_prop_casino_slot_01a`,
			`vw_prop_casino_slot_02a`,
			`vw_prop_casino_slot_03a`,
			`vw_prop_casino_slot_04a`,
			`vw_prop_casino_slot_05a`,
			`vw_prop_casino_slot_06a`,
			`vw_prop_casino_slot_07a`,
			`vw_prop_casino_slot_08a`,
		},
		options = {
			{
				type = "client",
				event = "qb-slots:enterBets",
				icon = "fa-solid fa-slot-machine",
				label = "Play Slot Machine",
			},
		},
		distance = 2.5,
	},

Enjoy :)

If You Have Any Problems Message Me On Discord @JustifY#9606
