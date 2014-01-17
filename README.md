SQLite-Plugin
=============

Work on this plugin has been stopped for now!  
Maybe we will finish it some day.

Purpose
---------
This is an update of the SQLite Plugin by "nareshr" ([https://github.com/nareshr/SQLite-Plugin](https://github.com/nareshr/SQLite-Plugin)) to be compatible with Phonegap 3.3.0 / Cordova 3.3.1.

Usage
-------
	sqlitePlugin.DEBUG = true;
	var db = sqlitePlugin.openDatabase(
		{ "name" : "yourDbName" }
		,function()
		{
		    console.log('DB opened successfully');
		}
		,function(event)
		{
		    console.log("db open failed");
		    console.log(JSON.stringify(e));
		}
	);