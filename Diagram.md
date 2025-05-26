```mermaid
flowchart TD
    A[3d Printing]--> B(Steps to begin printing)
    B --> |One|C(3d Model File)
    C --> |One|CA(Find a complete 3d file)
    C --> |Two|CB(Is it the correct file format for printer)
    CA --> D(Slice the Model)
    CB --> D(Slice the Model)
    D --> |One|DA(Set correct print settings on slicer software)
    D --> |Two|DB(Select correct printer and filament type)
    D --> |Three|DC(Export file)
    DA --> E(Review)
    DB --> E(Review)
    DC --> E(Review)
    E --> |One|EA(Confirm printer settings and filament type)
    E --> |Two|EB(Check printer bed and printer nozzle temperatures)
    EA --> F(Printer)
    EB --> F(Printer)
    F --> |One|FA(Clean printer bed)
    F --> |Two|FB(Make sure filament is correctly loaded)
    F --> |Three|FC(Check if nozzle is clear)
    F --> |Four|FD(Make sure the bed is leveled)
    FA --> G(PRINT)
    FB --> G(PRINT)
    FC --> G(PRINT)
    FD --> G(PRINT)
```

#Steps to 3d printing
  -3d Model File
    -Need to find a 3d file that will work with printer
  -Slice the Model
    -Slicing model to correct format so the printer can read it
  -Review
    -Make sure the settings are correct so the printer is able to print it without any problems
  -Printer
    -Make sure the printer physically is ready to print
  -Print
    -Print and wait for results or stop it if any issues occur
