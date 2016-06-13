# early-morning-cappucino

Introduction :

this is academic project aims to develop middleware module for all the TV standards
Initial plan is to support DVB as welll as ATSC
if all goes well then we can add support for the ARIB, DMB, ...


Folder Architecture:

app folder contains sample application to use/test this middleware functions
mw folder contains the actual middleware code

There are three main components in middleware code: 

	1. Tables 
	2. Driver Interface (HAL)
	3. Application Interface (APIs)


Tables sub-module takes care of collecting the required tables/sections from the DVB/ATSC standards.

HAL layer will help to port this middleware into different hardware components

APIs will help the application to use the specific functionalities 





