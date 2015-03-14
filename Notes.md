#Notes
A scratchpad for general thoughts & brainstorming on this module.

### There is no "perform script by name" step in filemaker.
 * Some plugins support this (e.g., Scriptmaster) but plugins are icky.
 * Can get around this in a hosted environment by calculating an FMP:// URL and executing a script; but that does not allow for retrieving the script result. Would need a standardized way (maybe Let-notation dictionary in a global variable?) to communicate between scripts.