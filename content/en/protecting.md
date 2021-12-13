---
title: Protecting your Stuff
description: ''
position: 2
category: 'Getting Started'
---

Minecraft.mom uses LWC (Lightweight Chest protection) allowing players to create protections for chests, doors, etc.

There are five levels of protection that players can choose:

<table>
<tr>
	<td> Public </td>
	<td>
		Anyone can access the protection, but no one can protect it for themselves. Mainly useful for community chests that store items for anyone to use.
	</td>
</tr>
<tr>
	<td> Private </td>
	<td>
		By default, only you can access the protection. You can also add other players  to the protection so that they, too can access it. So your chest and doors can only let in your close friends and those you choose to add to it.
	</td>
</tr>
<tr>
	<td> Password </td>
	<td>
		The protection has a set password and you need to enter it each time you login. This can of course be shared with other players -- they will be able to access the protection until they log out (after that they will need to re enter it)
	</td>
</tr>
<tr>
	<td> Donation </td>
	<td>
		Other players can put things into this protection, but won't be able to take anything out. This can be good for many purposes such as collecting items from people, or crowd sourcing materials for a build.
	</td>
</tr>
<tr>
	<td> Display </td>
	<td>
		The contents of the protection may be viewed by others, but they will not be able to put anything in or take anything out. Useful for basic shops, showing off items, reading books in lecterns, and so on.
</tr>
</table>

## Protecting a Chest
Look at the chest you want to protect, then use one of the following chat commands:
- `/cprivate` - This is the most common option. Create a private chest.
- `/cpublic` - Create a public chest that others cannot claim.
- `/cpassword <password>` - Create a password-protected chest with the given password.
- `/cdonation` - Create a donation chest.
- `/cdisplay` - Create a display chest.

<img src="/protection/1.jpg" width="640">

## Allowing Players in Private Chest
Each private chest can have various other players added to access the protecion using the `/cmodify` command. The owner of a chest cannot be removed from the protection.

If you wanted to add the player `notch` to have access to a private chest, you would run the following command while looking at the chest:

- `/cmodify notch`

To remove access from a player, add a dash before the player's name 

- `/cmodify -notch`

## Removing Protection from a Chest
If you want to change the protection type of a chest you will first need to remove the current protection. While looking at the protected chest, run the following chat command:
- `/cremove`
 
## Tips
- While the above commands were listed for chests, most should work on doors as well.