public:: true

- [[Projet A-2022]]
-
- __MENU__
	- ((6331b4d4-2e5d-41f7-8d6f-7fb99d8991d1))
	- ((63279ac0-02db-4d56-a253-cd4163216a23))
	- ((6328dde4-426a-47b1-bdfa-07225f4e1298))
	- ((6328f60e-a2d7-47d6-96c1-da7ab963e387))
-
-
- GENERAL TECHNICAL INFOS
  background-color:: #793e3e
  id:: 6331b4d4-2e5d-41f7-8d6f-7fb99d8991d1
	- __IC 555__
	- ![2560px-555_Pinout.svg.png](../assets/2560px-555_Pinout.svg_1661386060127_0.png)
	- __Circuits how-to videos__
	- LED fader with 555: https://www.youtube.com/watch?v=XajEBM7iC4A&ab_channel=learnelectronics
	- Adjustable strobe with 555: https://www.youtube.com/watch?v=H1jpMqPHyjA&ab_channel=learnelectronics
	- Light/Dark detector: https://www.youtube.com/watch?v=3G9f7u60D4w&ab_channel=learnelectronics
	-
	- Connecter batteries en séries pour __doubler le voltage!__
	  background-color:: #533e7d
		- (en parallèle pour doubler l'ampérage)
		- ![Capture d’écran, le 2022-09-19 à 19.00.20.png](../assets/Capture_d’écran,_le_2022-09-19_à_19.00.20_1663628438385_0.png)
-
-
- TESTED AND WORKING CIRCUITS
  background-color:: #497d46
  id:: 63279ac0-02db-4d56-a253-cd4163216a23
	- 2022/08/28
	- Hysteretic oscillator + fade (555)
	- ![Hysteretic-Fade555.jpg](../assets/Hysteretic-Fade555_1661704689677_0.jpg)
	- Dark detector (avec 2N3904) https://www.youtube.com/watch?v=3G9f7u60D4w&ab_channel=learnelectronics
	- ![DarkDetector-2N3904.jpg](../assets/DarkDetector-2N3904_1661704721842_0.jpg)
	- Try a mix of those 2 circuits (do not forget to unplug when making changes in the circuit)
	-
	- TO DO
		- Control blink speed (potentiometer) automatically and random
		-
	- Simple blinking LED circuit https://www.instructables.com/Simple-Blinking-LED-Circuit/
		- ![Capture d’écran, le 2022-08-28 à 13.04.30.png](../assets/Capture_d’écran,_le_2022-08-28_à_13.04.30_1661706615467_0.png)
		- ![BlinkingLED_WithLDR.jpg](../assets/BlinkingLED_WithLDR_1663622597230_0.jpg)
		-
	- ![Capture d’écran, le 2022-08-30 à 17.15.36.png](../assets/Capture_d’écran,_le_2022-08-30_à_17.15.36_1661894147266_0.png){:height 406, :width 746}
	- Pour modifier la vitesse = changer R1 et/ou C2
	- Pour baisser le volume = changer C4 (1uF ou 0.1uF)
	- Pour modifier le durée de chaque impulsion = changer R2
	- Bon mix de LDR = 8-16kohm + 10-50kohm
	- ![BirdSoundGenerator01.jpg](../assets/BirdSoundGenerator01_1663622562740_0.jpg)
	-
	- 2022/09/19
	- ![Capture d’écran, le 2022-09-19 à 18.22.30.png](../assets/Capture_d’écran,_le_2022-09-19_à_18.22.30_1663626163963_0.png)
	- Resistor and/or diode can be replaced by LDR
	-
	- Clap switch with microphone
	- ![Capture d’écran, le 2022-09-19 à 18.48.49.png](../assets/Capture_d’écran,_le_2022-09-19_à_18.48.49_1663627760729_0.png)
	- *More sensitive mic + more bright light
	- -> Pour que la LED soit plus bright, choisir un resistor plus petit à mettre juste avant la LED
	  background-color:: #978626
	- ![ClapSwitcch_Mic.jpg](../assets/ClapSwitcch_Mic_1663969559342_0.jpg)
-
-
- TO TRY LATER
  background-color:: #978626
  id:: 6328dde4-426a-47b1-bdfa-07225f4e1298
	- 2022/09/21
	- BC547 equivalent is 2n3904 - Q1
	- BC557 equivalent is 2n3906 - Q2
	- ![Capture d’écran, le 2022-09-20 à 15.51.26.png](../assets/Capture_d’écran,_le_2022-09-20_à_15.51.26_1663703504654_0.png)
	- https://circuitdigest.com/electronic-circuits/simple-motion-detector-circuit-using-555-timer-and-relay-to-control-ac-loads
	-
	- Bird-like sound effect http://solarbotics.net/library/circuits/misc_sound_wilfbird.html
	- ![bird-like.png](../assets/bird-like_1661705347629_0.png)
	-
	- Pummer (light)
	- ![pummer.png](../assets/pummer_1661705413008_0.png)
	-
	- Adjustable auto on/off delay time circuit (555) https://elonics.org/adjustable-auto-on-off-delay-timer-circuit-using-555/
	- ![Capture d’écran, le 2022-08-28 à 13.03.44.png](../assets/Capture_d’écran,_le_2022-08-28_à_13.03.44_1661706247273_0.png)
-
-
- CIRCUITS THAT DIDN'T WORK
  background-color:: #264c9b
  id:: 6328f60e-a2d7-47d6-96c1-da7ab963e387
	- N'a pas fonctionné (2022/09/16)
	- ![Capture d’écran, le 2022-09-16 à 17.22.17.png](../assets/Capture_d’écran,_le_2022-09-16_à_17.22.17_1663363349998_0.png)
	- 2022/09/19
	- N'a pas fonctionné
	- ![Capture d’écran, le 2022-09-19 à 16.03.49.png](../assets/Capture_d’écran,_le_2022-09-19_à_16.03.49_1663617840017_0.png)
	- Scuff Circuit (pas sûre que je peux le faire)
	- ![Capture d’écran, le 2022-09-19 à 17.28.25.png](../assets/Capture_d’écran,_le_2022-09-19_à_17.28.25_1663622915585_0.png)