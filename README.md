# IntelliJ configuration

Follow these steps to configure IntelliJ according to the development standards.

## Import settings

	1. File > Import Settings...
	2. Select 'PersonalSettings.jar'

## IntelliJ Plugins

These plugins should ask for an "update" automatically.

- BrowseWordAtCaret
- Lombok Plugin
- SonarLint
- String Manipulation
- Save Actions

If an automatic update is not prompt, try updating the plugins manually and restarting 
the IDE.

## Update Codestyle
Codestyle gives a set of configurations to keep a common style in the code.

	1. Go to Preferences...
	2. Editor > Code Style
	3. In the Scheme field select PersonalCodeStyle

## Update Inspections
Code inspections rise warning/errors according to some good practices rules.

	1. Go to Preferences...
	2. Editor > Inspections
	3. In the Profile field select PersonalInspections
	
## Configure Save Actions Plugin
Save Actions plugins apply a set of rules when a file is saved. To configure it apply the rules shown in **SaveActionsConf.png**.

***

# Estandarice project

Once IntelliJ is configured with the common rules, go to the root folder of the project 
you are working on and perform the following actions:

	1. Right click and select "Reformat Code".
	2. Right click and select "Analize > Code Cleanup...".
	3. In the pop-up dialog make sure you select "PersonalInspections" in the inspection 
	profile.
