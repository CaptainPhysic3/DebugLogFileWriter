# DebugLogFileWriter
Simple Script to add the ability of writing logs to files

-basic message = DebugLogger.LogInfo({message}) <- script will not prefix this in the log<br>
-warning message = DebugLogger.LogWarning({message}) <- script will prefix this in the log with *WARNING*<br>
-error message = DebugLogger.LogError({message}) <- script will prefix this in the log with *ERROR*<br>
-Enable/Disable Logging = isLoggingEnabled <- Defaults to true

ToDo:
Add Bool to enable or disable file writing
