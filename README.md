# Overview

A sample origin with a secondary species.  Demonstrates my "reuse the default initialization" technique.

You may freely reuse and modify this code for use in your own mods.

# Logging

The code in this example will log things to the [game.log](https://stellaris.paradoxwikis.com/Modding_tutorial#game.log) file to show you that its code is being called.  The default logging results in 5 log lines similar to these when starting a new game:

```
[14:39:17][effect_impl.cpp:19610]: [2200.1.1] Log command triggered from effect in file: events/my_mod_name_events.txt line: 99. my_mod_name.3 for Uliahtake Star Imperium Test
[14:39:17][effect_impl.cpp:19610]: [2200.1.1] Log command triggered from effect in file: events/my_mod_name_events.txt line: 36. my_mod_name.1 for Uliahtake Star Imperium Test
[14:39:17][effect_impl.cpp:19610]: [2200.1.1] Log command triggered from effect in file: events/my_mod_name_events.txt line: 36. my_mod_name.1 for Uliahtake Star Imperium Test
[14:39:17][effect_impl.cpp:19610]: [2200.1.1] Log command triggered from effect in file: events/my_mod_name_events.txt line: 64. my_mod_name.2 for Uliahtake Star Imperium Test
[14:39:17][effect_impl.cpp:19610]: [2200.1.1] Log command triggered from effect in file: scripted effect generate_origin_my_mod_name_example_start_pops at file: events/my_mod_name_events.txt line: 82 line: 1. generate_origin_my_mod_name_example_start_pops on Vuubate for Uliahtake Star Imperium Test
[14:39:18][effect_impl.cpp:19610]: [2200.1.1] Log command triggered from effect in file: events/my_mod_name_events.txt line: 14. my_mod_name.13
```

# Troubleshooting

Always check your Stellaris [error.log](https://stellaris.paradoxwikis.com/Modding_tutorial#error.log) file - it can alert you to many script issues, especially if your syntax or scoping are incorrect.

There is a community-maintained tool called [CWTools](https://github.com/cwtools/cwtools) (Clausewitz Tools - named for the PDS game engine Clausewitz) that can help validated your Stellaris files.  The easiest way to use it is to install Microsoft [Visual Studio Code](https://code.visualstudio.com/) (free) and install the [CWTools](https://marketplace.visualstudio.com/items?itemName=tboby.cwtools-vscode) extension directly through Visual Studio Code.  It includes the validation rules for the Stellaris flavor of CW script - installing the extension and pointing its settings to your Stellaris folder is the minimal amount of setup needed.  The rules are a collorative effort between PDS and the community - if you find any places where the rules are incorrect based on the game's behavior, you are encouraged to submit pull requests: https://github.com/cwtools/cwtools-stellaris-config.