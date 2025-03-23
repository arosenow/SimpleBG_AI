# SimpleBG_AI
Simple Baldurs Gate AI 1.03

I tend to play baldur's gate fairly hands on, directly controlling wizards and trying to constrain warriors to attacking those nearby. 

# Features of this AI:

Toggle being passive with V key, handy if you only want them to use their modal skills. 

Outside combat, always use skills, during combat if you're an archer, alternate skill use and attack

Your party will act as a team, if one is in combat, others if skilled, will run to help, this means your archers will actually advance and attack enemies kiting you

Don't do anything to break stealth


#History
1.01 Fixed that the combat skill timer could break as it wasn't 3 seconds every 12, but 2 timers on different frequencies

1.02 Made the necessary adjustments for Icewind Dale 2. Sadly there's no way for AI to identify switches in the environment as opposed to enemies

1.03 Removed weapon swapping, added a LOS check before you attack to prevent changing targets to an ally due to engine bug. Added a check whether you're neutral or allied because the engine occasionally misflagsnpcs as enemies

