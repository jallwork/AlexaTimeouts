# AlexaTimeouts
How to trap Alexa timeouts in a Python skill

Please see the attached docx file,

Briefly, this shows how to use await asyncio.wait_for() command to capture a timeout before Alexa does!

Example using await asyncio.wait_for(randomTime(), timeout=2.0)

See lambda_function.py for for example code
