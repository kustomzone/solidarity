# API - Draft 1.0

In this draft document I briefly describe a set of API calls required by the front-end; these draft 
specifications are a work-in-progress, and thefore should not be used to create a finished API.

The terminolgy used here should be taken loosely.

Login and Authentication will be achieved via existing solid .js libraries which been already created.


# Calls

<b>Solidarity.Rooms.getList()</b>

Returns: list of chat rooms

Purpose: 

---

<b>Solidarity.Rooms.getPeople()</b>

Returns: list of people in the room

Purpose: 

---

<b>Solidarity.Room.create()</b>

Returns:

Purpose: create room, and the logged in user is the owner.

---

<b>Solidarity.Room.remove()</b>

Returns:

Purpose: remove room from your list of rooms.

---

<b>Solidarity.Room.delete()</b>

Returns:

Purpose: delete room, if you are the owner.

---

<b>Solidarity.Room.invite()</b>

Returns:

Purpose: send an invitation to a person to join a room.

---

<b>Solidarity.Room.addPerson()</b>

Returns:

Purpose: adds a person to a room.

---

<b>Solidarity.Room.removePerson()</b>

Returns: 

Purpose: removes a person from a room, if you are the owner of the room.

---

<b>Solidarity.Profile.get()</b>

Returns: solid profile for a person;

Purpose:

---

<b>Solidarity.Room.SendChat()</b>

Returns: 

Purpose: send a chat message to a room
