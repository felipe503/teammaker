# Register admin
## admin has:
	name, email, password
## admin can:
	add admin, update admin, create group, erase group, remove users
# Group
## group has :
	name, admin, players
## group can:
	rename group, add players, remove players, display players
# Players
## player has:
	name, email, group, skills, team
## player can:
	read group
# User
## user has:
	name, email, password
## user can:
	qualify players, change name, change password
