# Atermiter X79G and Xeon E5-2640 0 EFI for MacOS 11 - 15 (and most likely 26 beta)
OpenCore version - 1.0.5

Hardware Details:
• Platform - Intel LGA 2011, X79 Chipset, Sandy Bridge-E
• Motherboard - Atermiter X79G v1.2 - 1.3
• BIOS - X79GN006
• Processor - Intel® Xeon® E5-2640 0
• Graphics - NVIDIA GeForce GTX 1050 Ti
• Memory - 16GB DDR3 1600 MHz (4x4)
• Ethernet - RTL8111

  ![Uploading Снимок экрана 2025-08-16 в 22.04.01.png…]()![Uploading Снимок экрана 2025-08-16 в 22.05.42.png…]()



When installing MacOS starting with Ventura (13), the cryptexfixup patch is required (it is already present in EFI). Cryptexfixup may not work, although I have found that it works about once out of ten. If it does not work, you will need to manually replace the os.dmg in the preboot section, as described in this detailed guide. (https://youtu.be/0jUsJpzgZnU?si=38hUtEh8Q-LsV-EZ) All components are installed (including nvidia graphics via OCLP), except for the bluetooth from tp-link(ub500).
