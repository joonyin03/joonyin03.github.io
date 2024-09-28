
@import url('https://fonts.googleapis.com/css2?family=Comfortaa&display=swap%27');  /*font*/

:root {
  --FVUI: "Loading";
  --font: "Comfortaa" ;
}

:root{ /* Colors for users customization */
	--color1: 30, 40,  50;   /* Additional BG */
	--color2: 9,  18,  24;   /* Background */
	--color3: 35, 120, 200;  /* Blue */
	--color4: 63, 43,  150;  /* Gradient Color*/
	
	--text1: 174, 174, 174;  /*accent*/
	--text2: 107, 107, 107;  /*no accent*/
}
:root.theme-light { /* Colors for users customization */
	--color1: 211, 204, 227;  /* Additional BG */
	--color2: 219, 219, 219;  /* Background */
	--color3: 96,  205, 255;  /* Blue */
	--color4: 63,  43,  150;  /* Gradient Color*/
}


:root {
    /*main*/
  --color01: rgb(var(--color1));
  --color02: rgb(var(--color2));
  --color03: rgb(var(--color3));
  --color04: rgb(var(--color4));
    /*opacity*/
  --ColorOpacity  : 1;  /* opacity multiplier (0.1-...) */
  --DisableOpacity: 0;  /* Default=0 (0 or 1) */
	
  --opacity01: rgba(var(--color1), calc(var(--ColorOpacity)*0.9*(1 - var(--DisableOpacity)) + var(--DisableOpacity)));
  --opacity02: rgba(var(--color2), calc(var(--ColorOpacity)*0.9*(1 - var(--DisableOpacity)) + var(--DisableOpacity)));

  --opacity020a: rgba(var(--color2), calc(var(--ColorOpacity)*0.8*(1 - var(--DisableOpacity)) + var(--DisableOpacity)));

  --opacity01a: rgba(var(--color1), calc(var(--ColorOpacity)*0.6*(1 - var(--DisableOpacity)) + var(--DisableOpacity)));
  --opacity02a: rgba(var(--color2), calc(var(--ColorOpacity)*0.6*(1 - var(--DisableOpacity)) + var(--DisableOpacity)));

  --opacity01b: rgba(var(--color1), calc(var(--ColorOpacity)*0.4*(1 - var(--DisableOpacity)) + var(--DisableOpacity)));
  --opacity02b: rgb(var(--color2),calc(var(--ColorOpacity)*0.4*(1 - var(--DisableOpacity)) + var(--DisableOpacity)));

  --opacity01c: rgba(var(--color1), calc(var(--ColorOpacity)*0.2*(1 - var(--DisableOpacity)) + var(--DisableOpacity)));
  --opacity02c: rgba(var(--color1), calc(var(--ColorOpacity)*0.2*(1 - var(--DisableOpacity)) + var(--DisableOpacity)));

  --opacity03 : rgba(var(--color3), calc(var(--ColorOpacity)*0.5*(1 - var(--DisableOpacity)) + var(--DisableOpacity)));
  --opacity03a: rgba(var(--color3), calc(var(--ColorOpacity)*0.2*(1 - var(--DisableOpacity)) + var(--DisableOpacity)));
      /*text*/
  --text01: rgb(var(--text1));
  --text02: rgb(var(--text2));
}

:root {
  --full01: var(--full01_lite_MUI, rgba(var(--color1), calc(var(--ColorOpacity)*0.9*(1 - var(--DisableOpacity)) + var(--DisableOpacity))));
  --full02: var(--full02_lite_MUI, rgba(var(--color2), calc(var(--ColorOpacity)*0.9*(1 - var(--DisableOpacity)) + var(--DisableOpacity))));

  --full020a: var(--full020a_lite_MUI, rgba(var(--color2), calc(var(--ColorOpacity)*0.8*(1 - var(--DisableOpacity)) + var(--DisableOpacity))));

  --full01a: var(--full01a_lite_MUI, rgba(var(--color1), calc(var(--ColorOpacity)*0.6*(1 - var(--DisableOpacity)) + var(--DisableOpacity))));
  --full02a: var(--full02a_lite_MUI, rgba(var(--color2), calc(var(--ColorOpacity)*0.6*(1 - var(--DisableOpacity)) + var(--DisableOpacity))));

  --full01b: var(--full01b_lite_MUI, rgba(var(--color1), calc(var(--ColorOpacity)*0.4*(1 - var(--DisableOpacity)) + var(--DisableOpacity))));
  --full02b: var(--full02b_lite_MUI, rgba(var(--color2), calc(var(--ColorOpacity)*0.4*(1 - var(--DisableOpacity)) + var(--DisableOpacity))));

  --full01c: var(--full01c_lite_MUI, rgba(var(--color1), calc(var(--ColorOpacity)*0.2*(1 - var(--DisableOpacity)) + var(--DisableOpacity))))
  --full02c: var(--full02c_lite_MUI, rgba(var(--color1), calc(var(--ColorOpacity)*0.2*(1 - var(--DisableOpacity)) + var(--DisableOpacity))));

  --full03 : var(--full03_lite_MUI, rgba(var(--color3), calc(var(--ColorOpacity)*0.8*(1 - var(--DisableOpacity)) + var(--DisableOpacity))));
  --full03a: var(--full03a_lite_MUI, rgba(var(--color3), calc(var(--ColorOpacity)*0.4*(1 - var(--DisableOpacity)) + var(--DisableOpacity))));
}

@keyframes loaderr{
  to{
    --version      : "Make sure you used at least one of the subtopics OR did not break the syntax. If this doesn't help, reinstall the theme.";
    --FVUI         : "Error. ";
    pointer-events : none;
    backdrop-filter: none;
    background     : var(--opacity02b);
  }
}

