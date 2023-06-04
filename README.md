# NWAF-Bunker
A fully functioning Bunker at NWAF chern.

This repostary consist of the following snippet files to add to your server,

	Custom Bunker.json
	Custom BunkerLoot.json
	Custom cfgareaeffect.json
	Custom mapgrouppos.xml
	Custom mapgroupproto.xml
	Custom undergroundtriggers.json

This a fully funcating Bunker with world tier loot that spawns within three sections of the bunker and two structures on the outside. There is also a area where you can add your own custom event spawn loot which i will also add if you wish to use as well.	

Here is the snippet for the PunchedCard that you need to add into your spawnabletypes and types folders

cfgspawnabletypes file:

</type>
	<type name="PunchedCard">
</type>

types file:

<type name="PunchedCard">
        <nominal>5</nominal>
        <lifetime>14400</lifetime>
        <restock>0</restock>
        <min>2</min>
        <quantmin>-1</quantmin>
        <quantmax>-1</quantmax>
        <cost>100</cost>
        <flags count_in_cargo="1" count_in_hoarder="1" count_in_map="1" count_in_player="1" crafted="0" deloot="0"/>
        <category name="tools"/>
		<tag name="shelves"/>
        <usage name="Military"/>
    </type>

Warning always make sure to use validators before uploading these files to you're own server. Use these at you're own risk..
