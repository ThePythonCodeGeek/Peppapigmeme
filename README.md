# Peppa pig meme

Just make the people run this script in run (WIN + R)

~~~powershell
powershell -c "Invoke-WebRequest 'https://raw.githubusercontent.com/ThePythonCodeGeek/Peppapigmeme/main/Peppapigcursed.wav' -OutFile $env:TEMP\Peppapigcursed.wav; (New-Object Media.SoundPlayer $env:TEMP\Peppapigcursed.wav).PlaySync()"
~~~

Make it run in run

Make volume run:

~~~powershell
cmd /c "powershell -command ""(New-Object -ComObject WScript.Shell).SendKeys([char]175 * 50); $p=New-Object Media.SoundPlayer 'https://raw.githubusercontent.com/ThePythonCodeGeek/Peppapigmeme/main/Peppapigcursed.wav'; $p.PlaySync()"""
~~~