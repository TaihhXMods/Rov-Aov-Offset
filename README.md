# Rov-Aov Offset
This is Offset for Arena Of Valor // Rov-Aov
# For Modding Creator
--0x0110F01 // Hack Map

--0xDE01249 // Unlimited Recovery(Skill)

--0x1F21D07 // No Skill Cooldown (Allian)

#Syntax Use Case
#Memory Offset Patch
OBFUSCATE{} else if {
MemoryPatch(/*Offset*/)'}
#LibPatch(Game)
(libPatch)(/*Libname*/orlib32.so)(/*HexOrOffset*/)(ClearResult)
#LibPatch (Original)
OBFUSCATE{} else if {LibPatch=>(Offset)=>(Hex) else if else}

