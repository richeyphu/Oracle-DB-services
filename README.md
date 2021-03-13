# Oracle-DB-switch
Two simple batch scripts that will turn on/off the Oracle Database services.

## Usage
- Go to `services.msc`
  - Make sure that all `Start up Type` of `Oracle Database` services are set to `Manual`.
    ```services
    - OracleServiceXE
    - OracleOraDB18Home1TNSListener
    - OracleOraDB18Home1MTSRecoveryService
    - OracleVssWriterXE
    ```
  - Restart your PC.
- Run `oracle-start.bat` to start the Oracle Database services.
- Run `oracle-stop.bat` to stop the Oracle Database services.

>***Note*** This was tested in `Oracle Database 18c Express Edition`.
