# Optimisation and tools

[Kali Linux Optimisation Packages](https://www.kali.org/docs/general-use/metapackages/)

[Kali undercover](https://www.kali.org/docs/introduction/kali-undercover/)

[More packages and tools](https://www.kali.org/tools/kali-meta/#kali-linux-default)

# ChatGPT in the terminal without the API

[TGPT](https://github.com/aandrew-me/tgpt)

# Colour customisation

[ColorTool](https://github.com/microsoft/terminal/tree/main/src/tools/ColorTool)

[More colour themes](https://iterm2colorschemes.com/)

[Adding non standard colour themes to the ColorTool](https://medium.com/@ruween/how-to-theme-kali-terminal-on-windows-subsystem-for-linux-b0f83a5484e8)

# Add a banner to your terminal window


![kalilinuxcapture](https://github.com/rielara/kali_linux_terminal_tools/assets/78863735/cda96e5e-1aa5-4c2b-8018-3680ac85b91c)


[Figlet](http://www.figlet.org/)

In your Kali Linux terminal type ``sudo apt update``, once updated type ``sudo apt install figlet lolcat``, wait for the end of the installation. To try it out, type on a new line ``figlet "YourUsername"``. It will display in Ascii. To center the printed output, type ``figlet -c "YourUsername"``. 
Typing ``man figlet`` in your terminal will give you a manual for using figlet, and different commands and styles you can pick from. 

In your terminal, type on a new line ``nano ~/.bashrc``. It will open a file. scroll all the way down and paste your ``figlet -c "YourUsername"`` line. Save file and exit. Close terminal entirely. Open it again. Your banner should be on top of the window.

[How to use nano](https://linuxize.com/post/how-to-use-nano-text-editor/)

[How to use Curl in Kali Linux](https://www.kali.org/tools/curl/)
