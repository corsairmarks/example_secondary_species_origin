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